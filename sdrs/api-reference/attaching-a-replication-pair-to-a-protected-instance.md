# Attaching a Replication Pair to a Protected Instance<a name="sdrs_05_0506"></a>

## Function<a name="en-us_topic_0079693002_section34649765"></a>

This API is used to attach the specified replication pair to the specified protected instance.

## Constraints and Limitations<a name="section1479914268378"></a>

-   **status**  of the protection group must be  **available**  or  **protected**.
-   **status**  of the protected instance must be  **available**  or  **protected**.
-   **status**  of the replication pair must be  **available**  or  **protected**.
-   The non-shared replication pair has not been attached to any protected instance.

## URI<a name="en-us_topic_0079693002_section39390935"></a>

-   URI format

    POST /v1/\{project\_id\}/protected-instances/\{protected\_instance\_id\}/attachreplication

-   Parameter description

    <a name="en-us_topic_0079693002_table63321005"></a>
    <table><thead align="left"><tr id="en-us_topic_0079693002_row37593218"><th class="cellrowborder" valign="top" width="17.82178217821782%" id="mcps1.1.5.1.1"><p id="p1346872192510"><a name="p1346872192510"></a><a name="p1346872192510"></a>Parameter</p>
    </th>
    <th class="cellrowborder" valign="top" width="15.841584158415841%" id="mcps1.1.5.1.2"><p id="p746872172511"><a name="p746872172511"></a><a name="p746872172511"></a>Mandatory</p>
    </th>
    <th class="cellrowborder" valign="top" width="16.831683168316832%" id="mcps1.1.5.1.3"><p id="p194681724259"><a name="p194681724259"></a><a name="p194681724259"></a>Type</p>
    </th>
    <th class="cellrowborder" valign="top" width="49.504950495049506%" id="mcps1.1.5.1.4"><p id="p1946815216252"><a name="p1946815216252"></a><a name="p1946815216252"></a>Description</p>
    </th>
    </tr>
    </thead>
    <tbody><tr id="en-us_topic_0079693002_row29123463"><td class="cellrowborder" valign="top" width="17.82178217821782%" headers="mcps1.1.5.1.1 "><p id="p144685282514"><a name="p144685282514"></a><a name="p144685282514"></a>project_id</p>
    </td>
    <td class="cellrowborder" valign="top" width="15.841584158415841%" headers="mcps1.1.5.1.2 "><p id="p7468132162510"><a name="p7468132162510"></a><a name="p7468132162510"></a>Yes</p>
    </td>
    <td class="cellrowborder" valign="top" width="16.831683168316832%" headers="mcps1.1.5.1.3 "><p id="p184681252517"><a name="p184681252517"></a><a name="p184681252517"></a>String</p>
    </td>
    <td class="cellrowborder" valign="top" width="49.504950495049506%" headers="mcps1.1.5.1.4 "><p id="p3468182182513"><a name="p3468182182513"></a><a name="p3468182182513"></a>Specifies the project ID.</p>
    </td>
    </tr>
    <tr id="row13416191664314"><td class="cellrowborder" valign="top" width="17.82178217821782%" headers="mcps1.1.5.1.1 "><p id="p74691827251"><a name="p74691827251"></a><a name="p74691827251"></a>protected_instance_id</p>
    </td>
    <td class="cellrowborder" valign="top" width="15.841584158415841%" headers="mcps1.1.5.1.2 "><p id="p34691524255"><a name="p34691524255"></a><a name="p34691524255"></a>Yes</p>
    </td>
    <td class="cellrowborder" valign="top" width="16.831683168316832%" headers="mcps1.1.5.1.3 "><p id="p1746919232516"><a name="p1746919232516"></a><a name="p1746919232516"></a>String</p>
    </td>
    <td class="cellrowborder" valign="top" width="49.504950495049506%" headers="mcps1.1.5.1.4 "><p id="p0469202102519"><a name="p0469202102519"></a><a name="p0469202102519"></a>Specifies the ID of a protected instance.</p>
    <p id="p548112512436"><a name="p548112512436"></a><a name="p548112512436"></a>You can obtain this value by calling the API described in <a href="querying-protected-instances.md">Querying Protected Instances</a>.</p>
    </td>
    </tr>
    </tbody>
    </table>


## Request<a name="en-us_topic_0079693002_section18974100"></a>

-   Parameter description

    <a name="en-us_topic_0079693002_table54932709"></a>
    <table><thead align="left"><tr id="en-us_topic_0079693002_row41882373"><th class="cellrowborder" valign="top" width="25%" id="mcps1.1.5.1.1"><p id="en-us_topic_0079693002_p8696081161227"><a name="en-us_topic_0079693002_p8696081161227"></a><a name="en-us_topic_0079693002_p8696081161227"></a>Parameter</p>
    </th>
    <th class="cellrowborder" valign="top" width="14.000000000000002%" id="mcps1.1.5.1.2"><p id="en-us_topic_0079693002_p33293980161227"><a name="en-us_topic_0079693002_p33293980161227"></a><a name="en-us_topic_0079693002_p33293980161227"></a>Mandatory</p>
    </th>
    <th class="cellrowborder" valign="top" width="15%" id="mcps1.1.5.1.3"><p id="en-us_topic_0079693002_p12457872161227"><a name="en-us_topic_0079693002_p12457872161227"></a><a name="en-us_topic_0079693002_p12457872161227"></a>Type</p>
    </th>
    <th class="cellrowborder" valign="top" width="46%" id="mcps1.1.5.1.4"><p id="en-us_topic_0079693002_p2454675161227"><a name="en-us_topic_0079693002_p2454675161227"></a><a name="en-us_topic_0079693002_p2454675161227"></a>Description</p>
    </th>
    </tr>
    </thead>
    <tbody><tr id="en-us_topic_0079693002_row27990155"><td class="cellrowborder" valign="top" width="25%" headers="mcps1.1.5.1.1 "><p id="p18603123510433"><a name="p18603123510433"></a><a name="p18603123510433"></a>replicationAttachment</p>
    </td>
    <td class="cellrowborder" valign="top" width="14.000000000000002%" headers="mcps1.1.5.1.2 "><p id="p126031135114313"><a name="p126031135114313"></a><a name="p126031135114313"></a>Yes</p>
    </td>
    <td class="cellrowborder" valign="top" width="15%" headers="mcps1.1.5.1.3 "><p id="p18603193514313"><a name="p18603193514313"></a><a name="p18603193514313"></a>Object</p>
    </td>
    <td class="cellrowborder" valign="top" width="46%" headers="mcps1.1.5.1.4 "><p id="p5603203554316"><a name="p5603203554316"></a><a name="p5603203554316"></a>Attaches a replication pair to a protected instance.</p>
    <p id="p9878151113468"><a name="p9878151113468"></a><a name="p9878151113468"></a>For details, see <a href="#table1470881204413">Table 1</a>.</p>
    </td>
    </tr>
    </tbody>
    </table>

    **Table  1** **replicationAttachment**  field description

    <a name="table1470881204413"></a>
    <table><thead align="left"><tr id="row197221212114410"><th class="cellrowborder" valign="top" width="25%" id="mcps1.2.5.1.1"><p id="p872581254415"><a name="p872581254415"></a><a name="p872581254415"></a>Parameter</p>
    </th>
    <th class="cellrowborder" valign="top" width="14.000000000000002%" id="mcps1.2.5.1.2"><p id="p147298120446"><a name="p147298120446"></a><a name="p147298120446"></a>Mandatory</p>
    </th>
    <th class="cellrowborder" valign="top" width="15%" id="mcps1.2.5.1.3"><p id="p13734141294415"><a name="p13734141294415"></a><a name="p13734141294415"></a>Type</p>
    </th>
    <th class="cellrowborder" valign="top" width="46%" id="mcps1.2.5.1.4"><p id="p17737111215440"><a name="p17737111215440"></a><a name="p17737111215440"></a>Description</p>
    </th>
    </tr>
    </thead>
    <tbody><tr id="row127401512204411"><td class="cellrowborder" valign="top" width="25%" headers="mcps1.2.5.1.1 "><p id="p15319115616257"><a name="p15319115616257"></a><a name="p15319115616257"></a>replication_id</p>
    </td>
    <td class="cellrowborder" valign="top" width="14.000000000000002%" headers="mcps1.2.5.1.2 "><p id="p11319145617251"><a name="p11319145617251"></a><a name="p11319145617251"></a>Yes</p>
    </td>
    <td class="cellrowborder" valign="top" width="15%" headers="mcps1.2.5.1.3 "><p id="p1431905622518"><a name="p1431905622518"></a><a name="p1431905622518"></a>String</p>
    </td>
    <td class="cellrowborder" valign="top" width="46%" headers="mcps1.2.5.1.4 "><p id="p2031955615250"><a name="p2031955615250"></a><a name="p2031955615250"></a>Specifies the ID of a replication pair.</p>
    <p id="p16929164515"><a name="p16929164515"></a><a name="p16929164515"></a>You can obtain this value by calling the API described in <a href="querying-replication-pairs.md">Querying Replication Pairs</a>.</p>
    </td>
    </tr>
    <tr id="row641154810250"><td class="cellrowborder" valign="top" width="25%" headers="mcps1.2.5.1.1 "><p id="p17319185615255"><a name="p17319185615255"></a><a name="p17319185615255"></a>device</p>
    </td>
    <td class="cellrowborder" valign="top" width="14.000000000000002%" headers="mcps1.2.5.1.2 "><p id="p183191256112517"><a name="p183191256112517"></a><a name="p183191256112517"></a>Yes</p>
    </td>
    <td class="cellrowborder" valign="top" width="15%" headers="mcps1.2.5.1.3 "><p id="p13195563256"><a name="p13195563256"></a><a name="p13195563256"></a>String</p>
    </td>
    <td class="cellrowborder" valign="top" width="46%" headers="mcps1.2.5.1.4 "><p id="p179035435915"><a name="p179035435915"></a><a name="p179035435915"></a>Specifies the disk device name of a replication pair.</p>
    <div class="note" id="note1755312117111"><a name="note1755312117111"></a><a name="note1755312117111"></a><span class="notetitle"> NOTE: </span><div class="notebody"><a name="ul1580711965"></a><a name="ul1580711965"></a><ul id="ul1580711965"><li>The new disk device name cannot be the same as an existing one.</li><li>Set the parameter value to <strong id="b18233182041819"><a name="b18233182041819"></a><a name="b18233182041819"></a>/dev/sda</strong> for the system disks of protected instances created using Xen <span id="text396571623"><a name="text396571623"></a><a name="text396571623"></a>server</span><span id="text1735681415216"><a name="text1735681415216"></a><a name="text1735681415216"></a></span>s and to <strong id="b16234520201811"><a name="b16234520201811"></a><a name="b16234520201811"></a>/dev/sd</strong><em id="i16235202071811"><a name="i16235202071811"></a><a name="i16235202071811"></a>x</em> for data disks, where <em id="i52362020171818"><a name="i52362020171818"></a><a name="i52362020171818"></a>x</em> is a letter in alphabetical order. For example, if there are two data disks, set the device names of the two data disks to <strong id="b023612204187"><a name="b023612204187"></a><a name="b023612204187"></a>/dev/sdb</strong> and <strong id="b923772012186"><a name="b923772012186"></a><a name="b923772012186"></a>/dev/sdc</strong>, respectively. If you set a device name starting with <strong id="b10238202016189"><a name="b10238202016189"></a><a name="b10238202016189"></a>/dev/vd</strong>, the system uses <strong id="b7238220131811"><a name="b7238220131811"></a><a name="b7238220131811"></a>/dev/sd</strong> by default.</li><li>Set the parameter value to <strong id="b825819192291"><a name="b825819192291"></a><a name="b825819192291"></a>/dev/vda</strong> for the system disks of protected instances created using KVM <span id="text9347720827"><a name="text9347720827"></a><a name="text9347720827"></a></span><span id="text4347142014211"><a name="text4347142014211"></a><a name="text4347142014211"></a>server</span>s and to <strong id="b3259151913294"><a name="b3259151913294"></a><a name="b3259151913294"></a>/dev/vd</strong><em id="i2259161915298"><a name="i2259161915298"></a><a name="i2259161915298"></a>x</em> for data disks, where <em id="i3260619192919"><a name="i3260619192919"></a><a name="i3260619192919"></a>x</em> is a letter in alphabetical order. For example, if there are two data disks, set the device names of the two data disks to <strong id="b62601919122910"><a name="b62601919122910"></a><a name="b62601919122910"></a>/dev/vdb</strong> and <strong id="b226141917299"><a name="b226141917299"></a><a name="b226141917299"></a>/dev/vdc</strong>, respectively. If you set a device name starting with <strong id="b6262151918295"><a name="b6262151918295"></a><a name="b6262151918295"></a>/dev/sd</strong>, the system uses <strong id="b16262719202911"><a name="b16262719202911"></a><a name="b16262719202911"></a>/dev/vd</strong> by default.</li></ul>
    </div></div>
    </td>
    </tr>
    </tbody>
    </table>


-   Example request

    POST https://\{Endpoint\}/v1/\{project\_id\}/protected-instances/00000000632302f501632305f63c000e/attachreplication

    ```
    { 
         "replicationAttachment": { 
            "replication_id": "6568f7c4-0510-4f39-929d-8ffccbd4fd47",
            "device": "/dev/vda"
         } 
     }
    ```


## Response<a name="en-us_topic_0079693002_section36549175"></a>

-   Parameter description

    <a name="table155991608555"></a>
    <table><thead align="left"><tr id="row460510055518"><th class="cellrowborder" valign="top" width="29.07%" id="mcps1.1.4.1.1"><p id="p137011644152620"><a name="p137011644152620"></a><a name="p137011644152620"></a>Parameter</p>
    </th>
    <th class="cellrowborder" valign="top" width="17.44%" id="mcps1.1.4.1.2"><p id="p77031644192610"><a name="p77031644192610"></a><a name="p77031644192610"></a>Type</p>
    </th>
    <th class="cellrowborder" valign="top" width="53.49%" id="mcps1.1.4.1.3"><p id="p970334482618"><a name="p970334482618"></a><a name="p970334482618"></a>Description</p>
    </th>
    </tr>
    </thead>
    <tbody><tr id="row86164025512"><td class="cellrowborder" valign="top" width="29.07%" headers="mcps1.1.4.1.1 "><p id="p870374412614"><a name="p870374412614"></a><a name="p870374412614"></a>job_id</p>
    </td>
    <td class="cellrowborder" valign="top" width="17.44%" headers="mcps1.1.4.1.2 "><p id="p17703174482616"><a name="p17703174482616"></a><a name="p17703174482616"></a>String</p>
    </td>
    <td class="cellrowborder" valign="top" width="53.49%" headers="mcps1.1.4.1.3 "><p id="p16703184492610"><a name="p16703184492610"></a><a name="p16703184492610"></a>Specifies the job ID.</p>
    <p id="p10486911173216"><a name="p10486911173216"></a><a name="p10486911173216"></a>This is a returned parameter when the asynchronous API command is issued successfully. For details about the task execution result, see the description in <a href="querying-the-job-status.md">Querying the Job Status</a>.</p>
    </td>
    </tr>
    </tbody>
    </table>

-   Example response

    ```
    { 
       "job_id": "0000000062db92d70162db9d200f00bb" 
     }
    ```

    Or

    ```
    { 
         "error": { 
             "message": "XXXX",  
             "code": "XXX" 
         } 
     }
    ```

    In this example,  **error**  represents a general error, including  **badrequest**  \(shown below\) and  **itemNotFound**.

    ```
    { 
         "badrequest": { 
             "message": "XXXX",  
             "code": "XXX" 
         } 
     }
    ```


## Returned Values<a name="en-us_topic_0079693002_section60507121"></a>

-   Normal

    <a name="sdrs_05_0101_table4315991194956"></a>
    <table><thead align="left"><tr id="sdrs_05_0101_row2336641294956"><th class="cellrowborder" valign="top" width="42.59%" id="mcps1.1.3.1.1"><p id="sdrs_05_0101_p1363125894956"><a name="sdrs_05_0101_p1363125894956"></a><a name="sdrs_05_0101_p1363125894956"></a>Returned Value</p>
    </th>
    <th class="cellrowborder" valign="top" width="57.410000000000004%" id="mcps1.1.3.1.2"><p id="sdrs_05_0101_p3039012494956"><a name="sdrs_05_0101_p3039012494956"></a><a name="sdrs_05_0101_p3039012494956"></a>Description</p>
    </th>
    </tr>
    </thead>
    <tbody><tr id="sdrs_05_0101_row507566794956"><td class="cellrowborder" valign="top" width="42.59%" headers="mcps1.1.3.1.1 "><p id="sdrs_05_0101_p847584694956"><a name="sdrs_05_0101_p847584694956"></a><a name="sdrs_05_0101_p847584694956"></a>200</p>
    </td>
    <td class="cellrowborder" valign="top" width="57.410000000000004%" headers="mcps1.1.3.1.2 "><p id="sdrs_05_0101_p1545496394956"><a name="sdrs_05_0101_p1545496394956"></a><a name="sdrs_05_0101_p1545496394956"></a>The server has accepted the request.</p>
    </td>
    </tr>
    </tbody>
    </table>

-   Abnormal

    <a name="sdrs_05_0101_table22458872203835"></a>
    <table><thead align="left"><tr id="sdrs_05_0101_row35704554203835"><th class="cellrowborder" valign="top" width="43.419999999999995%" id="mcps1.1.3.1.1"><p id="sdrs_05_0101_p6387753203835"><a name="sdrs_05_0101_p6387753203835"></a><a name="sdrs_05_0101_p6387753203835"></a>Returned Value</p>
    </th>
    <th class="cellrowborder" valign="top" width="56.58%" id="mcps1.1.3.1.2"><p id="sdrs_05_0101_p47646009203835"><a name="sdrs_05_0101_p47646009203835"></a><a name="sdrs_05_0101_p47646009203835"></a>Description</p>
    </th>
    </tr>
    </thead>
    <tbody><tr id="sdrs_05_0101_row34121538203835"><td class="cellrowborder" valign="top" width="43.419999999999995%" headers="mcps1.1.3.1.1 "><p id="sdrs_05_0101_p12381163203835"><a name="sdrs_05_0101_p12381163203835"></a><a name="sdrs_05_0101_p12381163203835"></a>400 Bad Request</p>
    </td>
    <td class="cellrowborder" valign="top" width="56.58%" headers="mcps1.1.3.1.2 "><p id="sdrs_05_0101_p63350108203835"><a name="sdrs_05_0101_p63350108203835"></a><a name="sdrs_05_0101_p63350108203835"></a>The server failed to process the request.</p>
    </td>
    </tr>
    <tr id="sdrs_05_0101_row33280063203835"><td class="cellrowborder" valign="top" width="43.419999999999995%" headers="mcps1.1.3.1.1 "><p id="sdrs_05_0101_p11330608203835"><a name="sdrs_05_0101_p11330608203835"></a><a name="sdrs_05_0101_p11330608203835"></a>401 Unauthorized</p>
    </td>
    <td class="cellrowborder" valign="top" width="56.58%" headers="mcps1.1.3.1.2 "><p id="sdrs_05_0101_p45364094203835"><a name="sdrs_05_0101_p45364094203835"></a><a name="sdrs_05_0101_p45364094203835"></a>You must enter a username and the password to access the requested page.</p>
    </td>
    </tr>
    <tr id="sdrs_05_0101_row5623667203835"><td class="cellrowborder" valign="top" width="43.419999999999995%" headers="mcps1.1.3.1.1 "><p id="sdrs_05_0101_p52863895203835"><a name="sdrs_05_0101_p52863895203835"></a><a name="sdrs_05_0101_p52863895203835"></a>403 Forbidden</p>
    </td>
    <td class="cellrowborder" valign="top" width="56.58%" headers="mcps1.1.3.1.2 "><p id="sdrs_05_0101_p54117066203835"><a name="sdrs_05_0101_p54117066203835"></a><a name="sdrs_05_0101_p54117066203835"></a>You are forbidden to access the requested page.</p>
    </td>
    </tr>
    <tr id="sdrs_05_0101_row17291554203835"><td class="cellrowborder" valign="top" width="43.419999999999995%" headers="mcps1.1.3.1.1 "><p id="sdrs_05_0101_p58438642203835"><a name="sdrs_05_0101_p58438642203835"></a><a name="sdrs_05_0101_p58438642203835"></a>404 Not Found</p>
    </td>
    <td class="cellrowborder" valign="top" width="56.58%" headers="mcps1.1.3.1.2 "><p id="sdrs_05_0101_p35909542203835"><a name="sdrs_05_0101_p35909542203835"></a><a name="sdrs_05_0101_p35909542203835"></a>The server could not find the requested page.</p>
    </td>
    </tr>
    <tr id="sdrs_05_0101_row54750425203835"><td class="cellrowborder" valign="top" width="43.419999999999995%" headers="mcps1.1.3.1.1 "><p id="sdrs_05_0101_p5599455203835"><a name="sdrs_05_0101_p5599455203835"></a><a name="sdrs_05_0101_p5599455203835"></a>405 Method Not Allowed</p>
    </td>
    <td class="cellrowborder" valign="top" width="56.58%" headers="mcps1.1.3.1.2 "><p id="sdrs_05_0101_p50902717203835"><a name="sdrs_05_0101_p50902717203835"></a><a name="sdrs_05_0101_p50902717203835"></a>You are not allowed to use the method specified in the request.</p>
    </td>
    </tr>
    <tr id="sdrs_05_0101_row55471277203835"><td class="cellrowborder" valign="top" width="43.419999999999995%" headers="mcps1.1.3.1.1 "><p id="sdrs_05_0101_p63988484203835"><a name="sdrs_05_0101_p63988484203835"></a><a name="sdrs_05_0101_p63988484203835"></a>406 Not Acceptable</p>
    </td>
    <td class="cellrowborder" valign="top" width="56.58%" headers="mcps1.1.3.1.2 "><p id="sdrs_05_0101_p15684678203835"><a name="sdrs_05_0101_p15684678203835"></a><a name="sdrs_05_0101_p15684678203835"></a>The response generated by the server could not be accepted by the client.</p>
    </td>
    </tr>
    <tr id="sdrs_05_0101_row6944380203835"><td class="cellrowborder" valign="top" width="43.419999999999995%" headers="mcps1.1.3.1.1 "><p id="sdrs_05_0101_p25623884203835"><a name="sdrs_05_0101_p25623884203835"></a><a name="sdrs_05_0101_p25623884203835"></a>407 Proxy Authentication Required</p>
    </td>
    <td class="cellrowborder" valign="top" width="56.58%" headers="mcps1.1.3.1.2 "><p id="sdrs_05_0101_p62268733203835"><a name="sdrs_05_0101_p62268733203835"></a><a name="sdrs_05_0101_p62268733203835"></a>You must use the proxy server for authentication so that the request can be processed.</p>
    </td>
    </tr>
    <tr id="sdrs_05_0101_row23547689203835"><td class="cellrowborder" valign="top" width="43.419999999999995%" headers="mcps1.1.3.1.1 "><p id="sdrs_05_0101_p28314670203835"><a name="sdrs_05_0101_p28314670203835"></a><a name="sdrs_05_0101_p28314670203835"></a>408 Request Timeout</p>
    </td>
    <td class="cellrowborder" valign="top" width="56.58%" headers="mcps1.1.3.1.2 "><p id="sdrs_05_0101_p11786919203835"><a name="sdrs_05_0101_p11786919203835"></a><a name="sdrs_05_0101_p11786919203835"></a>The request timed out.</p>
    </td>
    </tr>
    <tr id="sdrs_05_0101_row38973411203835"><td class="cellrowborder" valign="top" width="43.419999999999995%" headers="mcps1.1.3.1.1 "><p id="sdrs_05_0101_p2729702203835"><a name="sdrs_05_0101_p2729702203835"></a><a name="sdrs_05_0101_p2729702203835"></a>409 Conflict</p>
    </td>
    <td class="cellrowborder" valign="top" width="56.58%" headers="mcps1.1.3.1.2 "><p id="sdrs_05_0101_p19779281203835"><a name="sdrs_05_0101_p19779281203835"></a><a name="sdrs_05_0101_p19779281203835"></a>The request could not be processed due to a conflict.</p>
    </td>
    </tr>
    <tr id="sdrs_05_0101_row43795805203835"><td class="cellrowborder" valign="top" width="43.419999999999995%" headers="mcps1.1.3.1.1 "><p id="sdrs_05_0101_p57799353203835"><a name="sdrs_05_0101_p57799353203835"></a><a name="sdrs_05_0101_p57799353203835"></a>500 Internal Server Error</p>
    </td>
    <td class="cellrowborder" valign="top" width="56.58%" headers="mcps1.1.3.1.2 "><p id="sdrs_05_0101_p51235984203835"><a name="sdrs_05_0101_p51235984203835"></a><a name="sdrs_05_0101_p51235984203835"></a>Failed to complete the request because of a service error.</p>
    </td>
    </tr>
    <tr id="sdrs_05_0101_row58470678203835"><td class="cellrowborder" valign="top" width="43.419999999999995%" headers="mcps1.1.3.1.1 "><p id="sdrs_05_0101_p38504500203835"><a name="sdrs_05_0101_p38504500203835"></a><a name="sdrs_05_0101_p38504500203835"></a>501 Not Implemented</p>
    </td>
    <td class="cellrowborder" valign="top" width="56.58%" headers="mcps1.1.3.1.2 "><p id="sdrs_05_0101_p31856770203835"><a name="sdrs_05_0101_p31856770203835"></a><a name="sdrs_05_0101_p31856770203835"></a>Failed to complete the request because the server does not support the requested function.</p>
    </td>
    </tr>
    <tr id="sdrs_05_0101_row18275474203835"><td class="cellrowborder" valign="top" width="43.419999999999995%" headers="mcps1.1.3.1.1 "><p id="sdrs_05_0101_p3918444203835"><a name="sdrs_05_0101_p3918444203835"></a><a name="sdrs_05_0101_p3918444203835"></a>502 Bad Gateway</p>
    </td>
    <td class="cellrowborder" valign="top" width="56.58%" headers="mcps1.1.3.1.2 "><p id="sdrs_05_0101_p48958538203835"><a name="sdrs_05_0101_p48958538203835"></a><a name="sdrs_05_0101_p48958538203835"></a>Failed to complete the request because the server receives an invalid response from an upstream server.</p>
    </td>
    </tr>
    <tr id="sdrs_05_0101_row37973662203835"><td class="cellrowborder" valign="top" width="43.419999999999995%" headers="mcps1.1.3.1.1 "><p id="sdrs_05_0101_p55967806203835"><a name="sdrs_05_0101_p55967806203835"></a><a name="sdrs_05_0101_p55967806203835"></a>503 Service Unavailable</p>
    </td>
    <td class="cellrowborder" valign="top" width="56.58%" headers="mcps1.1.3.1.2 "><p id="sdrs_05_0101_p37098455203835"><a name="sdrs_05_0101_p37098455203835"></a><a name="sdrs_05_0101_p37098455203835"></a>Failed to complete the request because the system is unavailable.</p>
    </td>
    </tr>
    <tr id="sdrs_05_0101_row65450640203835"><td class="cellrowborder" valign="top" width="43.419999999999995%" headers="mcps1.1.3.1.1 "><p id="sdrs_05_0101_p67010448203835"><a name="sdrs_05_0101_p67010448203835"></a><a name="sdrs_05_0101_p67010448203835"></a>504 Gateway Timeout</p>
    </td>
    <td class="cellrowborder" valign="top" width="56.58%" headers="mcps1.1.3.1.2 "><p id="sdrs_05_0101_p59137180203835"><a name="sdrs_05_0101_p59137180203835"></a><a name="sdrs_05_0101_p59137180203835"></a>A gateway timeout error occurred.</p>
    </td>
    </tr>
    </tbody>
    </table>


