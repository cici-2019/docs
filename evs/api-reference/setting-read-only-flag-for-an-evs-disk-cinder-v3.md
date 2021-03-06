# Setting Read-Only Flag for an EVS Disk<a name="evs_04_3050"></a>

## Function<a name="section19390540"></a>

This API is used to set the read-only flag for the EVS disk.

## URI<a name="section40297137"></a>

-   URI format

    POST /v3/\{project\_id\}/volumes/\{volume\_id\}/action

-   Parameter description

    <a name="table8745607"></a>
    <table><thead align="left"><tr id="row15985080"><th class="cellrowborder" valign="top" width="26.19%" id="mcps1.1.4.1.1"><p id="p19723089"><a name="p19723089"></a><a name="p19723089"></a>Parameter</p>
    </th>
    <th class="cellrowborder" valign="top" width="22.8%" id="mcps1.1.4.1.2"><p id="p54066375"><a name="p54066375"></a><a name="p54066375"></a>Mandatory</p>
    </th>
    <th class="cellrowborder" valign="top" width="51.01%" id="mcps1.1.4.1.3"><p id="p17300225"><a name="p17300225"></a><a name="p17300225"></a>Description</p>
    </th>
    </tr>
    </thead>
    <tbody><tr id="row59140967"><td class="cellrowborder" valign="top" width="26.19%" headers="mcps1.1.4.1.1 "><p id="p25689059"><a name="p25689059"></a><a name="p25689059"></a>project_id</p>
    </td>
    <td class="cellrowborder" valign="top" width="22.8%" headers="mcps1.1.4.1.2 "><p id="p439002"><a name="p439002"></a><a name="p439002"></a>Yes</p>
    </td>
    <td class="cellrowborder" valign="top" width="51.01%" headers="mcps1.1.4.1.3 "><p id="p35559222"><a name="p35559222"></a><a name="p35559222"></a>Specifies the project ID.</p>
    </td>
    </tr>
    <tr id="row51597550"><td class="cellrowborder" valign="top" width="26.19%" headers="mcps1.1.4.1.1 "><p id="p18651996"><a name="p18651996"></a><a name="p18651996"></a>volume_id</p>
    </td>
    <td class="cellrowborder" valign="top" width="22.8%" headers="mcps1.1.4.1.2 "><p id="p34416674"><a name="p34416674"></a><a name="p34416674"></a>Yes</p>
    </td>
    <td class="cellrowborder" valign="top" width="51.01%" headers="mcps1.1.4.1.3 "><p id="p36287209"><a name="p36287209"></a><a name="p36287209"></a>Specifies the disk ID.</p>
    </td>
    </tr>
    </tbody>
    </table>


## Request<a name="section27129916"></a>

-   Parameter description

    <a name="evs_04_2085_table42671863"></a>
    <table><thead align="left"><tr id="evs_04_2085_row12592542"><th class="cellrowborder" valign="top" width="19.919999999999998%" id="mcps1.1.5.1.1"><p id="evs_04_2085_p13362997"><a name="evs_04_2085_p13362997"></a><a name="evs_04_2085_p13362997"></a>Parameter</p>
    </th>
    <th class="cellrowborder" valign="top" width="16.73%" id="mcps1.1.5.1.2"><p id="evs_04_2085_p8661001"><a name="evs_04_2085_p8661001"></a><a name="evs_04_2085_p8661001"></a>Type</p>
    </th>
    <th class="cellrowborder" valign="top" width="18.05%" id="mcps1.1.5.1.3"><p id="evs_04_2085_p30452481"><a name="evs_04_2085_p30452481"></a><a name="evs_04_2085_p30452481"></a>Mandatory</p>
    </th>
    <th class="cellrowborder" valign="top" width="45.300000000000004%" id="mcps1.1.5.1.4"><p id="evs_04_2085_p50731910"><a name="evs_04_2085_p50731910"></a><a name="evs_04_2085_p50731910"></a>Description</p>
    </th>
    </tr>
    </thead>
    <tbody><tr id="evs_04_2085_row5187493615377"><td class="cellrowborder" valign="top" width="19.919999999999998%" headers="mcps1.1.5.1.1 "><p id="evs_04_2085_p4112025815377"><a name="evs_04_2085_p4112025815377"></a><a name="evs_04_2085_p4112025815377"></a>os-update_readonly_flag</p>
    </td>
    <td class="cellrowborder" valign="top" width="16.73%" headers="mcps1.1.5.1.2 "><p id="evs_04_2085_p4240658415377"><a name="evs_04_2085_p4240658415377"></a><a name="evs_04_2085_p4240658415377"></a>Object</p>
    </td>
    <td class="cellrowborder" valign="top" width="18.05%" headers="mcps1.1.5.1.3 "><p id="evs_04_2085_p1238131615377"><a name="evs_04_2085_p1238131615377"></a><a name="evs_04_2085_p1238131615377"></a>Yes</p>
    </td>
    <td class="cellrowborder" valign="top" width="45.300000000000004%" headers="mcps1.1.5.1.4 "><p id="evs_04_2085_p6336250715377"><a name="evs_04_2085_p6336250715377"></a><a name="evs_04_2085_p6336250715377"></a>Specifies the disk read-only flag. For details, see <a href="#evs_04_2085_li55520608111457">Parameter in the os-update_readonly_flag field</a>.</p>
    </td>
    </tr>
    </tbody>
    </table>

-   <a name="evs_04_2085_li55520608111457"></a>Parameter in the  **os-update\_readonly\_flag**  field

    <a name="evs_04_2085_table38065209105423"></a>
    <table><thead align="left"><tr id="evs_04_2085_row47014882105423"><th class="cellrowborder" valign="top" width="19.17%" id="mcps1.1.5.1.1"><p id="evs_04_2085_p50109122105423"><a name="evs_04_2085_p50109122105423"></a><a name="evs_04_2085_p50109122105423"></a>Parameter</p>
    </th>
    <th class="cellrowborder" valign="top" width="17.669999999999998%" id="mcps1.1.5.1.2"><p id="evs_04_2085_p32307099105423"><a name="evs_04_2085_p32307099105423"></a><a name="evs_04_2085_p32307099105423"></a>Type</p>
    </th>
    <th class="cellrowborder" valign="top" width="17.86%" id="mcps1.1.5.1.3"><p id="evs_04_2085_p66738196105423"><a name="evs_04_2085_p66738196105423"></a><a name="evs_04_2085_p66738196105423"></a>Mandatory</p>
    </th>
    <th class="cellrowborder" valign="top" width="45.300000000000004%" id="mcps1.1.5.1.4"><p id="evs_04_2085_p37084757105423"><a name="evs_04_2085_p37084757105423"></a><a name="evs_04_2085_p37084757105423"></a>Description</p>
    </th>
    </tr>
    </thead>
    <tbody><tr id="evs_04_2085_row65642867105423"><td class="cellrowborder" valign="top" width="19.17%" headers="mcps1.1.5.1.1 "><p id="evs_04_2085_p1874528111511"><a name="evs_04_2085_p1874528111511"></a><a name="evs_04_2085_p1874528111511"></a>readonly</p>
    </td>
    <td class="cellrowborder" valign="top" width="17.669999999999998%" headers="mcps1.1.5.1.2 "><p id="evs_04_2085_p45274007105423"><a name="evs_04_2085_p45274007105423"></a><a name="evs_04_2085_p45274007105423"></a>Boolean</p>
    </td>
    <td class="cellrowborder" valign="top" width="17.86%" headers="mcps1.1.5.1.3 "><p id="evs_04_2085_p43315944105423"><a name="evs_04_2085_p43315944105423"></a><a name="evs_04_2085_p43315944105423"></a>Yes</p>
    </td>
    <td class="cellrowborder" valign="top" width="45.300000000000004%" headers="mcps1.1.5.1.4 "><div class="p" id="evs_04_2085_p18930541105423"><a name="evs_04_2085_p18930541105423"></a><a name="evs_04_2085_p18930541105423"></a>Specifies the read-only flag.<a name="evs_04_2085_ul4954137112218"></a><a name="evs_04_2085_ul4954137112218"></a><ul id="evs_04_2085_ul4954137112218"><li><strong id="evs_04_2085_b1846332111818"><a name="evs_04_2085_b1846332111818"></a><a name="evs_04_2085_b1846332111818"></a>true</strong>: specifies the disk is read-only.</li><li><strong id="evs_04_2085_b326591715916"><a name="evs_04_2085_b326591715916"></a><a name="evs_04_2085_b326591715916"></a>false</strong>: specifies the disk is not read-only.</li></ul>
    </div>
    </td>
    </tr>
    </tbody>
    </table>

-   Example request

    ```
    {
        "os-update_readonly_flag": {
            "readonly": true
        }
    }
    ```


## Response<a name="section42842654"></a>

-   Parameter description

    <a name="evs_04_2085_table5532594121252"></a>
    <table><thead align="left"><tr id="evs_04_2085_row60048709121252"><th class="cellrowborder" valign="top" width="21.17788221177882%" id="mcps1.1.4.1.1"><p id="evs_04_2085_p32107236121252"><a name="evs_04_2085_p32107236121252"></a><a name="evs_04_2085_p32107236121252"></a>Parameter</p>
    </th>
    <th class="cellrowborder" valign="top" width="21.17788221177882%" id="mcps1.1.4.1.2"><p id="evs_04_2085_p50549312121252"><a name="evs_04_2085_p50549312121252"></a><a name="evs_04_2085_p50549312121252"></a>Type</p>
    </th>
    <th class="cellrowborder" valign="top" width="57.64423557644236%" id="mcps1.1.4.1.3"><p id="evs_04_2085_p2030156121252"><a name="evs_04_2085_p2030156121252"></a><a name="evs_04_2085_p2030156121252"></a>Description</p>
    </th>
    </tr>
    </thead>
    <tbody><tr id="evs_04_2085_row30224973121252"><td class="cellrowborder" valign="top" width="21.17788221177882%" headers="mcps1.1.4.1.1 "><p id="evs_04_2085_p129522216412"><a name="evs_04_2085_p129522216412"></a><a name="evs_04_2085_p129522216412"></a>error</p>
    </td>
    <td class="cellrowborder" valign="top" width="21.17788221177882%" headers="mcps1.1.4.1.2 "><p id="evs_04_2085_p1595262111415"><a name="evs_04_2085_p1595262111415"></a><a name="evs_04_2085_p1595262111415"></a>String</p>
    </td>
    <td class="cellrowborder" valign="top" width="57.64423557644236%" headers="mcps1.1.4.1.3 "><p id="evs_04_2085_p109527215417"><a name="evs_04_2085_p109527215417"></a><a name="evs_04_2085_p109527215417"></a>Specifies the error message returned when an error occurs. For details, see <a href="#evs_04_2085_li0419202382514">Parameters in the error field</a>.</p>
    </td>
    </tr>
    </tbody>
    </table>

-   <a name="evs_04_2085_li0419202382514"></a>Parameters in the  **error**  field

    <a name="evs_04_2085_evs_04_2013_table15441099103019"></a>
    <table><thead align="left"><tr id="evs_04_2085_evs_04_2013_row54094047103019"><th class="cellrowborder" valign="top" width="21.17788221177882%" id="mcps1.1.4.1.1"><p id="evs_04_2085_evs_04_2013_p19541716103019"><a name="evs_04_2085_evs_04_2013_p19541716103019"></a><a name="evs_04_2085_evs_04_2013_p19541716103019"></a>Parameter</p>
    </th>
    <th class="cellrowborder" valign="top" width="21.17788221177882%" id="mcps1.1.4.1.2"><p id="evs_04_2085_evs_04_2013_p39375186103019"><a name="evs_04_2085_evs_04_2013_p39375186103019"></a><a name="evs_04_2085_evs_04_2013_p39375186103019"></a>Type</p>
    </th>
    <th class="cellrowborder" valign="top" width="57.64423557644236%" id="mcps1.1.4.1.3"><p id="evs_04_2085_evs_04_2013_p38578950103019"><a name="evs_04_2085_evs_04_2013_p38578950103019"></a><a name="evs_04_2085_evs_04_2013_p38578950103019"></a>Description</p>
    </th>
    </tr>
    </thead>
    <tbody><tr id="evs_04_2085_evs_04_2013_row59401790103019"><td class="cellrowborder" valign="top" width="21.17788221177882%" headers="mcps1.1.4.1.1 "><p id="evs_04_2085_evs_04_2013_p46815658103019"><a name="evs_04_2085_evs_04_2013_p46815658103019"></a><a name="evs_04_2085_evs_04_2013_p46815658103019"></a>message</p>
    </td>
    <td class="cellrowborder" valign="top" width="21.17788221177882%" headers="mcps1.1.4.1.2 "><p id="evs_04_2085_evs_04_2013_p33971979103019"><a name="evs_04_2085_evs_04_2013_p33971979103019"></a><a name="evs_04_2085_evs_04_2013_p33971979103019"></a>String</p>
    </td>
    <td class="cellrowborder" valign="top" width="57.64423557644236%" headers="mcps1.1.4.1.3 "><p id="evs_04_2085_evs_04_2013_p21623243103019"><a name="evs_04_2085_evs_04_2013_p21623243103019"></a><a name="evs_04_2085_evs_04_2013_p21623243103019"></a>Specifies the error message returned when an error occurs.</p>
    </td>
    </tr>
    <tr id="evs_04_2085_evs_04_2013_row60391466103019"><td class="cellrowborder" valign="top" width="21.17788221177882%" headers="mcps1.1.4.1.1 "><p id="evs_04_2085_evs_04_2013_p59870541103019"><a name="evs_04_2085_evs_04_2013_p59870541103019"></a><a name="evs_04_2085_evs_04_2013_p59870541103019"></a>code</p>
    </td>
    <td class="cellrowborder" valign="top" width="21.17788221177882%" headers="mcps1.1.4.1.2 "><p id="evs_04_2085_evs_04_2013_p17675690103019"><a name="evs_04_2085_evs_04_2013_p17675690103019"></a><a name="evs_04_2085_evs_04_2013_p17675690103019"></a>String</p>
    </td>
    <td class="cellrowborder" valign="top" width="57.64423557644236%" headers="mcps1.1.4.1.3 "><p id="evs_04_2085_evs_04_2013_p6087468103019"><a name="evs_04_2085_evs_04_2013_p6087468103019"></a><a name="evs_04_2085_evs_04_2013_p6087468103019"></a>Specifies the error code returned when an error occurs.</p>
    <p id="evs_04_2085_evs_04_2013_p54787218103019"><a name="evs_04_2085_evs_04_2013_p54787218103019"></a><a name="evs_04_2085_evs_04_2013_p54787218103019"></a>For details about the error code, see <a href="error-codes.md">Error Codes</a>.</p>
    </td>
    </tr>
    </tbody>
    </table>


-   Example response

    None

    or

    ```
    {
        "error": {
            "message": "XXXX", 
            "code": "XXX"
        }
    }
    ```

    In the preceding example,  **error**  indicates a general error, for example,  **badRequest**  or  **itemNotFound**. An example is provided as follows:

    ```
    {
        "itemNotFound": {
            "message": "XXXX", 
            "code": "XXX"
        }
    }
    ```


## Status Codes<a name="section50039568"></a>

-   Normal

    202


## Error Codes<a name="section431317151242"></a>

For details, see  [Error Codes](error-codes.md).

