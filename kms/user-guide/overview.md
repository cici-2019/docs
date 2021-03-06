# Overview<a name="en-us_topic_0101786406"></a>

A CMK contains key metadata \(key ID, key alias, description, key status, and creation date\) and the key material used for encrypting and decrypting data.

-   When a user uses the KMS Console to create a CMK, the KMS automatically generates a key material for the CMK.
-   If you want to use your own key material, you can use the key import function on KMS Console to create a CMK whose key material is empty, and import the key material to the CMK.

## Important Notes<a name="section45818511344"></a>

-   Security

    You need to ensure that random sources meet your security requirements when using them to generate key material. When using the import key function, you need to be responsible for the security of your key material. Save the original backup of the key material so that the backup key material can be imported to the KMS in time when the key material is deleted accidentally.

-   Availability and Durability

    Before importing the key material into KMS, you need to ensure the availability and durability of the key material.

    Differences between the imported key material and the key material generated by KMS are shown in  [Table 1](#table1433519477126).

    **Table  1**  Differences between the imported key material and the key material generated by KMS

    <a name="table1433519477126"></a>
    <table><thead align="left"><tr id="row433564761219"><th class="cellrowborder" valign="top" width="14.000000000000002%" id="mcps1.2.3.1.1"><p id="p433534731217"><a name="p433534731217"></a><a name="p433534731217"></a>Key Material Source</p>
    </th>
    <th class="cellrowborder" valign="top" width="86%" id="mcps1.2.3.1.2"><p id="p1533534711216"><a name="p1533534711216"></a><a name="p1533534711216"></a>Difference</p>
    </th>
    </tr>
    </thead>
    <tbody><tr id="row83351447111218"><td class="cellrowborder" valign="top" width="14.000000000000002%" headers="mcps1.2.3.1.1 "><p id="p38838794154627"><a name="p38838794154627"></a><a name="p38838794154627"></a>CMKs using the imported key material</p>
    </td>
    <td class="cellrowborder" valign="top" width="86%" headers="mcps1.2.3.1.2 "><a name="ul1891815542265"></a><a name="ul1891815542265"></a><ul id="ul1891815542265"><li>You can delete the key material, but cannot delete the CMK and its metadata.</li><li>When importing the key material, you can set the expiration time of the key material. After the key material expires, the KMS automatically deletes the key material within 24 hours, but does not delete the CMK and its metadata.<p id="p2606539135511"><a name="p2606539135511"></a><a name="p2606539135511"></a>It is recommended that you save a copy of the material on your local device because it may be used for re-import in cases of invalid key material or unintended deletion of key material.</p>
    </li></ul>
    </td>
    </tr>
    <tr id="row633524781210"><td class="cellrowborder" valign="top" width="14.000000000000002%" headers="mcps1.2.3.1.1 "><p id="p13649906154627"><a name="p13649906154627"></a><a name="p13649906154627"></a>CMKs using KMS generated key material</p>
    </td>
    <td class="cellrowborder" valign="top" width="86%" headers="mcps1.2.3.1.2 "><a name="ul462610575262"></a><a name="ul462610575262"></a><ul id="ul462610575262"><li>The key material cannot be manually deleted.</li><li>You cannot set the expiration time for key material.</li></ul>
    </td>
    </tr>
    </tbody>
    </table>

-   Association

    When a key material is imported to a CMK, the CMK is permanently associated with the key material. Other key material cannot be imported into the CMK.

-   Uniqueness

    If you use the CMK created using the imported key material to encrypt data, the encrypted data can be decrypted only by the CMK that has been used to encrypt the data, because the metadata and key material of the CMK must be consistent.


