# Querying Endpoints<a name="en-us_topic_0057845562"></a>

## Function Description<a name="s81394c6441e2433aa089b83d9ae901bb"></a>

This interface is used to query the list of terminal addresses and provides a service access entry.

## URI<a name="s7f773a8bf34349f5bf81d0c7af9a440d"></a>

-   URI format

    GET /v3/endpoints\{?interface, service\_id\}


-   URI parameter description

    <a name="t3b91158605e2483f8ec0f7e76612766e"></a>
    <table><thead align="left"><tr id="r7c9a4d7646cc40838d1c27ac6a0771ed"><th class="cellrowborder" valign="top" width="20.89%" id="mcps1.1.5.1.1"><p id="a870dd0e09c234313a6279943760cd249"><a name="a870dd0e09c234313a6279943760cd249"></a><a name="a870dd0e09c234313a6279943760cd249"></a><strong id="b37426530113629"><a name="b37426530113629"></a><a name="b37426530113629"></a>Parameter</strong></p>
    </th>
    <th class="cellrowborder" valign="top" width="18.89%" id="mcps1.1.5.1.2"><p id="a3fa42d29543146eda8cc5294eee7152c"><a name="a3fa42d29543146eda8cc5294eee7152c"></a><a name="a3fa42d29543146eda8cc5294eee7152c"></a><strong id="b842352706112524"><a name="b842352706112524"></a><a name="b842352706112524"></a>Mandatory</strong></p>
    </th>
    <th class="cellrowborder" valign="top" width="18.759999999999998%" id="mcps1.1.5.1.3"><p id="a8747c43669bb409782410e7aafd0e8d9"><a name="a8747c43669bb409782410e7aafd0e8d9"></a><a name="a8747c43669bb409782410e7aafd0e8d9"></a><strong id="b84235270615026"><a name="b84235270615026"></a><a name="b84235270615026"></a>Type</strong></p>
    </th>
    <th class="cellrowborder" valign="top" width="41.46%" id="mcps1.1.5.1.4"><p id="a7f591587c22c4b1ebc7dedb7d0d2a0d6"><a name="a7f591587c22c4b1ebc7dedb7d0d2a0d6"></a><a name="a7f591587c22c4b1ebc7dedb7d0d2a0d6"></a><strong id="b14438018113629"><a name="b14438018113629"></a><a name="b14438018113629"></a>Description</strong></p>
    </th>
    </tr>
    </thead>
    <tbody><tr id="rf333d691ffb44900a252228851b25489"><td class="cellrowborder" valign="top" width="20.89%" headers="mcps1.1.5.1.1 "><p id="ae5039ab3eff744ad907f616fc966800e"><a name="ae5039ab3eff744ad907f616fc966800e"></a><a name="ae5039ab3eff744ad907f616fc966800e"></a>interface</p>
    </td>
    <td class="cellrowborder" valign="top" width="18.89%" headers="mcps1.1.5.1.2 "><p id="en-us_topic_0031136110_p768020911147"><a name="en-us_topic_0031136110_p768020911147"></a><a name="en-us_topic_0031136110_p768020911147"></a>No</p>
    </td>
    <td class="cellrowborder" valign="top" width="18.759999999999998%" headers="mcps1.1.5.1.3 "><p id="a4f03dce88dca4b1db054686a2bb07d31"><a name="a4f03dce88dca4b1db054686a2bb07d31"></a><a name="a4f03dce88dca4b1db054686a2bb07d31"></a>String</p>
    </td>
    <td class="cellrowborder" valign="top" width="41.46%" headers="mcps1.1.5.1.4 "><p id="p1833035034212"><a name="p1833035034212"></a><a name="p1833035034212"></a>Plane to which an endpoint belongs.</p>
    <p id="ac5f8e279cf8b4f34bac2ed5df644fbf5"><a name="ac5f8e279cf8b4f34bac2ed5df644fbf5"></a><a name="ac5f8e279cf8b4f34bac2ed5df644fbf5"></a>The value can be <strong id="b842352706195827"><a name="b842352706195827"></a><a name="b842352706195827"></a>public</strong>, <strong id="b842352706195832"><a name="b842352706195832"></a><a name="b842352706195832"></a>internal</strong>, or <strong id="b842352706195837"><a name="b842352706195837"></a><a name="b842352706195837"></a>admin</strong>.</p>
    <a name="ul11999124617111"></a><a name="ul11999124617111"></a><ul id="ul11999124617111"><li><strong id="b842352706195852"><a name="b842352706195852"></a><a name="b842352706195852"></a>public</strong>: Users can view it on the public network interface.</li><li><strong id="b588044409"><a name="b588044409"></a><a name="b588044409"></a>internal</strong>: Users can view it on the internal network interface.</li><li><strong id="b8423527062002"><a name="b8423527062002"></a><a name="b8423527062002"></a>admin</strong>: The administrator can view it on the secure network interface.</li></ul>
    </td>
    </tr>
    <tr id="r9f23e5d0e8de4d70bb3200d16e4f2789"><td class="cellrowborder" valign="top" width="20.89%" headers="mcps1.1.5.1.1 "><p id="a8b74590de667463195f36260f5b8baf9"><a name="a8b74590de667463195f36260f5b8baf9"></a><a name="a8b74590de667463195f36260f5b8baf9"></a>service_id</p>
    </td>
    <td class="cellrowborder" valign="top" width="18.89%" headers="mcps1.1.5.1.2 "><p id="a2e615c570a484ad3bd1572d579904e5e"><a name="a2e615c570a484ad3bd1572d579904e5e"></a><a name="a2e615c570a484ad3bd1572d579904e5e"></a>No</p>
    </td>
    <td class="cellrowborder" valign="top" width="18.759999999999998%" headers="mcps1.1.5.1.3 "><p id="a2b5c563d5b934e40979aac7a0904045c"><a name="a2b5c563d5b934e40979aac7a0904045c"></a><a name="a2b5c563d5b934e40979aac7a0904045c"></a>String</p>
    </td>
    <td class="cellrowborder" valign="top" width="41.46%" headers="mcps1.1.5.1.4 "><p id="en-us_topic_0031136110_p529112711147"><a name="en-us_topic_0031136110_p529112711147"></a><a name="en-us_topic_0031136110_p529112711147"></a>Service ID.</p>
    </td>
    </tr>
    </tbody>
    </table>


## Request<a name="sf86f3f4f84a8493e84f564c16c53eaf3"></a>

-   Request header parameter description

    <a name="tab13448d4b644cd482b72e023e311a4c"></a>
    <table><thead align="left"><tr id="r9cc8c45e565f499a85068ccf812c4906"><th class="cellrowborder" valign="top" width="20.89%" id="mcps1.1.5.1.1"><p id="en-us_topic_0031136110_p289771511147"><a name="en-us_topic_0031136110_p289771511147"></a><a name="en-us_topic_0031136110_p289771511147"></a><strong id="b1731820942"><a name="b1731820942"></a><a name="b1731820942"></a>Parameter</strong></p>
    </th>
    <th class="cellrowborder" valign="top" width="18.759999999999998%" id="mcps1.1.5.1.2"><p id="aa8a52be628254fb799e7d667253339cf"><a name="aa8a52be628254fb799e7d667253339cf"></a><a name="aa8a52be628254fb799e7d667253339cf"></a><strong id="b12871341"><a name="b12871341"></a><a name="b12871341"></a>Mandatory</strong></p>
    </th>
    <th class="cellrowborder" valign="top" width="18.89%" id="mcps1.1.5.1.3"><p id="a8de3dfc3143a4304a1273fade5a53dae"><a name="a8de3dfc3143a4304a1273fade5a53dae"></a><a name="a8de3dfc3143a4304a1273fade5a53dae"></a><strong id="b1996691433"><a name="b1996691433"></a><a name="b1996691433"></a>Type</strong></p>
    </th>
    <th class="cellrowborder" valign="top" width="41.46%" id="mcps1.1.5.1.4"><p id="a51fedaacfb0744a39c0e39893bf93f94"><a name="a51fedaacfb0744a39c0e39893bf93f94"></a><a name="a51fedaacfb0744a39c0e39893bf93f94"></a><strong id="b984032701"><a name="b984032701"></a><a name="b984032701"></a>Description</strong></p>
    </th>
    </tr>
    </thead>
    <tbody><tr id="r439e4c7cd1bc47f5a75d1632d4b0d739"><td class="cellrowborder" valign="top" width="20.89%" headers="mcps1.1.5.1.1 "><p id="a0131df71ca694a6ca73f9ad3a3a794a9"><a name="a0131df71ca694a6ca73f9ad3a3a794a9"></a><a name="a0131df71ca694a6ca73f9ad3a3a794a9"></a>Content-Type</p>
    </td>
    <td class="cellrowborder" valign="top" width="18.759999999999998%" headers="mcps1.1.5.1.2 "><p id="en-us_topic_0031136110_p746938611147"><a name="en-us_topic_0031136110_p746938611147"></a><a name="en-us_topic_0031136110_p746938611147"></a>Yes</p>
    </td>
    <td class="cellrowborder" valign="top" width="18.89%" headers="mcps1.1.5.1.3 "><p id="en-us_topic_0031136110_p104050011147"><a name="en-us_topic_0031136110_p104050011147"></a><a name="en-us_topic_0031136110_p104050011147"></a>String</p>
    </td>
    <td class="cellrowborder" valign="top" width="41.46%" headers="mcps1.1.5.1.4 "><p id="a15c772f0a23d4d52b8f64d1377e3410a"><a name="a15c772f0a23d4d52b8f64d1377e3410a"></a><a name="a15c772f0a23d4d52b8f64d1377e3410a"></a>Fill <strong id="b842352706161331"><a name="b842352706161331"></a><a name="b842352706161331"></a>application/json;charset=utf8</strong> in this field.</p>
    </td>
    </tr>
    <tr id="r80e6b051a95142239d52ef85b3b9e59c"><td class="cellrowborder" valign="top" width="20.89%" headers="mcps1.1.5.1.1 "><p id="a88f9db0a7b6c4b4690378ccf5a787f60"><a name="a88f9db0a7b6c4b4690378ccf5a787f60"></a><a name="a88f9db0a7b6c4b4690378ccf5a787f60"></a>X-Auth-Token</p>
    </td>
    <td class="cellrowborder" valign="top" width="18.759999999999998%" headers="mcps1.1.5.1.2 "><p id="ad6cfd0f57eb643a0afb40a639b4a8515"><a name="ad6cfd0f57eb643a0afb40a639b4a8515"></a><a name="ad6cfd0f57eb643a0afb40a639b4a8515"></a>Yes</p>
    </td>
    <td class="cellrowborder" valign="top" width="18.89%" headers="mcps1.1.5.1.3 "><p id="ac4cc17eda4bf4dd4aa34a5449be8f04e"><a name="ac4cc17eda4bf4dd4aa34a5449be8f04e"></a><a name="ac4cc17eda4bf4dd4aa34a5449be8f04e"></a>String</p>
    </td>
    <td class="cellrowborder" valign="top" width="41.46%" headers="mcps1.1.5.1.4 "><p id="a259cd575002145db850a7dcaf1cbe007"><a name="a259cd575002145db850a7dcaf1cbe007"></a><a name="a259cd575002145db850a7dcaf1cbe007"></a>Authenticated token.</p>
    </td>
    </tr>
    </tbody>
    </table>

-   Sample request

    ```
    curl -i -k -H 'Accept:application/json' -H 'Content-Type:application/json;charset=utf8' -H "X-Auth-Token:$token" -X GET https://172.30.48.86:31943/v3/endpoints?interface=public&service_id=43cbe5e77aaf4665bbb962062dc1fc9d
    ```


## Response<a name="s6e8a35fa777c4de29b376bef459aba1d"></a>

-   Response body parameter description

    <a name="t9b9cc7b83ce9466facb4897baefbd791"></a>
    <table><thead align="left"><tr id="r6f8d72799e954178a1c13b2708d9c121"><th class="cellrowborder" valign="top" width="20.89%" id="mcps1.1.5.1.1"><p id="aadd4863bb2174e1c8719a4c40ab8dfd6"><a name="aadd4863bb2174e1c8719a4c40ab8dfd6"></a><a name="aadd4863bb2174e1c8719a4c40ab8dfd6"></a><strong id="b1855739173"><a name="b1855739173"></a><a name="b1855739173"></a>Parameter</strong></p>
    </th>
    <th class="cellrowborder" valign="top" width="18.89%" id="mcps1.1.5.1.2"><p id="a6f2fff27222d4aedad96357dac77ff93"><a name="a6f2fff27222d4aedad96357dac77ff93"></a><a name="a6f2fff27222d4aedad96357dac77ff93"></a><strong id="b2102488954"><a name="b2102488954"></a><a name="b2102488954"></a>Mandatory</strong></p>
    </th>
    <th class="cellrowborder" valign="top" width="18.63%" id="mcps1.1.5.1.3"><p id="a6083fcf4a1b748159753a8800608d241"><a name="a6083fcf4a1b748159753a8800608d241"></a><a name="a6083fcf4a1b748159753a8800608d241"></a><strong id="b1263755704"><a name="b1263755704"></a><a name="b1263755704"></a>Type</strong></p>
    </th>
    <th class="cellrowborder" valign="top" width="41.589999999999996%" id="mcps1.1.5.1.4"><p id="ae5d4ab162e88407f98ae462ff5f98fce"><a name="ae5d4ab162e88407f98ae462ff5f98fce"></a><a name="ae5d4ab162e88407f98ae462ff5f98fce"></a><strong id="b145061871"><a name="b145061871"></a><a name="b145061871"></a>Description</strong></p>
    </th>
    </tr>
    </thead>
    <tbody><tr id="r16afb2529a6341649de40ef7ff47933c"><td class="cellrowborder" valign="top" width="20.89%" headers="mcps1.1.5.1.1 "><p id="a72924dbd8aa54cda8ab55e77fcb56c30"><a name="a72924dbd8aa54cda8ab55e77fcb56c30"></a><a name="a72924dbd8aa54cda8ab55e77fcb56c30"></a>links</p>
    </td>
    <td class="cellrowborder" valign="top" width="18.89%" headers="mcps1.1.5.1.2 "><p id="a851dfd46f4794e7cad023dcf8504aae2"><a name="a851dfd46f4794e7cad023dcf8504aae2"></a><a name="a851dfd46f4794e7cad023dcf8504aae2"></a>Yes</p>
    </td>
    <td class="cellrowborder" valign="top" width="18.63%" headers="mcps1.1.5.1.3 "><p id="a9363b3ac19a04bab9f845375faaa318c"><a name="a9363b3ac19a04bab9f845375faaa318c"></a><a name="a9363b3ac19a04bab9f845375faaa318c"></a>dict</p>
    </td>
    <td class="cellrowborder" valign="top" width="41.589999999999996%" headers="mcps1.1.5.1.4 "><p id="ae524881a658143949b0abea373ae6c4b"><a name="ae524881a658143949b0abea373ae6c4b"></a><a name="ae524881a658143949b0abea373ae6c4b"></a>Resource links of endpoints.</p>
    </td>
    </tr>
    <tr id="r192d669799e346b696708a75a8dae810"><td class="cellrowborder" valign="top" width="20.89%" headers="mcps1.1.5.1.1 "><p id="add0a344089f5407699a10789a24858fc"><a name="add0a344089f5407699a10789a24858fc"></a><a name="add0a344089f5407699a10789a24858fc"></a>endpoints</p>
    </td>
    <td class="cellrowborder" valign="top" width="18.89%" headers="mcps1.1.5.1.2 "><p id="a4782d8832a9b49e7a2f63f33fdf3c9f1"><a name="a4782d8832a9b49e7a2f63f33fdf3c9f1"></a><a name="a4782d8832a9b49e7a2f63f33fdf3c9f1"></a>Yes</p>
    </td>
    <td class="cellrowborder" valign="top" width="18.63%" headers="mcps1.1.5.1.3 "><p id="a3f160b835d4c46daa70430037fda9c82"><a name="a3f160b835d4c46daa70430037fda9c82"></a><a name="a3f160b835d4c46daa70430037fda9c82"></a>list</p>
    </td>
    <td class="cellrowborder" valign="top" width="41.589999999999996%" headers="mcps1.1.5.1.4 "><p id="en-us_topic_0031136110_p203975521820"><a name="en-us_topic_0031136110_p203975521820"></a><a name="en-us_topic_0031136110_p203975521820"></a>List of endpoints.</p>
    </td>
    </tr>
    </tbody>
    </table>

-   Description for the endpoints format

    <a name="t16022c574b1f456a9e3297282854efaf"></a>
    <table><thead align="left"><tr id="r4133e3880d0440b59b24410f7f89af5d"><th class="cellrowborder" valign="top" width="21.15%" id="mcps1.1.5.1.1"><p id="a7138bee2d8cc41199306dc41c55eb5e8"><a name="a7138bee2d8cc41199306dc41c55eb5e8"></a><a name="a7138bee2d8cc41199306dc41c55eb5e8"></a><strong id="b1503651778"><a name="b1503651778"></a><a name="b1503651778"></a>Parameter</strong></p>
    </th>
    <th class="cellrowborder" valign="top" width="19.03%" id="mcps1.1.5.1.2"><p id="aa07bf7c32f024c11b532cad9df2bf50a"><a name="aa07bf7c32f024c11b532cad9df2bf50a"></a><a name="aa07bf7c32f024c11b532cad9df2bf50a"></a><strong id="b115453887"><a name="b115453887"></a><a name="b115453887"></a>Mandatory</strong></p>
    </th>
    <th class="cellrowborder" valign="top" width="18.360000000000003%" id="mcps1.1.5.1.3"><p id="a1467c9fcdb724143b22fc72f0bfeae9a"><a name="a1467c9fcdb724143b22fc72f0bfeae9a"></a><a name="a1467c9fcdb724143b22fc72f0bfeae9a"></a><strong id="b341737710"><a name="b341737710"></a><a name="b341737710"></a>Type</strong></p>
    </th>
    <th class="cellrowborder" valign="top" width="41.46%" id="mcps1.1.5.1.4"><p id="a9fcabcd69a75432fba32464cdaa09e49"><a name="a9fcabcd69a75432fba32464cdaa09e49"></a><a name="a9fcabcd69a75432fba32464cdaa09e49"></a><strong id="b12244928"><a name="b12244928"></a><a name="b12244928"></a>Description</strong></p>
    </th>
    </tr>
    </thead>
    <tbody><tr id="r15edfdd4c059495cb29238044439d202"><td class="cellrowborder" valign="top" width="21.15%" headers="mcps1.1.5.1.1 "><p id="a2971dbb1a1654dfe85ed54a8d90b22d7"><a name="a2971dbb1a1654dfe85ed54a8d90b22d7"></a><a name="a2971dbb1a1654dfe85ed54a8d90b22d7"></a>id</p>
    </td>
    <td class="cellrowborder" valign="top" width="19.03%" headers="mcps1.1.5.1.2 "><p id="a4170ff579cde4b15b4fbb694f35b3a8d"><a name="a4170ff579cde4b15b4fbb694f35b3a8d"></a><a name="a4170ff579cde4b15b4fbb694f35b3a8d"></a>Yes</p>
    </td>
    <td class="cellrowborder" valign="top" width="18.360000000000003%" headers="mcps1.1.5.1.3 "><p id="af6c77d268cea4449abb3a07fbfe3e64d"><a name="af6c77d268cea4449abb3a07fbfe3e64d"></a><a name="af6c77d268cea4449abb3a07fbfe3e64d"></a>String</p>
    </td>
    <td class="cellrowborder" valign="top" width="41.46%" headers="mcps1.1.5.1.4 "><p id="afd58bdac91854377841b4a27796e3d3a"><a name="afd58bdac91854377841b4a27796e3d3a"></a><a name="afd58bdac91854377841b4a27796e3d3a"></a>Endpoint ID.</p>
    </td>
    </tr>
    <tr id="r77a90cc239f946aaa8b3216933dd7b62"><td class="cellrowborder" valign="top" width="21.15%" headers="mcps1.1.5.1.1 "><p id="aa251ba66310e45ff821ff8fca12d0284"><a name="aa251ba66310e45ff821ff8fca12d0284"></a><a name="aa251ba66310e45ff821ff8fca12d0284"></a>url</p>
    </td>
    <td class="cellrowborder" valign="top" width="19.03%" headers="mcps1.1.5.1.2 "><p id="ae0fd727d9b6c41d4b89ddcac8ccc77da"><a name="ae0fd727d9b6c41d4b89ddcac8ccc77da"></a><a name="ae0fd727d9b6c41d4b89ddcac8ccc77da"></a>Yes</p>
    </td>
    <td class="cellrowborder" valign="top" width="18.360000000000003%" headers="mcps1.1.5.1.3 "><p id="a71143d726f8d4b43937c927aa3b78c12"><a name="a71143d726f8d4b43937c927aa3b78c12"></a><a name="a71143d726f8d4b43937c927aa3b78c12"></a>String</p>
    </td>
    <td class="cellrowborder" valign="top" width="41.46%" headers="mcps1.1.5.1.4 "><p id="a6e58b2fabc424cac9436270e40b8ffc8"><a name="a6e58b2fabc424cac9436270e40b8ffc8"></a><a name="a6e58b2fabc424cac9436270e40b8ffc8"></a>Terminal endpoint URL.</p>
    </td>
    </tr>
    <tr id="rc5fb03f0f6aa4698abeb469bde3835a8"><td class="cellrowborder" valign="top" width="21.15%" headers="mcps1.1.5.1.1 "><p id="a79b6a077c4eb4d929cfefd18246d3f1e"><a name="a79b6a077c4eb4d929cfefd18246d3f1e"></a><a name="a79b6a077c4eb4d929cfefd18246d3f1e"></a>region</p>
    </td>
    <td class="cellrowborder" valign="top" width="19.03%" headers="mcps1.1.5.1.2 "><p id="ad5731f649ce24224854aa29ca4946b5e"><a name="ad5731f649ce24224854aa29ca4946b5e"></a><a name="ad5731f649ce24224854aa29ca4946b5e"></a>Yes</p>
    </td>
    <td class="cellrowborder" valign="top" width="18.360000000000003%" headers="mcps1.1.5.1.3 "><p id="a5d196fdb5fcd4808b2d7e544161bfbcb"><a name="a5d196fdb5fcd4808b2d7e544161bfbcb"></a><a name="a5d196fdb5fcd4808b2d7e544161bfbcb"></a>String</p>
    </td>
    <td class="cellrowborder" valign="top" width="41.46%" headers="mcps1.1.5.1.4 "><p id="a9c85283a25964b44883a0b6d22c6b2f4"><a name="a9c85283a25964b44883a0b6d22c6b2f4"></a><a name="a9c85283a25964b44883a0b6d22c6b2f4"></a>Region to which an endpoint belongs.</p>
    </td>
    </tr>
    <tr id="r2096cd2bc2eb4b8ca39e9fdad2c17abf"><td class="cellrowborder" valign="top" width="21.15%" headers="mcps1.1.5.1.1 "><p id="ad2dcf84f07cc41c38e900a5d90d06739"><a name="ad2dcf84f07cc41c38e900a5d90d06739"></a><a name="ad2dcf84f07cc41c38e900a5d90d06739"></a>region_id</p>
    </td>
    <td class="cellrowborder" valign="top" width="19.03%" headers="mcps1.1.5.1.2 "><p id="ab96b74713e05427c8439edb349ce487a"><a name="ab96b74713e05427c8439edb349ce487a"></a><a name="ab96b74713e05427c8439edb349ce487a"></a>Yes</p>
    </td>
    <td class="cellrowborder" valign="top" width="18.360000000000003%" headers="mcps1.1.5.1.3 "><p id="a075e9acc826c414f8888326b94d78aa7"><a name="a075e9acc826c414f8888326b94d78aa7"></a><a name="a075e9acc826c414f8888326b94d78aa7"></a>String</p>
    </td>
    <td class="cellrowborder" valign="top" width="41.46%" headers="mcps1.1.5.1.4 "><p id="a25e316b867d04d72a0a507269ef030bb"><a name="a25e316b867d04d72a0a507269ef030bb"></a><a name="a25e316b867d04d72a0a507269ef030bb"></a>ID of the region to which an endpoint belongs.</p>
    </td>
    </tr>
    <tr id="r4922ccdb2d08465b94962d83d5228584"><td class="cellrowborder" valign="top" width="21.15%" headers="mcps1.1.5.1.1 "><p id="a64d2d781d0d2410ead11072acb279bb6"><a name="a64d2d781d0d2410ead11072acb279bb6"></a><a name="a64d2d781d0d2410ead11072acb279bb6"></a>enabled</p>
    </td>
    <td class="cellrowborder" valign="top" width="19.03%" headers="mcps1.1.5.1.2 "><p id="a9a7be9e28d194926b1124c08af56e199"><a name="a9a7be9e28d194926b1124c08af56e199"></a><a name="a9a7be9e28d194926b1124c08af56e199"></a>Yes</p>
    </td>
    <td class="cellrowborder" valign="top" width="18.360000000000003%" headers="mcps1.1.5.1.3 "><p id="a049def9b6a2943378b78e42ad2eeceb1"><a name="a049def9b6a2943378b78e42ad2eeceb1"></a><a name="a049def9b6a2943378b78e42ad2eeceb1"></a>Boolean</p>
    </td>
    <td class="cellrowborder" valign="top" width="41.46%" headers="mcps1.1.5.1.4 "><p id="a3064e8830a2043319d9079497d7eb003"><a name="a3064e8830a2043319d9079497d7eb003"></a><a name="a3064e8830a2043319d9079497d7eb003"></a>Whether an endpoint is available.</p>
    </td>
    </tr>
    <tr id="r6344aee994a24051be58519d4c9cfb9e"><td class="cellrowborder" valign="top" width="21.15%" headers="mcps1.1.5.1.1 "><p id="a43498c3cf2104e84a79c19749889d933"><a name="a43498c3cf2104e84a79c19749889d933"></a><a name="a43498c3cf2104e84a79c19749889d933"></a>interface</p>
    </td>
    <td class="cellrowborder" valign="top" width="19.03%" headers="mcps1.1.5.1.2 "><p id="a0b3a5427e0db43cc99daa7176081c580"><a name="a0b3a5427e0db43cc99daa7176081c580"></a><a name="a0b3a5427e0db43cc99daa7176081c580"></a>Yes</p>
    </td>
    <td class="cellrowborder" valign="top" width="18.360000000000003%" headers="mcps1.1.5.1.3 "><p id="ac579d4c833b34b309dbad0e5e89f099c"><a name="ac579d4c833b34b309dbad0e5e89f099c"></a><a name="ac579d4c833b34b309dbad0e5e89f099c"></a>String</p>
    </td>
    <td class="cellrowborder" valign="top" width="41.46%" headers="mcps1.1.5.1.4 "><p id="a381f50159a6147319a9614014bd1f239"><a name="a381f50159a6147319a9614014bd1f239"></a><a name="a381f50159a6147319a9614014bd1f239"></a>Plane to which an endpoint belongs.</p>
    </td>
    </tr>
    <tr id="r9940352ff08f494091659e4c40ae85f1"><td class="cellrowborder" valign="top" width="21.15%" headers="mcps1.1.5.1.1 "><p id="a6a5ef091076949d8ae3d40e1fedd37e5"><a name="a6a5ef091076949d8ae3d40e1fedd37e5"></a><a name="a6a5ef091076949d8ae3d40e1fedd37e5"></a>service_id</p>
    </td>
    <td class="cellrowborder" valign="top" width="19.03%" headers="mcps1.1.5.1.2 "><p id="a372888c6e85e48e7876fe01b6240ae04"><a name="a372888c6e85e48e7876fe01b6240ae04"></a><a name="a372888c6e85e48e7876fe01b6240ae04"></a>Yes</p>
    </td>
    <td class="cellrowborder" valign="top" width="18.360000000000003%" headers="mcps1.1.5.1.3 "><p id="aa0bc2dc415544308b924a959dcebcff9"><a name="aa0bc2dc415544308b924a959dcebcff9"></a><a name="aa0bc2dc415544308b924a959dcebcff9"></a>String</p>
    </td>
    <td class="cellrowborder" valign="top" width="41.46%" headers="mcps1.1.5.1.4 "><p id="aba5234bd2cad42579cc42dd2bc9d9e5d"><a name="aba5234bd2cad42579cc42dd2bc9d9e5d"></a><a name="aba5234bd2cad42579cc42dd2bc9d9e5d"></a>ID of the service to which an endpoint belongs.</p>
    </td>
    </tr>
    <tr id="r1524ca29ae2241558138b4bd41f0c804"><td class="cellrowborder" valign="top" width="21.15%" headers="mcps1.1.5.1.1 "><p id="en-us_topic_0031136110_p719542217241"><a name="en-us_topic_0031136110_p719542217241"></a><a name="en-us_topic_0031136110_p719542217241"></a>links</p>
    </td>
    <td class="cellrowborder" valign="top" width="19.03%" headers="mcps1.1.5.1.2 "><p id="a233563f9d238407b9b6572e26d5dbdd6"><a name="a233563f9d238407b9b6572e26d5dbdd6"></a><a name="a233563f9d238407b9b6572e26d5dbdd6"></a>Yes</p>
    </td>
    <td class="cellrowborder" valign="top" width="18.360000000000003%" headers="mcps1.1.5.1.3 "><p id="a1fca8face8944d9c999fa0c684918e71"><a name="a1fca8face8944d9c999fa0c684918e71"></a><a name="a1fca8face8944d9c999fa0c684918e71"></a>dict</p>
    </td>
    <td class="cellrowborder" valign="top" width="41.46%" headers="mcps1.1.5.1.4 "><p id="a5454237eb6554868a596bf506fa32964"><a name="a5454237eb6554868a596bf506fa32964"></a><a name="a5454237eb6554868a596bf506fa32964"></a>Resource links of endpoints.</p>
    </td>
    </tr>
    </tbody>
    </table>

-   Sample response \(successful request\)

    ```
    {
        "endpoints": [
            {
                "region_id": null,
                "links": {
                    "self": "https://iamcore_links.com/v3/endpoints/162277d696f54cf592f19b569f85d158"
                },
                "url": "https://10.185.190.104:7443/v3",
                "region": null,
                "enabled": true,
                "interface": "public",
                "service_id": "053d21d488d1463c818132d9d08fb617",
                "id": "162277d696f54cf592f19b569f85d158"
            }
        ],
        "links": {
            "self": "https://iamcore_links.com/v3/endpoints?service_id=053d21d488d1463c818132d9d08fb617&interface=public",
            "previous": null,
            "next": null
        }
    }
    ```


## Status Codes<a name="s161ee4f22c7a4e5f928bf049a4425742"></a>

<a name="en-us_topic_0031136110_table25927028"></a>
<table><thead align="left"><tr id="en-us_topic_0031136110_row10578662"><th class="cellrowborder" valign="top" width="50%" id="mcps1.1.3.1.1"><p id="en-us_topic_0031136110_p51565323"><a name="en-us_topic_0031136110_p51565323"></a><a name="en-us_topic_0031136110_p51565323"></a><strong id="b37151362163018"><a name="b37151362163018"></a><a name="b37151362163018"></a>Status Code</strong></p>
</th>
<th class="cellrowborder" valign="top" width="50%" id="mcps1.1.3.1.2"><p id="en-us_topic_0031136110_p16041657"><a name="en-us_topic_0031136110_p16041657"></a><a name="en-us_topic_0031136110_p16041657"></a><strong id="b38470707163018"><a name="b38470707163018"></a><a name="b38470707163018"></a>Description</strong></p>
</th>
</tr>
</thead>
<tbody><tr id="en-us_topic_0031136110_row24305815"><td class="cellrowborder" valign="top" width="50%" headers="mcps1.1.3.1.1 "><p id="en-us_topic_0031136110_p22613965"><a name="en-us_topic_0031136110_p22613965"></a><a name="en-us_topic_0031136110_p22613965"></a>200</p>
</td>
<td class="cellrowborder" valign="top" width="50%" headers="mcps1.1.3.1.2 "><p id="en-us_topic_0031136110_p19791876"><a name="en-us_topic_0031136110_p19791876"></a><a name="en-us_topic_0031136110_p19791876"></a>The request is successful.</p>
</td>
</tr>
<tr id="en-us_topic_0031136110_row43909159"><td class="cellrowborder" valign="top" width="50%" headers="mcps1.1.3.1.1 "><p id="en-us_topic_0031136110_p66980994"><a name="en-us_topic_0031136110_p66980994"></a><a name="en-us_topic_0031136110_p66980994"></a>400</p>
</td>
<td class="cellrowborder" valign="top" width="50%" headers="mcps1.1.3.1.2 "><p id="en-us_topic_0031136110_p56751409"><a name="en-us_topic_0031136110_p56751409"></a><a name="en-us_topic_0031136110_p56751409"></a>The server failed to process the request.</p>
</td>
</tr>
<tr id="re5868592b58a49148d1e374ab0ee4186"><td class="cellrowborder" valign="top" width="50%" headers="mcps1.1.3.1.1 "><p id="a67da088f332e48ca9c70f3ba30897dde"><a name="a67da088f332e48ca9c70f3ba30897dde"></a><a name="a67da088f332e48ca9c70f3ba30897dde"></a>401</p>
</td>
<td class="cellrowborder" valign="top" width="50%" headers="mcps1.1.3.1.2 "><p id="a0525ff08629b4648808d6e876aaf9c5f"><a name="a0525ff08629b4648808d6e876aaf9c5f"></a><a name="a0525ff08629b4648808d6e876aaf9c5f"></a>You must enter a username and password to access the requested page.</p>
</td>
</tr>
<tr id="en-us_topic_0031136110_row41000636"><td class="cellrowborder" valign="top" width="50%" headers="mcps1.1.3.1.1 "><p id="en-us_topic_0031136110_p32717189"><a name="en-us_topic_0031136110_p32717189"></a><a name="en-us_topic_0031136110_p32717189"></a>403</p>
</td>
<td class="cellrowborder" valign="top" width="50%" headers="mcps1.1.3.1.2 "><p id="a98f74bf5eda646c6a5973dfa742126c4"><a name="a98f74bf5eda646c6a5973dfa742126c4"></a><a name="a98f74bf5eda646c6a5973dfa742126c4"></a>You are forbidden to access the requested page.</p>
</td>
</tr>
<tr id="r40e82c2469d34bf089fe9bfb0fa81526"><td class="cellrowborder" valign="top" width="50%" headers="mcps1.1.3.1.1 "><p id="a8be4e075b25144a38cbe0ff05c2b2f15"><a name="a8be4e075b25144a38cbe0ff05c2b2f15"></a><a name="a8be4e075b25144a38cbe0ff05c2b2f15"></a>404</p>
</td>
<td class="cellrowborder" valign="top" width="50%" headers="mcps1.1.3.1.2 "><p id="a5147e7c96ca94cb882828f2c4a33c1dc"><a name="a5147e7c96ca94cb882828f2c4a33c1dc"></a><a name="a5147e7c96ca94cb882828f2c4a33c1dc"></a>The server could not find the requested page.</p>
</td>
</tr>
<tr id="r6ae77ec5e12645e0a53aa0f3be73d1a9"><td class="cellrowborder" valign="top" width="50%" headers="mcps1.1.3.1.1 "><p id="a61cb90ae8ac1482f83a82028556bbee5"><a name="a61cb90ae8ac1482f83a82028556bbee5"></a><a name="a61cb90ae8ac1482f83a82028556bbee5"></a>405</p>
</td>
<td class="cellrowborder" valign="top" width="50%" headers="mcps1.1.3.1.2 "><p id="a41bd1c94c1ba4153b7346917bc58b6b3"><a name="a41bd1c94c1ba4153b7346917bc58b6b3"></a><a name="a41bd1c94c1ba4153b7346917bc58b6b3"></a>You are not allowed to use the method specified in the request.</p>
</td>
</tr>
<tr id="rbea4e490c384410e8d1210ca41179e16"><td class="cellrowborder" valign="top" width="50%" headers="mcps1.1.3.1.1 "><p id="a9eaf1c04680e4901822818bfe53ee0fc"><a name="a9eaf1c04680e4901822818bfe53ee0fc"></a><a name="a9eaf1c04680e4901822818bfe53ee0fc"></a>413</p>
</td>
<td class="cellrowborder" valign="top" width="50%" headers="mcps1.1.3.1.2 "><p id="a5e2acac6d93f406caa8cb7f89f4b0e4d"><a name="a5e2acac6d93f406caa8cb7f89f4b0e4d"></a><a name="a5e2acac6d93f406caa8cb7f89f4b0e4d"></a>The request entity is too large.</p>
</td>
</tr>
<tr id="r3b34616283144b19899b01b4552b799c"><td class="cellrowborder" valign="top" width="50%" headers="mcps1.1.3.1.1 "><p id="a898bb41bdd874b25b452c9fd609e5bc0"><a name="a898bb41bdd874b25b452c9fd609e5bc0"></a><a name="a898bb41bdd874b25b452c9fd609e5bc0"></a>500</p>
</td>
<td class="cellrowborder" valign="top" width="50%" headers="mcps1.1.3.1.2 "><p id="ad43eae2906e84b6fb48fb6c11746dfab"><a name="ad43eae2906e84b6fb48fb6c11746dfab"></a><a name="ad43eae2906e84b6fb48fb6c11746dfab"></a>Failed to complete the request because of an internal service error.</p>
</td>
</tr>
<tr id="r73ae10963ce24ea09cafcfec5f21c2ab"><td class="cellrowborder" valign="top" width="50%" headers="mcps1.1.3.1.1 "><p id="a3f2f513363a24dcb87462518dff622e7"><a name="a3f2f513363a24dcb87462518dff622e7"></a><a name="a3f2f513363a24dcb87462518dff622e7"></a>503</p>
</td>
<td class="cellrowborder" valign="top" width="50%" headers="mcps1.1.3.1.2 "><p id="a642a35bd05f24df68588a7f13c7cb3b7"><a name="a642a35bd05f24df68588a7f13c7cb3b7"></a><a name="a642a35bd05f24df68588a7f13c7cb3b7"></a>Failed to complete the request because the service is unavailable.</p>
</td>
</tr>
</tbody>
</table>

