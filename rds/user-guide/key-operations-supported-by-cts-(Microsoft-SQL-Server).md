# Key Operations Supported by CTS<a name="rds_sqlserver_06_0004"></a>

Cloud Trace Service \(CTS\)  records operations related to RDS for further query, audit, and backtrack.

**Table  1**  RDS operations that can be recorded by CTS

<a name="en-us_topic_0171122358_table27743863194823"></a>
<table><thead align="left"><tr id="en-us_topic_0171122358_r7f44d07f1a7e4ab497849a732991fed3"><th class="cellrowborder" valign="top" width="42.54%" id="mcps1.2.4.1.1"><p id="en-us_topic_0171122358_a63fd6e5d562f4282bd32649f4a854de8"><a name="en-us_topic_0171122358_a63fd6e5d562f4282bd32649f4a854de8"></a><a name="en-us_topic_0171122358_a63fd6e5d562f4282bd32649f4a854de8"></a><strong id="en-us_topic_0171122358_en-us_topic_0100240370_b726976511613"><a name="en-us_topic_0171122358_en-us_topic_0100240370_b726976511613"></a><a name="en-us_topic_0171122358_en-us_topic_0100240370_b726976511613"></a>Operation</strong></p>
</th>
<th class="cellrowborder" valign="top" width="28.449999999999996%" id="mcps1.2.4.1.2"><p id="en-us_topic_0171122358_a0a92d786e2224a2a8d4deb79e5bd168e"><a name="en-us_topic_0171122358_a0a92d786e2224a2a8d4deb79e5bd168e"></a><a name="en-us_topic_0171122358_a0a92d786e2224a2a8d4deb79e5bd168e"></a><strong id="en-us_topic_0171122358_a9430514f195a4b62b833818f12495e16"><a name="en-us_topic_0171122358_a9430514f195a4b62b833818f12495e16"></a><a name="en-us_topic_0171122358_a9430514f195a4b62b833818f12495e16"></a>Resource Type</strong></p>
</th>
<th class="cellrowborder" valign="top" width="29.01%" id="mcps1.2.4.1.3"><p id="en-us_topic_0171122358_ae1d2b2f997f0470ab6de7eeba1d14f39"><a name="en-us_topic_0171122358_ae1d2b2f997f0470ab6de7eeba1d14f39"></a><a name="en-us_topic_0171122358_ae1d2b2f997f0470ab6de7eeba1d14f39"></a><strong id="en-us_topic_0171122358_a33cb9fe8828b4f27881562cc9616018e"><a name="en-us_topic_0171122358_a33cb9fe8828b4f27881562cc9616018e"></a><a name="en-us_topic_0171122358_a33cb9fe8828b4f27881562cc9616018e"></a>Trace Name</strong></p>
</th>
</tr>
</thead>
<tbody><tr id="en-us_topic_0171122358_rd5d58084a7d9466d9d8d525b49beece9"><td class="cellrowborder" valign="top" width="42.54%" headers="mcps1.2.4.1.1 "><p id="en-us_topic_0171122358_af7e5728f6d764ff5ab332ee110252aef"><a name="en-us_topic_0171122358_af7e5728f6d764ff5ab332ee110252aef"></a><a name="en-us_topic_0171122358_af7e5728f6d764ff5ab332ee110252aef"></a>Creating a DB instance or using backup data to create a new DB instance (using the console, Trove APIs, or open APIs)</p>
</td>
<td class="cellrowborder" valign="top" width="28.449999999999996%" headers="mcps1.2.4.1.2 "><p id="en-us_topic_0171122358_af825779a9cd54e738b3d639508529df4"><a name="en-us_topic_0171122358_af825779a9cd54e738b3d639508529df4"></a><a name="en-us_topic_0171122358_af825779a9cd54e738b3d639508529df4"></a>DB instance</p>
</td>
<td class="cellrowborder" valign="top" width="29.01%" headers="mcps1.2.4.1.3 "><p id="en-us_topic_0171122358_a0a5e47f01d004f469067ead9f4ce02e0"><a name="en-us_topic_0171122358_a0a5e47f01d004f469067ead9f4ce02e0"></a><a name="en-us_topic_0171122358_a0a5e47f01d004f469067ead9f4ce02e0"></a>createInstance</p>
</td>
</tr>
<tr id="en-us_topic_0171122358_r5e6aedcb2aac46808bbc406ccfa72a70"><td class="cellrowborder" valign="top" width="42.54%" headers="mcps1.2.4.1.1 "><p id="en-us_topic_0171122358_en-us_topic_0100240370_p467992810535"><a name="en-us_topic_0171122358_en-us_topic_0100240370_p467992810535"></a><a name="en-us_topic_0171122358_en-us_topic_0100240370_p467992810535"></a>Creating a read replica (using the console, Trove APIs, or open APIs)</p>
</td>
<td class="cellrowborder" valign="top" width="28.449999999999996%" headers="mcps1.2.4.1.2 "><p id="en-us_topic_0171122358_a44ed0967776848f9bd337ec45ff25b2a"><a name="en-us_topic_0171122358_a44ed0967776848f9bd337ec45ff25b2a"></a><a name="en-us_topic_0171122358_a44ed0967776848f9bd337ec45ff25b2a"></a>DB instance</p>
</td>
<td class="cellrowborder" valign="top" width="29.01%" headers="mcps1.2.4.1.3 "><p id="en-us_topic_0171122358_aca9c9a8053534fd193e6e552aaf59014"><a name="en-us_topic_0171122358_aca9c9a8053534fd193e6e552aaf59014"></a><a name="en-us_topic_0171122358_aca9c9a8053534fd193e6e552aaf59014"></a>createReadReplicate</p>
</td>
</tr>
<tr id="en-us_topic_0171122358_r36e06c63d1334c1490d62de6cfa24e65"><td class="cellrowborder" valign="top" width="42.54%" headers="mcps1.2.4.1.1 "><p id="en-us_topic_0171122358_ad9998ab28d504bd4aeb2baa958b10bd1"><a name="en-us_topic_0171122358_ad9998ab28d504bd4aeb2baa958b10bd1"></a><a name="en-us_topic_0171122358_ad9998ab28d504bd4aeb2baa958b10bd1"></a>Scaling up storage space and changing instance class (using the console, Trove APIs, or open APIs)</p>
</td>
<td class="cellrowborder" valign="top" width="28.449999999999996%" headers="mcps1.2.4.1.2 "><p id="en-us_topic_0171122358_en-us_topic_0100240370_p418869210749"><a name="en-us_topic_0171122358_en-us_topic_0100240370_p418869210749"></a><a name="en-us_topic_0171122358_en-us_topic_0100240370_p418869210749"></a>DB instance</p>
</td>
<td class="cellrowborder" valign="top" width="29.01%" headers="mcps1.2.4.1.3 "><p id="en-us_topic_0171122358_af5d36c8ee6934b4b84265525bbe7aa24"><a name="en-us_topic_0171122358_af5d36c8ee6934b4b84265525bbe7aa24"></a><a name="en-us_topic_0171122358_af5d36c8ee6934b4b84265525bbe7aa24"></a>instanceAction</p>
</td>
</tr>
<tr id="en-us_topic_0171122358_row1717353295215"><td class="cellrowborder" valign="top" width="42.54%" headers="mcps1.2.4.1.1 "><p id="en-us_topic_0171122358_p9174123213522"><a name="en-us_topic_0171122358_p9174123213522"></a><a name="en-us_topic_0171122358_p9174123213522"></a>Rebooting a DB instance (using the console, Trove APIs, or open APIs)</p>
</td>
<td class="cellrowborder" valign="top" width="28.449999999999996%" headers="mcps1.2.4.1.2 "><p id="en-us_topic_0171122358_p4174163225211"><a name="en-us_topic_0171122358_p4174163225211"></a><a name="en-us_topic_0171122358_p4174163225211"></a>DB instance</p>
</td>
<td class="cellrowborder" valign="top" width="29.01%" headers="mcps1.2.4.1.3 "><p id="en-us_topic_0171122358_p151752321520"><a name="en-us_topic_0171122358_p151752321520"></a><a name="en-us_topic_0171122358_p151752321520"></a>instanceRestart</p>
</td>
</tr>
<tr id="en-us_topic_0171122358_row562183515218"><td class="cellrowborder" valign="top" width="42.54%" headers="mcps1.2.4.1.1 "><p id="en-us_topic_0171122358_p17621183517524"><a name="en-us_topic_0171122358_p17621183517524"></a><a name="en-us_topic_0171122358_p17621183517524"></a>Restoring to the original DB instance (using the console, Trove APIs, or open APIs)</p>
</td>
<td class="cellrowborder" valign="top" width="28.449999999999996%" headers="mcps1.2.4.1.2 "><p id="en-us_topic_0171122358_p1962113357528"><a name="en-us_topic_0171122358_p1962113357528"></a><a name="en-us_topic_0171122358_p1962113357528"></a>DB instance</p>
</td>
<td class="cellrowborder" valign="top" width="29.01%" headers="mcps1.2.4.1.3 "><p id="en-us_topic_0171122358_p106211735165214"><a name="en-us_topic_0171122358_p106211735165214"></a><a name="en-us_topic_0171122358_p106211735165214"></a>instanceRestore</p>
</td>
</tr>
<tr id="row3456153321616"><td class="cellrowborder" valign="top" width="42.54%" headers="mcps1.2.4.1.1 "><p id="p7861959171115"><a name="p7861959171115"></a><a name="p7861959171115"></a>Renaming a DB instance (using the console)</p>
</td>
<td class="cellrowborder" valign="top" width="28.449999999999996%" headers="mcps1.2.4.1.2 "><p id="p886165961116"><a name="p886165961116"></a><a name="p886165961116"></a>DB instance</p>
</td>
<td class="cellrowborder" valign="top" width="29.01%" headers="mcps1.2.4.1.3 "><p id="p68610590113"><a name="p68610590113"></a><a name="p68610590113"></a>instanceRename</p>
</td>
</tr>
<tr id="en-us_topic_0171122358_r482e2acb5e5b4444aa055dac4b80afbc"><td class="cellrowborder" valign="top" width="42.54%" headers="mcps1.2.4.1.1 "><p id="en-us_topic_0171122358_a7c65853862154605a40a60d060affcad"><a name="en-us_topic_0171122358_a7c65853862154605a40a60d060affcad"></a><a name="en-us_topic_0171122358_a7c65853862154605a40a60d060affcad"></a>Resetting the password (using the console)</p>
</td>
<td class="cellrowborder" valign="top" width="28.449999999999996%" headers="mcps1.2.4.1.2 "><p id="en-us_topic_0171122358_a37c650fab97a4eef8b7913ac7956c8a4"><a name="en-us_topic_0171122358_a37c650fab97a4eef8b7913ac7956c8a4"></a><a name="en-us_topic_0171122358_a37c650fab97a4eef8b7913ac7956c8a4"></a>DB instance</p>
</td>
<td class="cellrowborder" valign="top" width="29.01%" headers="mcps1.2.4.1.3 "><p id="en-us_topic_0171122358_a6a482a4842ed4e53a9d67b25d9b0e53d"><a name="en-us_topic_0171122358_a6a482a4842ed4e53a9d67b25d9b0e53d"></a><a name="en-us_topic_0171122358_a6a482a4842ed4e53a9d67b25d9b0e53d"></a>resetPassword</p>
</td>
</tr>
<tr id="en-us_topic_0171122358_rcc318f6fd2274c3c8a3649709d1144a7"><td class="cellrowborder" valign="top" width="42.54%" headers="mcps1.2.4.1.1 "><p id="en-us_topic_0171122358_a7a7bffd693f3466f9d31d13469cdd6be"><a name="en-us_topic_0171122358_a7a7bffd693f3466f9d31d13469cdd6be"></a><a name="en-us_topic_0171122358_a7a7bffd693f3466f9d31d13469cdd6be"></a>Setting the database version parameters (using open APIs)</p>
</td>
<td class="cellrowborder" valign="top" width="28.449999999999996%" headers="mcps1.2.4.1.2 "><p id="en-us_topic_0171122358_a639badc3a3be4f37913cce4cf4b377dc"><a name="en-us_topic_0171122358_a639badc3a3be4f37913cce4cf4b377dc"></a><a name="en-us_topic_0171122358_a639badc3a3be4f37913cce4cf4b377dc"></a>DB instance</p>
</td>
<td class="cellrowborder" valign="top" width="29.01%" headers="mcps1.2.4.1.3 "><p id="en-us_topic_0171122358_afdb2067fb8fd4cfa8a17e3d582f0670b"><a name="en-us_topic_0171122358_afdb2067fb8fd4cfa8a17e3d582f0670b"></a><a name="en-us_topic_0171122358_afdb2067fb8fd4cfa8a17e3d582f0670b"></a>setDBParameters</p>
</td>
</tr>
<tr id="en-us_topic_0171122358_rb781d0d5a20344ef967e7983a4a4ab43"><td class="cellrowborder" valign="top" width="42.54%" headers="mcps1.2.4.1.1 "><p id="en-us_topic_0171122358_a495cfb49685e4267b6da2d2432b075b4"><a name="en-us_topic_0171122358_a495cfb49685e4267b6da2d2432b075b4"></a><a name="en-us_topic_0171122358_a495cfb49685e4267b6da2d2432b075b4"></a>Resetting the database version parameters (using open APIs)</p>
</td>
<td class="cellrowborder" valign="top" width="28.449999999999996%" headers="mcps1.2.4.1.2 "><p id="en-us_topic_0171122358_aa4a1acaa029a4e6fa6557bc684e4430d"><a name="en-us_topic_0171122358_aa4a1acaa029a4e6fa6557bc684e4430d"></a><a name="en-us_topic_0171122358_aa4a1acaa029a4e6fa6557bc684e4430d"></a>DB instance</p>
</td>
<td class="cellrowborder" valign="top" width="29.01%" headers="mcps1.2.4.1.3 "><p id="en-us_topic_0171122358_a4836101430dc4824978406d24413d0c6"><a name="en-us_topic_0171122358_a4836101430dc4824978406d24413d0c6"></a><a name="en-us_topic_0171122358_a4836101430dc4824978406d24413d0c6"></a>resetDBParameters</p>
</td>
</tr>
<tr id="en-us_topic_0171122358_r29eefbd82d204cc89a2164bba22d1a37"><td class="cellrowborder" valign="top" width="42.54%" headers="mcps1.2.4.1.1 "><p id="en-us_topic_0171122358_aa630277a78114119abe09b236bd3d341"><a name="en-us_topic_0171122358_aa630277a78114119abe09b236bd3d341"></a><a name="en-us_topic_0171122358_aa630277a78114119abe09b236bd3d341"></a>Enabling, modifying, or disabling the backup policy (using the console or open APIs)</p>
</td>
<td class="cellrowborder" valign="top" width="28.449999999999996%" headers="mcps1.2.4.1.2 "><p id="en-us_topic_0171122358_a7b2472afe98f44acae5596980479fa6e"><a name="en-us_topic_0171122358_a7b2472afe98f44acae5596980479fa6e"></a><a name="en-us_topic_0171122358_a7b2472afe98f44acae5596980479fa6e"></a>DB instance</p>
</td>
<td class="cellrowborder" valign="top" width="29.01%" headers="mcps1.2.4.1.3 "><p id="en-us_topic_0171122358_a9daf9c2cd9d547778dd68403785cafff"><a name="en-us_topic_0171122358_a9daf9c2cd9d547778dd68403785cafff"></a><a name="en-us_topic_0171122358_a9daf9c2cd9d547778dd68403785cafff"></a>setBackupPolicy</p>
</td>
</tr>
<tr id="en-us_topic_0171122358_rfe097bd8b106470fb9240510a8a1b1b9"><td class="cellrowborder" valign="top" width="42.54%" headers="mcps1.2.4.1.1 "><p id="en-us_topic_0171122358_a6679423693da4bd58b784354f70554b2"><a name="en-us_topic_0171122358_a6679423693da4bd58b784354f70554b2"></a><a name="en-us_topic_0171122358_a6679423693da4bd58b784354f70554b2"></a>Changing the database port number (using the console)</p>
</td>
<td class="cellrowborder" valign="top" width="28.449999999999996%" headers="mcps1.2.4.1.2 "><p id="en-us_topic_0171122358_abe3ac105e1d2478fb497130e328eb1ce"><a name="en-us_topic_0171122358_abe3ac105e1d2478fb497130e328eb1ce"></a><a name="en-us_topic_0171122358_abe3ac105e1d2478fb497130e328eb1ce"></a>DB instance</p>
</td>
<td class="cellrowborder" valign="top" width="29.01%" headers="mcps1.2.4.1.3 "><p id="en-us_topic_0171122358_a9cb63d4194fa43aea4c4f4d4f7f5ddec"><a name="en-us_topic_0171122358_a9cb63d4194fa43aea4c4f4d4f7f5ddec"></a><a name="en-us_topic_0171122358_a9cb63d4194fa43aea4c4f4d4f7f5ddec"></a>changeInstancePort</p>
</td>
</tr>
<tr id="en-us_topic_0171122358_r9068978436f9458696c8c92c74676a89"><td class="cellrowborder" valign="top" width="42.54%" headers="mcps1.2.4.1.1 "><p id="en-us_topic_0171122358_en-us_topic_0100240370_p24834310535"><a name="en-us_topic_0171122358_en-us_topic_0100240370_p24834310535"></a><a name="en-us_topic_0171122358_en-us_topic_0100240370_p24834310535"></a>Binding and unbinding an EIP (using the console)</p>
</td>
<td class="cellrowborder" valign="top" width="28.449999999999996%" headers="mcps1.2.4.1.2 "><p id="en-us_topic_0171122358_en-us_topic_0100240370_p824076810749"><a name="en-us_topic_0171122358_en-us_topic_0100240370_p824076810749"></a><a name="en-us_topic_0171122358_en-us_topic_0100240370_p824076810749"></a>DB instance</p>
</td>
<td class="cellrowborder" valign="top" width="29.01%" headers="mcps1.2.4.1.3 "><p id="en-us_topic_0171122358_ae011557d77d84908a68ae149eff2b357"><a name="en-us_topic_0171122358_ae011557d77d84908a68ae149eff2b357"></a><a name="en-us_topic_0171122358_ae011557d77d84908a68ae149eff2b357"></a>setOrResetPublicIP</p>
</td>
</tr>
<tr id="en-us_topic_0171122358_r32eb910448094ba8bf94a050804a2ffb"><td class="cellrowborder" valign="top" width="42.54%" headers="mcps1.2.4.1.1 "><p id="en-us_topic_0171122358_ad5a6e76acc1948929092d580fc8e0ae8"><a name="en-us_topic_0171122358_ad5a6e76acc1948929092d580fc8e0ae8"></a><a name="en-us_topic_0171122358_ad5a6e76acc1948929092d580fc8e0ae8"></a>Modifying the security group (using the console)</p>
</td>
<td class="cellrowborder" valign="top" width="28.449999999999996%" headers="mcps1.2.4.1.2 "><p id="en-us_topic_0171122358_a3a85043170494548ad872105c934799f"><a name="en-us_topic_0171122358_a3a85043170494548ad872105c934799f"></a><a name="en-us_topic_0171122358_a3a85043170494548ad872105c934799f"></a>DB instance</p>
</td>
<td class="cellrowborder" valign="top" width="29.01%" headers="mcps1.2.4.1.3 "><p id="en-us_topic_0171122358_af6e7f371fd334a14a727db3f9423868f"><a name="en-us_topic_0171122358_af6e7f371fd334a14a727db3f9423868f"></a><a name="en-us_topic_0171122358_af6e7f371fd334a14a727db3f9423868f"></a>modifySecurityGroup</p>
</td>
</tr>
<tr id="en-us_topic_0171122358_r0bc37b1afd114009bce9c986a9c6f394"><td class="cellrowborder" valign="top" width="42.54%" headers="mcps1.2.4.1.1 "><p id="en-us_topic_0171122358_ae6ca7c6647db4fd78c2ea7a1bd079784"><a name="en-us_topic_0171122358_ae6ca7c6647db4fd78c2ea7a1bd079784"></a><a name="en-us_topic_0171122358_ae6ca7c6647db4fd78c2ea7a1bd079784"></a>Adding a tag (using the console or open APIs)</p>
</td>
<td class="cellrowborder" valign="top" width="28.449999999999996%" headers="mcps1.2.4.1.2 "><p id="en-us_topic_0171122358_acb123bc8da1442a9a1e98629a8888bc2"><a name="en-us_topic_0171122358_acb123bc8da1442a9a1e98629a8888bc2"></a><a name="en-us_topic_0171122358_acb123bc8da1442a9a1e98629a8888bc2"></a>DB instance</p>
</td>
<td class="cellrowborder" valign="top" width="29.01%" headers="mcps1.2.4.1.3 "><p id="en-us_topic_0171122358_abda1c24b03b147419e53c681dc95965a"><a name="en-us_topic_0171122358_abda1c24b03b147419e53c681dc95965a"></a><a name="en-us_topic_0171122358_abda1c24b03b147419e53c681dc95965a"></a>createTag</p>
</td>
</tr>
<tr id="en-us_topic_0171122358_r882010fcb0604a53ad7686a898dc824c"><td class="cellrowborder" valign="top" width="42.54%" headers="mcps1.2.4.1.1 "><p id="en-us_topic_0171122358_a2f35e46f3fbb4554b5477ae9c5e76b5b"><a name="en-us_topic_0171122358_a2f35e46f3fbb4554b5477ae9c5e76b5b"></a><a name="en-us_topic_0171122358_a2f35e46f3fbb4554b5477ae9c5e76b5b"></a>Deleting a tag (using the console or open APIs)</p>
</td>
<td class="cellrowborder" valign="top" width="28.449999999999996%" headers="mcps1.2.4.1.2 "><p id="en-us_topic_0171122358_en-us_topic_0100240370_p178320210749"><a name="en-us_topic_0171122358_en-us_topic_0100240370_p178320210749"></a><a name="en-us_topic_0171122358_en-us_topic_0100240370_p178320210749"></a>DB instance</p>
</td>
<td class="cellrowborder" valign="top" width="29.01%" headers="mcps1.2.4.1.3 "><p id="en-us_topic_0171122358_a59d38e8bd6884dc290e3e30cf4e0a86f"><a name="en-us_topic_0171122358_a59d38e8bd6884dc290e3e30cf4e0a86f"></a><a name="en-us_topic_0171122358_a59d38e8bd6884dc290e3e30cf4e0a86f"></a>deleteTag</p>
</td>
</tr>
<tr id="en-us_topic_0171122358_rea7b8a9b9dbf44a7a7a4349b096889e6"><td class="cellrowborder" valign="top" width="42.54%" headers="mcps1.2.4.1.1 "><p id="en-us_topic_0171122358_a843f09db02c046e1933b627dcb9d37d7"><a name="en-us_topic_0171122358_a843f09db02c046e1933b627dcb9d37d7"></a><a name="en-us_topic_0171122358_a843f09db02c046e1933b627dcb9d37d7"></a>Modifying a tag (using the console or open APIs)</p>
</td>
<td class="cellrowborder" valign="top" width="28.449999999999996%" headers="mcps1.2.4.1.2 "><p id="en-us_topic_0171122358_af5cf210a22664504b30e955d27b2603a"><a name="en-us_topic_0171122358_af5cf210a22664504b30e955d27b2603a"></a><a name="en-us_topic_0171122358_af5cf210a22664504b30e955d27b2603a"></a>DB instance</p>
</td>
<td class="cellrowborder" valign="top" width="29.01%" headers="mcps1.2.4.1.3 "><p id="en-us_topic_0171122358_ae990bcd75a1448e4954e0f672322f893"><a name="en-us_topic_0171122358_ae990bcd75a1448e4954e0f672322f893"></a><a name="en-us_topic_0171122358_ae990bcd75a1448e4954e0f672322f893"></a>modifyTag</p>
</td>
</tr>
<tr id="en-us_topic_0171122358_rcbefd233a4214b6c934673228c750c31"><td class="cellrowborder" valign="top" width="42.54%" headers="mcps1.2.4.1.1 "><p id="en-us_topic_0171122358_a6126bb86508f4686956d028817e507da"><a name="en-us_topic_0171122358_a6126bb86508f4686956d028817e507da"></a><a name="en-us_topic_0171122358_a6126bb86508f4686956d028817e507da"></a>Deleting a DB instance (using the console, Trove APIs, or open APIs)</p>
</td>
<td class="cellrowborder" valign="top" width="28.449999999999996%" headers="mcps1.2.4.1.2 "><p id="en-us_topic_0171122358_a019b3caa778e4746a012c9b44a037a9f"><a name="en-us_topic_0171122358_a019b3caa778e4746a012c9b44a037a9f"></a><a name="en-us_topic_0171122358_a019b3caa778e4746a012c9b44a037a9f"></a>DB instance</p>
</td>
<td class="cellrowborder" valign="top" width="29.01%" headers="mcps1.2.4.1.3 "><p id="en-us_topic_0171122358_a747ccab3f97d455cbde1c8a754d35aa8"><a name="en-us_topic_0171122358_a747ccab3f97d455cbde1c8a754d35aa8"></a><a name="en-us_topic_0171122358_a747ccab3f97d455cbde1c8a754d35aa8"></a>deleteInstance</p>
</td>
</tr>
<tr id="row74318116178"><td class="cellrowborder" valign="top" width="42.54%" headers="mcps1.2.4.1.1 "><p id="p0526112810311"><a name="p0526112810311"></a><a name="p0526112810311"></a>Enabling TDE for a Microsoft SQL Server DB instance (using the console)</p>
</td>
<td class="cellrowborder" valign="top" width="28.449999999999996%" headers="mcps1.2.4.1.2 "><p id="p145262028733"><a name="p145262028733"></a><a name="p145262028733"></a>DB instance</p>
</td>
<td class="cellrowborder" valign="top" width="29.01%" headers="mcps1.2.4.1.3 "><p id="p7526428239"><a name="p7526428239"></a><a name="p7526428239"></a>sqlserverOpenTDE</p>
</td>
</tr>
<tr id="row102724101719"><td class="cellrowborder" valign="top" width="42.54%" headers="mcps1.2.4.1.1 "><p id="p591018166414"><a name="p591018166414"></a><a name="p591018166414"></a>Performing a primary/standby switchover (using the console)</p>
</td>
<td class="cellrowborder" valign="top" width="28.449999999999996%" headers="mcps1.2.4.1.2 "><p id="p5910916845"><a name="p5910916845"></a><a name="p5910916845"></a>DB instance</p>
</td>
<td class="cellrowborder" valign="top" width="29.01%" headers="mcps1.2.4.1.3 "><p id="p1991011611415"><a name="p1991011611415"></a><a name="p1991011611415"></a>instanceFailOver</p>
</td>
</tr>
<tr id="row2560749013"><td class="cellrowborder" valign="top" width="42.54%" headers="mcps1.2.4.1.1 "><p id="p7391913907"><a name="p7391913907"></a><a name="p7391913907"></a>Changing the synchronize model (using the console)</p>
</td>
<td class="cellrowborder" valign="top" width="28.449999999999996%" headers="mcps1.2.4.1.2 "><p id="p135613417016"><a name="p135613417016"></a><a name="p135613417016"></a>DB instance</p>
</td>
<td class="cellrowborder" valign="top" width="29.01%" headers="mcps1.2.4.1.3 "><p id="p8431220801"><a name="p8431220801"></a><a name="p8431220801"></a>instanceFailOverMode</p>
</td>
</tr>
<tr id="row11317802"><td class="cellrowborder" valign="top" width="42.54%" headers="mcps1.2.4.1.1 "><p id="p439161314017"><a name="p439161314017"></a><a name="p439161314017"></a>Changing the failover priority (using the console)</p>
</td>
<td class="cellrowborder" valign="top" width="28.449999999999996%" headers="mcps1.2.4.1.2 "><p id="p1317716015"><a name="p1317716015"></a><a name="p1317716015"></a>DB instance</p>
</td>
<td class="cellrowborder" valign="top" width="29.01%" headers="mcps1.2.4.1.3 "><p id="p4431820606"><a name="p4431820606"></a><a name="p4431820606"></a>instanceFailOverStrategy</p>
</td>
</tr>
<tr id="row20418123141716"><td class="cellrowborder" valign="top" width="42.54%" headers="mcps1.2.4.1.1 "><p id="p5683345100"><a name="p5683345100"></a><a name="p5683345100"></a>Changing a DB instance type from single to primary/standby (using the console, Trove APIs, or open APIs)</p>
</td>
<td class="cellrowborder" valign="top" width="28.449999999999996%" headers="mcps1.2.4.1.2 "><p id="p468313414101"><a name="p468313414101"></a><a name="p468313414101"></a>DB instance</p>
</td>
<td class="cellrowborder" valign="top" width="29.01%" headers="mcps1.2.4.1.3 "><p id="p17239302110"><a name="p17239302110"></a><a name="p17239302110"></a>modifySingleToHaInstance</p>
</td>
</tr>
<tr id="en-us_topic_0171122358_rf3b23d8780604636a608a10ea41d404a"><td class="cellrowborder" valign="top" width="42.54%" headers="mcps1.2.4.1.1 "><p id="en-us_topic_0171122358_en-us_topic_0100240370_p525050710535"><a name="en-us_topic_0171122358_en-us_topic_0100240370_p525050710535"></a><a name="en-us_topic_0171122358_en-us_topic_0100240370_p525050710535"></a>Creating a backup (using the console or open APIs)</p>
</td>
<td class="cellrowborder" valign="top" width="28.449999999999996%" headers="mcps1.2.4.1.2 "><p id="en-us_topic_0171122358_a2f50cfae5f924fd099e608d442a72dae"><a name="en-us_topic_0171122358_a2f50cfae5f924fd099e608d442a72dae"></a><a name="en-us_topic_0171122358_a2f50cfae5f924fd099e608d442a72dae"></a>Backup</p>
</td>
<td class="cellrowborder" valign="top" width="29.01%" headers="mcps1.2.4.1.3 "><p id="en-us_topic_0171122358_a03a599069a1e44808ac7ef0930886295"><a name="en-us_topic_0171122358_a03a599069a1e44808ac7ef0930886295"></a><a name="en-us_topic_0171122358_a03a599069a1e44808ac7ef0930886295"></a>createManualSnapshot</p>
</td>
</tr>
<tr id="en-us_topic_0171122358_r9f9d1e0e2e7e462191624e52baf3be74"><td class="cellrowborder" valign="top" width="42.54%" headers="mcps1.2.4.1.1 "><p id="en-us_topic_0171122358_en-us_topic_0100240370_p241488010535"><a name="en-us_topic_0171122358_en-us_topic_0100240370_p241488010535"></a><a name="en-us_topic_0171122358_en-us_topic_0100240370_p241488010535"></a>Replicating a backup (using the console)</p>
</td>
<td class="cellrowborder" valign="top" width="28.449999999999996%" headers="mcps1.2.4.1.2 "><p id="en-us_topic_0171122358_aaadf908e01064c738be8943010d3058d"><a name="en-us_topic_0171122358_aaadf908e01064c738be8943010d3058d"></a><a name="en-us_topic_0171122358_aaadf908e01064c738be8943010d3058d"></a>Backup</p>
</td>
<td class="cellrowborder" valign="top" width="29.01%" headers="mcps1.2.4.1.3 "><p id="en-us_topic_0171122358_a9618e8d61314469f92f2660c14519e85"><a name="en-us_topic_0171122358_a9618e8d61314469f92f2660c14519e85"></a><a name="en-us_topic_0171122358_a9618e8d61314469f92f2660c14519e85"></a>copySnapshot</p>
</td>
</tr>
<tr id="row8380132620119"><td class="cellrowborder" valign="top" width="42.54%" headers="mcps1.2.4.1.1 "><p id="p23801726515"><a name="p23801726515"></a><a name="p23801726515"></a>Download a backup (using the console or open APIs)</p>
</td>
<td class="cellrowborder" valign="top" width="28.449999999999996%" headers="mcps1.2.4.1.2 "><p id="p123804266115"><a name="p123804266115"></a><a name="p123804266115"></a>Backup</p>
</td>
<td class="cellrowborder" valign="top" width="29.01%" headers="mcps1.2.4.1.3 "><p id="p133807269113"><a name="p133807269113"></a><a name="p133807269113"></a>downLoadSnapshot</p>
</td>
</tr>
<tr id="en-us_topic_0171122358_rfe6b9fd03217482482a7f4bcb2e7efb9"><td class="cellrowborder" valign="top" width="42.54%" headers="mcps1.2.4.1.1 "><p id="en-us_topic_0171122358_afac2b142d1664a62b26d643093caed8d"><a name="en-us_topic_0171122358_afac2b142d1664a62b26d643093caed8d"></a><a name="en-us_topic_0171122358_afac2b142d1664a62b26d643093caed8d"></a>Deleting a backup (using the console or open APIs)</p>
</td>
<td class="cellrowborder" valign="top" width="28.449999999999996%" headers="mcps1.2.4.1.2 "><p id="en-us_topic_0171122358_afb26287fdb0d4fad9a0a2a9f295034c7"><a name="en-us_topic_0171122358_afb26287fdb0d4fad9a0a2a9f295034c7"></a><a name="en-us_topic_0171122358_afb26287fdb0d4fad9a0a2a9f295034c7"></a>Backup</p>
</td>
<td class="cellrowborder" valign="top" width="29.01%" headers="mcps1.2.4.1.3 "><p id="en-us_topic_0171122358_a256215ff7c934326a46cbae95ac060a7"><a name="en-us_topic_0171122358_a256215ff7c934326a46cbae95ac060a7"></a><a name="en-us_topic_0171122358_a256215ff7c934326a46cbae95ac060a7"></a>deleteManualSnapshot</p>
</td>
</tr>
<tr id="en-us_topic_0171122358_r93ed7975c035413498350d53d6bcb98f"><td class="cellrowborder" valign="top" width="42.54%" headers="mcps1.2.4.1.1 "><p id="en-us_topic_0171122358_a84f16655b0af40c88592e22ed7545c78"><a name="en-us_topic_0171122358_a84f16655b0af40c88592e22ed7545c78"></a><a name="en-us_topic_0171122358_a84f16655b0af40c88592e22ed7545c78"></a>Creating a parameter template (using the console or Trove APIs)</p>
</td>
<td class="cellrowborder" valign="top" width="28.449999999999996%" headers="mcps1.2.4.1.2 "><p id="en-us_topic_0171122358_afc8f1ad0765f45618c84e36ae9efbcdf"><a name="en-us_topic_0171122358_afc8f1ad0765f45618c84e36ae9efbcdf"></a><a name="en-us_topic_0171122358_afc8f1ad0765f45618c84e36ae9efbcdf"></a>parameterGroup</p>
</td>
<td class="cellrowborder" valign="top" width="29.01%" headers="mcps1.2.4.1.3 "><p id="en-us_topic_0171122358_ac80a41dd21114db789b7bdc8a1ea7406"><a name="en-us_topic_0171122358_ac80a41dd21114db789b7bdc8a1ea7406"></a><a name="en-us_topic_0171122358_ac80a41dd21114db789b7bdc8a1ea7406"></a>createParameterGroup</p>
</td>
</tr>
<tr id="en-us_topic_0171122358_r25e619c799314e318bb71987d1c08130"><td class="cellrowborder" valign="top" width="42.54%" headers="mcps1.2.4.1.1 "><p id="en-us_topic_0171122358_en-us_topic_0100240370_p719530510535"><a name="en-us_topic_0171122358_en-us_topic_0100240370_p719530510535"></a><a name="en-us_topic_0171122358_en-us_topic_0100240370_p719530510535"></a>Modifying parameters in a parameter template (using the console or Trove APIs)</p>
</td>
<td class="cellrowborder" valign="top" width="28.449999999999996%" headers="mcps1.2.4.1.2 "><p id="en-us_topic_0171122358_ac155e3c5f6f24860bf9e2cf64c13345a"><a name="en-us_topic_0171122358_ac155e3c5f6f24860bf9e2cf64c13345a"></a><a name="en-us_topic_0171122358_ac155e3c5f6f24860bf9e2cf64c13345a"></a>parameterGroup</p>
</td>
<td class="cellrowborder" valign="top" width="29.01%" headers="mcps1.2.4.1.3 "><p id="en-us_topic_0171122358_af5dbfd32626142a8a0c81fb375ea4251"><a name="en-us_topic_0171122358_af5dbfd32626142a8a0c81fb375ea4251"></a><a name="en-us_topic_0171122358_af5dbfd32626142a8a0c81fb375ea4251"></a>updateParameterGroup</p>
</td>
</tr>
<tr id="en-us_topic_0171122358_r4c36aaf73ad5434ea19531192026b26b"><td class="cellrowborder" valign="top" width="42.54%" headers="mcps1.2.4.1.1 "><p id="en-us_topic_0171122358_a3c61db77c20a4174962bbf3c765e8221"><a name="en-us_topic_0171122358_a3c61db77c20a4174962bbf3c765e8221"></a><a name="en-us_topic_0171122358_a3c61db77c20a4174962bbf3c765e8221"></a>Deleting a parameter template (using the console or Trove APIs)</p>
</td>
<td class="cellrowborder" valign="top" width="28.449999999999996%" headers="mcps1.2.4.1.2 "><p id="en-us_topic_0171122358_ac90dd13876f94c6789fd9503eb3cd216"><a name="en-us_topic_0171122358_ac90dd13876f94c6789fd9503eb3cd216"></a><a name="en-us_topic_0171122358_ac90dd13876f94c6789fd9503eb3cd216"></a>parameterGroup</p>
</td>
<td class="cellrowborder" valign="top" width="29.01%" headers="mcps1.2.4.1.3 "><p id="en-us_topic_0171122358_a5091b165705d4093845827e9618174c1"><a name="en-us_topic_0171122358_a5091b165705d4093845827e9618174c1"></a><a name="en-us_topic_0171122358_a5091b165705d4093845827e9618174c1"></a>deleteParameterGroup</p>
</td>
</tr>
<tr id="en-us_topic_0171122358_r9021082051c5494e8c4cc829028a208b"><td class="cellrowborder" valign="top" width="42.54%" headers="mcps1.2.4.1.1 "><p id="en-us_topic_0171122358_a966495c31a5e46b18e9a60ec8374f88d"><a name="en-us_topic_0171122358_a966495c31a5e46b18e9a60ec8374f88d"></a><a name="en-us_topic_0171122358_a966495c31a5e46b18e9a60ec8374f88d"></a>Replicating a parameter template (using the console)</p>
</td>
<td class="cellrowborder" valign="top" width="28.449999999999996%" headers="mcps1.2.4.1.2 "><p id="en-us_topic_0171122358_a4d4d91c42a4e4c8e80d8c9c85c8abf4b"><a name="en-us_topic_0171122358_a4d4d91c42a4e4c8e80d8c9c85c8abf4b"></a><a name="en-us_topic_0171122358_a4d4d91c42a4e4c8e80d8c9c85c8abf4b"></a>parameterGroup</p>
</td>
<td class="cellrowborder" valign="top" width="29.01%" headers="mcps1.2.4.1.3 "><p id="en-us_topic_0171122358_a8513407846a04c58b4eec4bdd9a4eedb"><a name="en-us_topic_0171122358_a8513407846a04c58b4eec4bdd9a4eedb"></a><a name="en-us_topic_0171122358_a8513407846a04c58b4eec4bdd9a4eedb"></a>copyParameterGroup</p>
</td>
</tr>
<tr id="en-us_topic_0171122358_r69098a72ee9944aba0e578bdfaf5823c"><td class="cellrowborder" valign="top" width="42.54%" headers="mcps1.2.4.1.1 "><p id="en-us_topic_0171122358_a630ea64ad5cc499bad891c212ce06eee"><a name="en-us_topic_0171122358_a630ea64ad5cc499bad891c212ce06eee"></a><a name="en-us_topic_0171122358_a630ea64ad5cc499bad891c212ce06eee"></a>Resetting a parameter template (using the console)</p>
</td>
<td class="cellrowborder" valign="top" width="28.449999999999996%" headers="mcps1.2.4.1.2 "><p id="en-us_topic_0171122358_ad85e2cc3dbec4d608eadf47509e25a85"><a name="en-us_topic_0171122358_ad85e2cc3dbec4d608eadf47509e25a85"></a><a name="en-us_topic_0171122358_ad85e2cc3dbec4d608eadf47509e25a85"></a>parameterGroup</p>
</td>
<td class="cellrowborder" valign="top" width="29.01%" headers="mcps1.2.4.1.3 "><p id="en-us_topic_0171122358_a80e1cc09373146628cf73624519fe4c9"><a name="en-us_topic_0171122358_a80e1cc09373146628cf73624519fe4c9"></a><a name="en-us_topic_0171122358_a80e1cc09373146628cf73624519fe4c9"></a>resetParameterGroup</p>
</td>
</tr>
<tr id="en-us_topic_0171122358_r6d8f78a0c1dc41f2a3cc709363e19cef"><td class="cellrowborder" valign="top" width="42.54%" headers="mcps1.2.4.1.1 "><p id="en-us_topic_0171122358_ae10377bbf28f40f8bb03731072ffc18b"><a name="en-us_topic_0171122358_ae10377bbf28f40f8bb03731072ffc18b"></a><a name="en-us_topic_0171122358_ae10377bbf28f40f8bb03731072ffc18b"></a>Comparing parameter templates (using the console)</p>
</td>
<td class="cellrowborder" valign="top" width="28.449999999999996%" headers="mcps1.2.4.1.2 "><p id="en-us_topic_0171122358_ac3ff0bdaf05047d295a086665061cb0c"><a name="en-us_topic_0171122358_ac3ff0bdaf05047d295a086665061cb0c"></a><a name="en-us_topic_0171122358_ac3ff0bdaf05047d295a086665061cb0c"></a>parameterGroup</p>
</td>
<td class="cellrowborder" valign="top" width="29.01%" headers="mcps1.2.4.1.3 "><p id="en-us_topic_0171122358_a0572ff1400944cd5abbe0bffa811dc7c"><a name="en-us_topic_0171122358_a0572ff1400944cd5abbe0bffa811dc7c"></a><a name="en-us_topic_0171122358_a0572ff1400944cd5abbe0bffa811dc7c"></a>compareParameterGroup</p>
</td>
</tr>
<tr id="en-us_topic_0171122358_r6e2b1aa947d144c3857c574b57df36fd"><td class="cellrowborder" valign="top" width="42.54%" headers="mcps1.2.4.1.1 "><p id="en-us_topic_0171122358_a5551bae8a28f45b4bde17e527496f5db"><a name="en-us_topic_0171122358_a5551bae8a28f45b4bde17e527496f5db"></a><a name="en-us_topic_0171122358_a5551bae8a28f45b4bde17e527496f5db"></a>Applying a parameter template (using the console)</p>
</td>
<td class="cellrowborder" valign="top" width="28.449999999999996%" headers="mcps1.2.4.1.2 "><p id="en-us_topic_0171122358_aabfedbf419c641739b910aa2e163bb38"><a name="en-us_topic_0171122358_aabfedbf419c641739b910aa2e163bb38"></a><a name="en-us_topic_0171122358_aabfedbf419c641739b910aa2e163bb38"></a>parameterGroup</p>
</td>
<td class="cellrowborder" valign="top" width="29.01%" headers="mcps1.2.4.1.3 "><p id="en-us_topic_0171122358_a1082f514daab40b797aba6ee50312a0c"><a name="en-us_topic_0171122358_a1082f514daab40b797aba6ee50312a0c"></a><a name="en-us_topic_0171122358_a1082f514daab40b797aba6ee50312a0c"></a>applyParameterGroup</p>
</td>
</tr>
<tr id="row89916381021"><td class="cellrowborder" valign="top" width="42.54%" headers="mcps1.2.4.1.1 "><p id="p1899115381821"><a name="p1899115381821"></a><a name="p1899115381821"></a>Saving parameters in a parameter template (using the console)</p>
</td>
<td class="cellrowborder" valign="top" width="28.449999999999996%" headers="mcps1.2.4.1.2 "><p id="p9991638629"><a name="p9991638629"></a><a name="p9991638629"></a>parameterGroup</p>
</td>
<td class="cellrowborder" valign="top" width="29.01%" headers="mcps1.2.4.1.3 "><p id="p99911386210"><a name="p99911386210"></a><a name="p99911386210"></a>saveParameterGroup</p>
</td>
</tr>
<tr id="row389516217713"><td class="cellrowborder" valign="top" width="42.54%" headers="mcps1.2.4.1.1 "><p id="p1895152110712"><a name="p1895152110712"></a><a name="p1895152110712"></a>Deleting a frozen DB instance (using the console)</p>
</td>
<td class="cellrowborder" valign="top" width="28.449999999999996%" headers="mcps1.2.4.1.2 "><p id="p178951021277"><a name="p178951021277"></a><a name="p178951021277"></a>All</p>
</td>
<td class="cellrowborder" valign="top" width="29.01%" headers="mcps1.2.4.1.3 "><p id="p108956219714"><a name="p108956219714"></a><a name="p108956219714"></a>rdsUnsubscribeInstance</p>
</td>
</tr>
<tr id="row18540122691"><td class="cellrowborder" valign="top" width="42.54%" headers="mcps1.2.4.1.1 "><p id="p5540821911"><a name="p5540821911"></a><a name="p5540821911"></a>Freezing a DB instance (using the console)</p>
</td>
<td class="cellrowborder" valign="top" width="28.449999999999996%" headers="mcps1.2.4.1.2 "><p id="p155408213910"><a name="p155408213910"></a><a name="p155408213910"></a>All</p>
</td>
<td class="cellrowborder" valign="top" width="29.01%" headers="mcps1.2.4.1.3 "><p id="p6540621394"><a name="p6540621394"></a><a name="p6540621394"></a>rdsunfreezeInstance</p>
</td>
</tr>
</tbody>
</table>

