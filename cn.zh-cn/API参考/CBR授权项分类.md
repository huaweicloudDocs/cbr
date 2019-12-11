# CBR授权项分类<a name="cbr_04_0018"></a>

## 任务<a name="section20433131231818"></a>

<a name="table144113417188"></a>
<table><thead align="left"><tr id="row19131841161810"><th class="cellrowborder" valign="top" width="25%" id="mcps1.1.5.1.1"><p id="p6975162710197"><a name="p6975162710197"></a><a name="p6975162710197"></a>权限</p>
</th>
<th class="cellrowborder" valign="top" width="25%" id="mcps1.1.5.1.2"><p id="p199751827141918"><a name="p199751827141918"></a><a name="p199751827141918"></a>授权项</p>
</th>
<th class="cellrowborder" valign="top" width="25%" id="mcps1.1.5.1.3"><p id="p397512719199"><a name="p397512719199"></a><a name="p397512719199"></a>授权范围</p>
</th>
<th class="cellrowborder" valign="top" width="25%" id="mcps1.1.5.1.4"><p id="p097617278193"><a name="p097617278193"></a><a name="p097617278193"></a>对应API接口</p>
</th>
</tr>
</thead>
<tbody><tr id="row1132134119186"><td class="cellrowborder" valign="top" width="25%" headers="mcps1.1.5.1.1 "><p id="p10297641161912"><a name="p10297641161912"></a><a name="p10297641161912"></a>查询任务列表</p>
</td>
<td class="cellrowborder" valign="top" width="25%" headers="mcps1.1.5.1.2 "><p id="p1745304771919"><a name="p1745304771919"></a><a name="p1745304771919"></a>cbr:tasks:list</p>
</td>
<td class="cellrowborder" valign="top" width="25%" headers="mcps1.1.5.1.3 "><a name="ul11631162411285"></a><a name="ul11631162411285"></a><ul id="ul11631162411285"><li>支持：<a name="ul1767395442816"></a><a name="ul1767395442816"></a><ul id="ul1767395442816"><li>项目（Project）</li><li>企业项目（Enterprise Project）</li></ul>
</li></ul>
</td>
<td class="cellrowborder" valign="top" width="25%" headers="mcps1.1.5.1.4 "><p id="p1432417062011"><a name="p1432417062011"></a><a name="p1432417062011"></a>GET /v3/{project_id}/operation_logs</p>
</td>
</tr>
<tr id="row7132164110184"><td class="cellrowborder" valign="top" width="25%" headers="mcps1.1.5.1.1 "><p id="p192971641111911"><a name="p192971641111911"></a><a name="p192971641111911"></a>查询单个任务</p>
</td>
<td class="cellrowborder" valign="top" width="25%" headers="mcps1.1.5.1.2 "><p id="p184531847101912"><a name="p184531847101912"></a><a name="p184531847101912"></a>cbr:tasks:get</p>
</td>
<td class="cellrowborder" valign="top" width="25%" headers="mcps1.1.5.1.3 "><a name="ul057212126293"></a><a name="ul057212126293"></a><ul id="ul057212126293"><li>支持：<a name="ul05725127293"></a><a name="ul05725127293"></a><ul id="ul05725127293"><li>项目（Project）</li><li>企业项目（Enterprise Project）</li></ul>
</li></ul>
</td>
<td class="cellrowborder" valign="top" width="25%" headers="mcps1.1.5.1.4 "><p id="p832416019209"><a name="p832416019209"></a><a name="p832416019209"></a>GET /v3/{project_id}/operation_logs/{operation_log_id}</p>
</td>
</tr>
</tbody>
</table>

## 可保护性<a name="section181615140268"></a>

<a name="table1829853692613"></a>
<table><thead align="left"><tr id="row74271936162611"><th class="cellrowborder" valign="top" width="25%" id="mcps1.1.5.1.1"><p id="p129917445262"><a name="p129917445262"></a><a name="p129917445262"></a>权限</p>
</th>
<th class="cellrowborder" valign="top" width="24.759999999999998%" id="mcps1.1.5.1.2"><p id="p141006445268"><a name="p141006445268"></a><a name="p141006445268"></a>授权项</p>
</th>
<th class="cellrowborder" valign="top" width="25.240000000000002%" id="mcps1.1.5.1.3"><p id="p1110034415266"><a name="p1110034415266"></a><a name="p1110034415266"></a>授权范围</p>
</th>
<th class="cellrowborder" valign="top" width="25%" id="mcps1.1.5.1.4"><p id="p21001644172615"><a name="p21001644172615"></a><a name="p21001644172615"></a>对应API接口</p>
</th>
</tr>
</thead>
<tbody><tr id="row1242753632616"><td class="cellrowborder" valign="top" width="25%" headers="mcps1.1.5.1.1 "><p id="p690065416265"><a name="p690065416265"></a><a name="p690065416265"></a>查询可保护资源</p>
</td>
<td class="cellrowborder" valign="top" width="24.759999999999998%" headers="mcps1.1.5.1.2 "><p id="p1413617169274"><a name="p1413617169274"></a><a name="p1413617169274"></a>cbr:vaults:listProtectables</p>
<p id="p1513671602711"><a name="p1513671602711"></a><a name="p1513671602711"></a>ecs:cloudServers:list/ecs:cloudServers:get</p>
<p id="p10136181612275"><a name="p10136181612275"></a><a name="p10136181612275"></a>evs:volumes:list/evs:volumes:get</p>
</td>
<td class="cellrowborder" valign="top" width="25.240000000000002%" headers="mcps1.1.5.1.3 "><a name="ul1721918164292"></a><a name="ul1721918164292"></a><ul id="ul1721918164292"><li>支持：<a name="ul192193169295"></a><a name="ul192193169295"></a><ul id="ul192193169295"><li>项目（Project）</li><li>企业项目（Enterprise Project）</li></ul>
</li></ul>
</td>
<td class="cellrowborder" valign="top" width="25%" headers="mcps1.1.5.1.4 "><p id="p06811538172717"><a name="p06811538172717"></a><a name="p06811538172717"></a>GET /v3/{project_id}/protectables/{protectable_type}</p>
</td>
</tr>
<tr id="row84277366267"><td class="cellrowborder" valign="top" width="25%" headers="mcps1.1.5.1.1 "><p id="p99001354192611"><a name="p99001354192611"></a><a name="p99001354192611"></a>查询指定可保护资源</p>
</td>
<td class="cellrowborder" valign="top" width="24.759999999999998%" headers="mcps1.1.5.1.2 "><p id="p0136116132719"><a name="p0136116132719"></a><a name="p0136116132719"></a>cbr:vaults:getProtectables</p>
<p id="p8136316192713"><a name="p8136316192713"></a><a name="p8136316192713"></a>ecs:cloudServers:list/ecs:cloudServers:get</p>
<p id="p1713661662720"><a name="p1713661662720"></a><a name="p1713661662720"></a>evs:volumes:list/evs:volumes:get</p>
</td>
<td class="cellrowborder" valign="top" width="25.240000000000002%" headers="mcps1.1.5.1.3 "><a name="ul10367020122912"></a><a name="ul10367020122912"></a><ul id="ul10367020122912"><li>支持：<a name="ul143678209294"></a><a name="ul143678209294"></a><ul id="ul143678209294"><li>项目（Project）</li><li>企业项目（Enterprise Project）</li></ul>
</li></ul>
</td>
<td class="cellrowborder" valign="top" width="25%" headers="mcps1.1.5.1.4 "><p id="p1868173822713"><a name="p1868173822713"></a><a name="p1868173822713"></a>GET /v3/{project_id}/protectables/{protectable_type}/instances/{instance_id}</p>
</td>
</tr>
<tr id="row1542813692618"><td class="cellrowborder" valign="top" width="25%" headers="mcps1.1.5.1.1 "><p id="p1990114544263"><a name="p1990114544263"></a><a name="p1990114544263"></a>查询agent状态</p>
</td>
<td class="cellrowborder" valign="top" width="24.759999999999998%" headers="mcps1.1.5.1.2 "><p id="p2013610165277"><a name="p2013610165277"></a><a name="p2013610165277"></a>cbr:backups:checkAgent</p>
<p id="p913661672718"><a name="p913661672718"></a><a name="p913661672718"></a>ecs:cloudServers:list/ecs:cloudServers:list</p>
</td>
<td class="cellrowborder" valign="top" width="25.240000000000002%" headers="mcps1.1.5.1.3 "><a name="ul15967162319291"></a><a name="ul15967162319291"></a><ul id="ul15967162319291"><li>支持：<a name="ul16967723182920"></a><a name="ul16967723182920"></a><ul id="ul16967723182920"><li>项目（Project）</li><li>企业项目（Enterprise Project）</li></ul>
</li></ul>
</td>
<td class="cellrowborder" valign="top" width="25%" headers="mcps1.1.5.1.4 "><p id="p56814382274"><a name="p56814382274"></a><a name="p56814382274"></a>POST /v3/{project_id}/providers/{provider_id}/agent/check</p>
</td>
</tr>
<tr id="row10428113632612"><td class="cellrowborder" valign="top" width="25%" headers="mcps1.1.5.1.1 "><p id="p2901354132610"><a name="p2901354132610"></a><a name="p2901354132610"></a>查询复制能力</p>
</td>
<td class="cellrowborder" valign="top" width="24.759999999999998%" headers="mcps1.1.5.1.2 "><p id="p813613162276"><a name="p813613162276"></a><a name="p813613162276"></a>cbr:backups:queryReplicationCapability</p>
</td>
<td class="cellrowborder" valign="top" width="25.240000000000002%" headers="mcps1.1.5.1.3 "><a name="ul1033442917291"></a><a name="ul1033442917291"></a><ul id="ul1033442917291"><li>支持：<a name="ul73341429122914"></a><a name="ul73341429122914"></a><ul id="ul73341429122914"><li>项目（Project）</li><li>企业项目（Enterprise Project）</li></ul>
</li></ul>
</td>
<td class="cellrowborder" valign="top" width="25%" headers="mcps1.1.5.1.4 "><p id="p3681123812274"><a name="p3681123812274"></a><a name="p3681123812274"></a>GET /v3/{project_id/replication_capabilities</p>
</td>
</tr>
</tbody>
</table>

## 存储库<a name="section16923143918296"></a>

<a name="table784617325307"></a>
<table><thead align="left"><tr id="row92133314303"><th class="cellrowborder" valign="top" width="25%" id="mcps1.1.5.1.1"><p id="p16203154693018"><a name="p16203154693018"></a><a name="p16203154693018"></a>权限</p>
</th>
<th class="cellrowborder" valign="top" width="25%" id="mcps1.1.5.1.2"><p id="p62032464302"><a name="p62032464302"></a><a name="p62032464302"></a>授权项</p>
</th>
<th class="cellrowborder" valign="top" width="25%" id="mcps1.1.5.1.3"><p id="p12203134613013"><a name="p12203134613013"></a><a name="p12203134613013"></a>授权范围</p>
</th>
<th class="cellrowborder" valign="top" width="25%" id="mcps1.1.5.1.4"><p id="p13203446113018"><a name="p13203446113018"></a><a name="p13203446113018"></a>对应API接口</p>
</th>
</tr>
</thead>
<tbody><tr id="row18283333020"><td class="cellrowborder" valign="top" width="25%" headers="mcps1.1.5.1.1 "><p id="p18724017123110"><a name="p18724017123110"></a><a name="p18724017123110"></a>设置存储库策略</p>
</td>
<td class="cellrowborder" valign="top" width="25%" headers="mcps1.1.5.1.2 "><p id="p727372843115"><a name="p727372843115"></a><a name="p727372843115"></a>cbr:vaults:associatePolicy</p>
</td>
<td class="cellrowborder" valign="top" width="25%" headers="mcps1.1.5.1.3 "><a name="ul151337589338"></a><a name="ul151337589338"></a><ul id="ul151337589338"><li>支持：<a name="ul171331558163315"></a><a name="ul171331558163315"></a><ul id="ul171331558163315"><li>项目（Project）</li><li>企业项目（Enterprise Project）</li></ul>
</li></ul>
</td>
<td class="cellrowborder" valign="top" width="25%" headers="mcps1.1.5.1.4 "><p id="p696803113217"><a name="p696803113217"></a><a name="p696803113217"></a>POST /v3/{project_id}/vaults/{vault_id}/associate_policy</p>
</td>
</tr>
<tr id="row1722333305"><td class="cellrowborder" valign="top" width="25%" headers="mcps1.1.5.1.1 "><p id="p1872420179319"><a name="p1872420179319"></a><a name="p1872420179319"></a>查询指定存储库</p>
</td>
<td class="cellrowborder" valign="top" width="25%" headers="mcps1.1.5.1.2 "><p id="p3273122803113"><a name="p3273122803113"></a><a name="p3273122803113"></a>cbr:vaults:get</p>
</td>
<td class="cellrowborder" valign="top" width="25%" headers="mcps1.1.5.1.3 "><a name="ul124001415347"></a><a name="ul124001415347"></a><ul id="ul124001415347"><li>支持：<a name="ul154017119342"></a><a name="ul154017119342"></a><ul id="ul154017119342"><li>项目（Project）</li><li>企业项目（Enterprise Project）</li></ul>
</li></ul>
</td>
<td class="cellrowborder" valign="top" width="25%" headers="mcps1.1.5.1.4 "><p id="p6968337328"><a name="p6968337328"></a><a name="p6968337328"></a>GET /v3/{project_id}/vaults/{vault_id}</p>
</td>
</tr>
<tr id="row83733123019"><td class="cellrowborder" valign="top" width="25%" headers="mcps1.1.5.1.1 "><p id="p7724141743111"><a name="p7724141743111"></a><a name="p7724141743111"></a>修改存储库</p>
</td>
<td class="cellrowborder" valign="top" width="25%" headers="mcps1.1.5.1.2 "><p id="p182731528173118"><a name="p182731528173118"></a><a name="p182731528173118"></a>cbr:vaults:update</p>
</td>
<td class="cellrowborder" valign="top" width="25%" headers="mcps1.1.5.1.3 "><a name="ul18938573412"></a><a name="ul18938573412"></a><ul id="ul18938573412"><li>支持：<a name="ul199310518343"></a><a name="ul199310518343"></a><ul id="ul199310518343"><li>项目（Project）</li><li>企业项目（Enterprise Project）</li></ul>
</li></ul>
</td>
<td class="cellrowborder" valign="top" width="25%" headers="mcps1.1.5.1.4 "><p id="p1896815315327"><a name="p1896815315327"></a><a name="p1896815315327"></a>PUT /v3/{project_id}/vaults/{vault_id}</p>
</td>
</tr>
<tr id="row12313314302"><td class="cellrowborder" valign="top" width="25%" headers="mcps1.1.5.1.1 "><p id="p172416171313"><a name="p172416171313"></a><a name="p172416171313"></a>删除存储库</p>
</td>
<td class="cellrowborder" valign="top" width="25%" headers="mcps1.1.5.1.2 "><p id="p22731328193113"><a name="p22731328193113"></a><a name="p22731328193113"></a>cbr:vaults:delete</p>
</td>
<td class="cellrowborder" valign="top" width="25%" headers="mcps1.1.5.1.3 "><a name="ul376398203419"></a><a name="ul376398203419"></a><ul id="ul376398203419"><li>支持：<a name="ul27631081341"></a><a name="ul27631081341"></a><ul id="ul27631081341"><li>项目（Project）</li><li>企业项目（Enterprise Project）</li></ul>
</li></ul>
</td>
<td class="cellrowborder" valign="top" width="25%" headers="mcps1.1.5.1.4 "><p id="p1396810353213"><a name="p1396810353213"></a><a name="p1396810353213"></a>DELETE /v3/{project_id}/vaults/{vault_id}</p>
</td>
</tr>
<tr id="row2315331306"><td class="cellrowborder" valign="top" width="25%" headers="mcps1.1.5.1.1 "><p id="p1472419171312"><a name="p1472419171312"></a><a name="p1472419171312"></a>移除资源</p>
</td>
<td class="cellrowborder" valign="top" width="25%" headers="mcps1.1.5.1.2 "><p id="p12731328143116"><a name="p12731328143116"></a><a name="p12731328143116"></a>cbr:vaults:removeResources</p>
</td>
<td class="cellrowborder" valign="top" width="25%" headers="mcps1.1.5.1.3 "><a name="ul10724811123411"></a><a name="ul10724811123411"></a><ul id="ul10724811123411"><li>支持：<a name="ul177242011163414"></a><a name="ul177242011163414"></a><ul id="ul177242011163414"><li>项目（Project）</li><li>企业项目（Enterprise Project）</li></ul>
</li></ul>
</td>
<td class="cellrowborder" valign="top" width="25%" headers="mcps1.1.5.1.4 "><p id="p4968535326"><a name="p4968535326"></a><a name="p4968535326"></a>POST /v3/{project_id}/vaults/{vault_id}/remove_resources</p>
</td>
</tr>
<tr id="row174143333013"><td class="cellrowborder" valign="top" width="25%" headers="mcps1.1.5.1.1 "><p id="p1972441720318"><a name="p1972441720318"></a><a name="p1972441720318"></a>添加资源</p>
</td>
<td class="cellrowborder" valign="top" width="25%" headers="mcps1.1.5.1.2 "><p id="p52731728103111"><a name="p52731728103111"></a><a name="p52731728103111"></a>cbr:vaults:addResources</p>
<p id="p17273328103110"><a name="p17273328103110"></a><a name="p17273328103110"></a>ecs:cloudServers:list/ecs:cloudServers:get</p>
<p id="p6273132813116"><a name="p6273132813116"></a><a name="p6273132813116"></a>evs:volumes:list/evs:volumes:get</p>
</td>
<td class="cellrowborder" valign="top" width="25%" headers="mcps1.1.5.1.3 "><a name="ul189661514183410"></a><a name="ul189661514183410"></a><ul id="ul189661514183410"><li>支持：<a name="ul8966121420346"></a><a name="ul8966121420346"></a><ul id="ul8966121420346"><li>项目（Project）</li><li>企业项目（Enterprise Project）</li></ul>
</li></ul>
</td>
<td class="cellrowborder" valign="top" width="25%" headers="mcps1.1.5.1.4 "><p id="p09681239329"><a name="p09681239329"></a><a name="p09681239329"></a>POST /v3/{project_id}/vaults/{vault_id}/add_resources</p>
</td>
</tr>
<tr id="row74193313308"><td class="cellrowborder" valign="top" width="25%" headers="mcps1.1.5.1.1 "><p id="p072417171317"><a name="p072417171317"></a><a name="p072417171317"></a>查询存储库列表</p>
</td>
<td class="cellrowborder" valign="top" width="25%" headers="mcps1.1.5.1.2 "><p id="p427316289314"><a name="p427316289314"></a><a name="p427316289314"></a>cbr:vaults:list</p>
</td>
<td class="cellrowborder" valign="top" width="25%" headers="mcps1.1.5.1.3 "><a name="ul1813217143419"></a><a name="ul1813217143419"></a><ul id="ul1813217143419"><li>支持：<a name="ul1813617153416"></a><a name="ul1813617153416"></a><ul id="ul1813617153416"><li>项目（Project）</li><li>企业项目（Enterprise Project）</li></ul>
</li></ul>
</td>
<td class="cellrowborder" valign="top" width="25%" headers="mcps1.1.5.1.4 "><p id="p119681131329"><a name="p119681131329"></a><a name="p119681131329"></a>GET /v3/{project_id}/vaults</p>
</td>
</tr>
<tr id="row135133318307"><td class="cellrowborder" valign="top" width="25%" headers="mcps1.1.5.1.1 "><p id="p972441733119"><a name="p972441733119"></a><a name="p972441733119"></a>创建存储库</p>
</td>
<td class="cellrowborder" valign="top" width="25%" headers="mcps1.1.5.1.2 "><p id="p927317289316"><a name="p927317289316"></a><a name="p927317289316"></a>cbr:vaults:create</p>
<p id="p19273152803119"><a name="p19273152803119"></a><a name="p19273152803119"></a>ecs:cloudServers:list/ecs:cloudServers:get</p>
<p id="p172731228203112"><a name="p172731228203112"></a><a name="p172731228203112"></a>evs:volumes:list/evs:volumes:get</p>
</td>
<td class="cellrowborder" valign="top" width="25%" headers="mcps1.1.5.1.3 "><a name="ul1679232119343"></a><a name="ul1679232119343"></a><ul id="ul1679232119343"><li>支持：<a name="ul10792021203412"></a><a name="ul10792021203412"></a><ul id="ul10792021203412"><li>项目（Project）</li><li>企业项目（Enterprise Project）</li></ul>
</li></ul>
</td>
<td class="cellrowborder" valign="top" width="25%" headers="mcps1.1.5.1.4 "><p id="p9969232324"><a name="p9969232324"></a><a name="p9969232324"></a>POST /v3/{project_id}/vaults</p>
</td>
</tr>
<tr id="row185203373014"><td class="cellrowborder" valign="top" width="25%" headers="mcps1.1.5.1.1 "><p id="p17725151714316"><a name="p17725151714316"></a><a name="p17725151714316"></a>查询其他区域存储库列表</p>
</td>
<td class="cellrowborder" valign="top" width="25%" headers="mcps1.1.5.1.2 "><p id="p4274122823114"><a name="p4274122823114"></a><a name="p4274122823114"></a>cbr:vaults:listExternalVaults</p>
<p id="p827412283319"><a name="p827412283319"></a><a name="p827412283319"></a>cbr:vaults:listVaults</p>
</td>
<td class="cellrowborder" valign="top" width="25%" headers="mcps1.1.5.1.3 "><a name="ul08161324103416"></a><a name="ul08161324103416"></a><ul id="ul08161324103416"><li>支持：<a name="ul9817152473420"></a><a name="ul9817152473420"></a><ul id="ul9817152473420"><li>项目（Project）</li><li>企业项目（Enterprise Project）</li></ul>
</li></ul>
</td>
<td class="cellrowborder" valign="top" width="25%" headers="mcps1.1.5.1.4 "><p id="p1596983103215"><a name="p1596983103215"></a><a name="p1596983103215"></a>GET /v3/{project_id}/external_vaults</p>
</td>
</tr>
<tr id="row1593343017"><td class="cellrowborder" valign="top" width="25%" headers="mcps1.1.5.1.1 "><p id="p472512171315"><a name="p472512171315"></a><a name="p472512171315"></a>解除存储库策略</p>
</td>
<td class="cellrowborder" valign="top" width="25%" headers="mcps1.1.5.1.2 "><p id="p1327462818312"><a name="p1327462818312"></a><a name="p1327462818312"></a>cbr:vaults:dissociatePolicy</p>
</td>
<td class="cellrowborder" valign="top" width="25%" headers="mcps1.1.5.1.3 "><a name="ul54441229193418"></a><a name="ul54441229193418"></a><ul id="ul54441229193418"><li>支持：<a name="ul84441629193419"></a><a name="ul84441629193419"></a><ul id="ul84441629193419"><li>项目（Project）</li><li>企业项目（Enterprise Project）</li></ul>
</li></ul>
</td>
<td class="cellrowborder" valign="top" width="25%" headers="mcps1.1.5.1.4 "><p id="p29699353212"><a name="p29699353212"></a><a name="p29699353212"></a>POST /v3/{project_id/vaults/{vault_id}/dissociate_policy</p>
</td>
</tr>
</tbody>
</table>

## 还原点<a name="section2888611163913"></a>

<a name="table14941156153912"></a>
<table><thead align="left"><tr id="row1412215578392"><th class="cellrowborder" valign="top" width="25%" id="mcps1.1.5.1.1"><p id="p195441761406"><a name="p195441761406"></a><a name="p195441761406"></a>权限</p>
</th>
<th class="cellrowborder" valign="top" width="25%" id="mcps1.1.5.1.2"><p id="p1954514674015"><a name="p1954514674015"></a><a name="p1954514674015"></a>授权项</p>
</th>
<th class="cellrowborder" valign="top" width="25%" id="mcps1.1.5.1.3"><p id="p205453644019"><a name="p205453644019"></a><a name="p205453644019"></a>授权范围</p>
</th>
<th class="cellrowborder" valign="top" width="25%" id="mcps1.1.5.1.4"><p id="p10545267402"><a name="p10545267402"></a><a name="p10545267402"></a>对应API接口</p>
</th>
</tr>
</thead>
<tbody><tr id="row0122175720392"><td class="cellrowborder" valign="top" width="25%" headers="mcps1.1.5.1.1 "><p id="p1482951612403"><a name="p1482951612403"></a><a name="p1482951612403"></a>同步备份还原点</p>
</td>
<td class="cellrowborder" valign="top" width="25%" headers="mcps1.1.5.1.2 "><p id="p177902115408"><a name="p177902115408"></a><a name="p177902115408"></a>cbr:vaults:sync</p>
</td>
<td class="cellrowborder" valign="top" width="25%" headers="mcps1.1.5.1.3 "><a name="ul787944184011"></a><a name="ul787944184011"></a><ul id="ul787944184011"><li>支持：<a name="ul188754419401"></a><a name="ul188754419401"></a><ul id="ul188754419401"><li>项目（Project）</li><li>企业项目（Enterprise Project）</li></ul>
</li></ul>
</td>
<td class="cellrowborder" valign="top" width="25%" headers="mcps1.1.5.1.4 "><p id="p18770173224019"><a name="p18770173224019"></a><a name="p18770173224019"></a>POST /v3/{project_id}/providers/{provider_id}/checkpoints/sync</p>
</td>
</tr>
<tr id="row13122175703915"><td class="cellrowborder" valign="top" width="25%" headers="mcps1.1.5.1.1 "><p id="p882913169402"><a name="p882913169402"></a><a name="p882913169402"></a>复制备份还原点</p>
</td>
<td class="cellrowborder" valign="top" width="25%" headers="mcps1.1.5.1.2 "><p id="p477972113402"><a name="p477972113402"></a><a name="p477972113402"></a>cbr:vaults:replicate</p>
</td>
<td class="cellrowborder" valign="top" width="25%" headers="mcps1.1.5.1.3 "><a name="ul18962164694012"></a><a name="ul18962164694012"></a><ul id="ul18962164694012"><li>支持：<a name="ul10962194624019"></a><a name="ul10962194624019"></a><ul id="ul10962194624019"><li>项目（Project）</li><li>企业项目（Enterprise Project）</li></ul>
</li></ul>
</td>
<td class="cellrowborder" valign="top" width="25%" headers="mcps1.1.5.1.4 "><p id="p67701532184019"><a name="p67701532184019"></a><a name="p67701532184019"></a>POST /v3/{project_id}/providers/{provider_id}/checkpoints/replicate</p>
</td>
</tr>
<tr id="row12122125703914"><td class="cellrowborder" valign="top" width="25%" headers="mcps1.1.5.1.1 "><p id="p0829101615404"><a name="p0829101615404"></a><a name="p0829101615404"></a>创建备份还原点</p>
</td>
<td class="cellrowborder" valign="top" width="25%" headers="mcps1.1.5.1.2 "><p id="p17779192144016"><a name="p17779192144016"></a><a name="p17779192144016"></a>cbr:vaults:backup</p>
<p id="p157791821144014"><a name="p157791821144014"></a><a name="p157791821144014"></a>ecs:cloudServers:list/ecs:cloudServers:get</p>
<p id="p977942117404"><a name="p977942117404"></a><a name="p977942117404"></a>evs:volumes:list/evs:volumes:get</p>
</td>
<td class="cellrowborder" valign="top" width="25%" headers="mcps1.1.5.1.3 "><a name="ul86358496407"></a><a name="ul86358496407"></a><ul id="ul86358496407"><li>支持：<a name="ul7635154984011"></a><a name="ul7635154984011"></a><ul id="ul7635154984011"><li>项目（Project）</li><li>企业项目（Enterprise Project）</li></ul>
</li></ul>
</td>
<td class="cellrowborder" valign="top" width="25%" headers="mcps1.1.5.1.4 "><p id="p57711832144012"><a name="p57711832144012"></a><a name="p57711832144012"></a>POST /v3/{project_id}/providers/{provider_id}/checkpoints</p>
</td>
</tr>
</tbody>
</table>

## 备份共享<a name="section86041763166"></a>

<a name="table3636133011616"></a>
<table><thead align="left"><tr id="row6783113021611"><th class="cellrowborder" valign="top" width="25%" id="mcps1.1.5.1.1"><p id="p4568193812167"><a name="p4568193812167"></a><a name="p4568193812167"></a>权限</p>
</th>
<th class="cellrowborder" valign="top" width="25%" id="mcps1.1.5.1.2"><p id="p1556818388166"><a name="p1556818388166"></a><a name="p1556818388166"></a>授权项</p>
</th>
<th class="cellrowborder" valign="top" width="25%" id="mcps1.1.5.1.3"><p id="p456833881611"><a name="p456833881611"></a><a name="p456833881611"></a>授权范围</p>
</th>
<th class="cellrowborder" valign="top" width="25%" id="mcps1.1.5.1.4"><p id="p13568143851617"><a name="p13568143851617"></a><a name="p13568143851617"></a>对应API接口</p>
</th>
</tr>
</thead>
<tbody><tr id="row2783143061611"><td class="cellrowborder" valign="top" width="25%" headers="mcps1.1.5.1.1 "><p id="p1893785571616"><a name="p1893785571616"></a><a name="p1893785571616"></a>添加备份成员</p>
</td>
<td class="cellrowborder" valign="top" width="25%" headers="mcps1.1.5.1.2 "><p id="p1742412178"><a name="p1742412178"></a><a name="p1742412178"></a>cbr:member:create</p>
</td>
<td class="cellrowborder" valign="top" width="25%" headers="mcps1.1.5.1.3 "><a name="ul049531351716"></a><a name="ul049531351716"></a><ul id="ul049531351716"><li>支持：<a name="ul1495181351716"></a><a name="ul1495181351716"></a><ul id="ul1495181351716"><li>项目（Project）</li><li>企业项目（Enterprise Project）</li></ul>
</li></ul>
</td>
<td class="cellrowborder" valign="top" width="25%" headers="mcps1.1.5.1.4 "><p id="p195811653491"><a name="p195811653491"></a><a name="p195811653491"></a>POST /v3/{project_id}/backups/{backup_id}/members</p>
</td>
</tr>
<tr id="row3783163019161"><td class="cellrowborder" valign="top" width="25%" headers="mcps1.1.5.1.1 "><p id="p179371355111613"><a name="p179371355111613"></a><a name="p179371355111613"></a>更新备份成员状态</p>
</td>
<td class="cellrowborder" valign="top" width="25%" headers="mcps1.1.5.1.2 "><p id="p47513431713"><a name="p47513431713"></a><a name="p47513431713"></a>cbr:member:update</p>
</td>
<td class="cellrowborder" valign="top" width="25%" headers="mcps1.1.5.1.3 "><a name="ul843917164178"></a><a name="ul843917164178"></a><ul id="ul843917164178"><li>支持：<a name="ul2439516121710"></a><a name="ul2439516121710"></a><ul id="ul2439516121710"><li>项目（Project）</li><li>企业项目（Enterprise Project）</li></ul>
</li></ul>
</td>
<td class="cellrowborder" valign="top" width="25%" headers="mcps1.1.5.1.4 "><p id="p7581057498"><a name="p7581057498"></a><a name="p7581057498"></a>PUT</p>
<p id="p115811574911"><a name="p115811574911"></a><a name="p115811574911"></a>/v3/{project_id}/backups/{backup_id}/members/{member_id}</p>
</td>
</tr>
<tr id="row178415304165"><td class="cellrowborder" valign="top" width="25%" headers="mcps1.1.5.1.1 "><p id="p1093775519165"><a name="p1093775519165"></a><a name="p1093775519165"></a>获取备份成员详情</p>
</td>
<td class="cellrowborder" valign="top" width="25%" headers="mcps1.1.5.1.2 "><p id="p87554171713"><a name="p87554171713"></a><a name="p87554171713"></a>cbr:member:get</p>
</td>
<td class="cellrowborder" valign="top" width="25%" headers="mcps1.1.5.1.3 "><a name="ul152793198179"></a><a name="ul152793198179"></a><ul id="ul152793198179"><li>支持：<a name="ul128091941713"></a><a name="ul128091941713"></a><ul id="ul128091941713"><li>项目（Project）</li><li>企业项目（Enterprise Project）</li></ul>
</li></ul>
</td>
<td class="cellrowborder" valign="top" width="25%" headers="mcps1.1.5.1.4 "><p id="p1658112524919"><a name="p1658112524919"></a><a name="p1658112524919"></a>GET</p>
<p id="p858175194915"><a name="p858175194915"></a><a name="p858175194915"></a>/v3/{project_id}/backups/{backup_id}/members/{member_id}</p>
</td>
</tr>
<tr id="row17847309167"><td class="cellrowborder" valign="top" width="25%" headers="mcps1.1.5.1.1 "><p id="p19937145511165"><a name="p19937145511165"></a><a name="p19937145511165"></a>获取备份成员列表</p>
</td>
<td class="cellrowborder" valign="top" width="25%" headers="mcps1.1.5.1.2 "><p id="p127534191714"><a name="p127534191714"></a><a name="p127534191714"></a>cbr:member:list</p>
</td>
<td class="cellrowborder" valign="top" width="25%" headers="mcps1.1.5.1.3 "><a name="ul11599172112171"></a><a name="ul11599172112171"></a><ul id="ul11599172112171"><li>支持：<a name="ul1659912117175"></a><a name="ul1659912117175"></a><ul id="ul1659912117175"><li>项目（Project）</li><li>企业项目（Enterprise Project）</li></ul>
</li></ul>
</td>
<td class="cellrowborder" valign="top" width="25%" headers="mcps1.1.5.1.4 "><p id="p0581195164912"><a name="p0581195164912"></a><a name="p0581195164912"></a>GET</p>
<p id="p95811351494"><a name="p95811351494"></a><a name="p95811351494"></a>/v3/{project_id}/backups/{backup_id}/members</p>
</td>
</tr>
<tr id="row4784830191617"><td class="cellrowborder" valign="top" width="25%" headers="mcps1.1.5.1.1 "><p id="p89381555151611"><a name="p89381555151611"></a><a name="p89381555151611"></a>删除指定的备份成员</p>
</td>
<td class="cellrowborder" valign="top" width="25%" headers="mcps1.1.5.1.2 "><p id="p16751244173"><a name="p16751244173"></a><a name="p16751244173"></a>cbr:member:delete</p>
</td>
<td class="cellrowborder" valign="top" width="25%" headers="mcps1.1.5.1.3 "><a name="ul182342311719"></a><a name="ul182342311719"></a><ul id="ul182342311719"><li>支持：<a name="ul58245231177"></a><a name="ul58245231177"></a><ul id="ul58245231177"><li>项目（Project）</li><li>企业项目（Enterprise Project）</li></ul>
</li></ul>
</td>
<td class="cellrowborder" valign="top" width="25%" headers="mcps1.1.5.1.4 "><p id="p12581125194911"><a name="p12581125194911"></a><a name="p12581125194911"></a>DELETE</p>
<p id="p19581175164910"><a name="p19581175164910"></a><a name="p19581175164910"></a>/v3/{project_id}/backups/{backup_id}/members/{member_id}</p>
</td>
</tr>
</tbody>
</table>

## 备份<a name="section711017126813"></a>

<a name="table318611341082"></a>
<table><thead align="left"><tr id="row10335234582"><th class="cellrowborder" valign="top" width="25%" id="mcps1.1.5.1.1"><p id="p4143152891018"><a name="p4143152891018"></a><a name="p4143152891018"></a>权限</p>
</th>
<th class="cellrowborder" valign="top" width="25%" id="mcps1.1.5.1.2"><p id="p17143132841011"><a name="p17143132841011"></a><a name="p17143132841011"></a>授权项</p>
</th>
<th class="cellrowborder" valign="top" width="25%" id="mcps1.1.5.1.3"><p id="p14143028181011"><a name="p14143028181011"></a><a name="p14143028181011"></a>授权范围</p>
</th>
<th class="cellrowborder" valign="top" width="25%" id="mcps1.1.5.1.4"><p id="p01439281106"><a name="p01439281106"></a><a name="p01439281106"></a>对应API接口</p>
</th>
</tr>
</thead>
<tbody><tr id="row11336143419818"><td class="cellrowborder" valign="top" width="25%" headers="mcps1.1.5.1.1 "><p id="p126249413815"><a name="p126249413815"></a><a name="p126249413815"></a>查询所有备份</p>
</td>
<td class="cellrowborder" valign="top" width="25%" headers="mcps1.1.5.1.2 "><p id="p20921491681"><a name="p20921491681"></a><a name="p20921491681"></a>cbr:backups:list</p>
</td>
<td class="cellrowborder" valign="top" width="25%" headers="mcps1.1.5.1.3 "><a name="ul10777115717814"></a><a name="ul10777115717814"></a><ul id="ul10777115717814"><li>支持：<a name="ul1977711574813"></a><a name="ul1977711574813"></a><ul id="ul1977711574813"><li>项目（Project）</li><li>企业项目（Enterprise Project）</li></ul>
</li></ul>
</td>
<td class="cellrowborder" valign="top" width="25%" headers="mcps1.1.5.1.4 "><p id="p182421326699"><a name="p182421326699"></a><a name="p182421326699"></a>GET /v3/{project_id}/providers/{provider_id}/backups</p>
</td>
</tr>
<tr id="row143361349816"><td class="cellrowborder" valign="top" width="25%" headers="mcps1.1.5.1.1 "><p id="p15624541186"><a name="p15624541186"></a><a name="p15624541186"></a>查询指定备份</p>
</td>
<td class="cellrowborder" valign="top" width="25%" headers="mcps1.1.5.1.2 "><p id="p39234917820"><a name="p39234917820"></a><a name="p39234917820"></a>cbr:backups:get</p>
</td>
<td class="cellrowborder" valign="top" width="25%" headers="mcps1.1.5.1.3 "><a name="ul097702092"></a><a name="ul097702092"></a><ul id="ul097702092"><li>支持：<a name="ul7984013914"></a><a name="ul7984013914"></a><ul id="ul7984013914"><li>项目（Project）</li><li>企业项目（Enterprise Project）</li></ul>
</li></ul>
</td>
<td class="cellrowborder" valign="top" width="25%" headers="mcps1.1.5.1.4 "><p id="p202429269913"><a name="p202429269913"></a><a name="p202429269913"></a>GET /v3/{project_id}/providers/{provider_id}/backups/{backup_id}</p>
</td>
</tr>
<tr id="row133362349816"><td class="cellrowborder" valign="top" width="25%" headers="mcps1.1.5.1.1 "><p id="p10624541088"><a name="p10624541088"></a><a name="p10624541088"></a>删除备份</p>
</td>
<td class="cellrowborder" valign="top" width="25%" headers="mcps1.1.5.1.2 "><p id="p159211491280"><a name="p159211491280"></a><a name="p159211491280"></a>cbr:backups:delete</p>
</td>
<td class="cellrowborder" valign="top" width="25%" headers="mcps1.1.5.1.3 "><a name="ul12130633918"></a><a name="ul12130633918"></a><ul id="ul12130633918"><li>支持：<a name="ul19130103796"></a><a name="ul19130103796"></a><ul id="ul19130103796"><li>项目（Project）</li><li>企业项目（Enterprise Project）</li></ul>
</li></ul>
</td>
<td class="cellrowborder" valign="top" width="25%" headers="mcps1.1.5.1.4 "><p id="p1242152613919"><a name="p1242152613919"></a><a name="p1242152613919"></a>DELETE /v3/{project_id}/providers/{provider_id}/backups/{backup_id}</p>
</td>
</tr>
<tr id="row53371234881"><td class="cellrowborder" valign="top" width="25%" headers="mcps1.1.5.1.1 "><p id="p126251341188"><a name="p126251341188"></a><a name="p126251341188"></a>同步备份</p>
</td>
<td class="cellrowborder" valign="top" width="25%" headers="mcps1.1.5.1.2 "><p id="p15930495812"><a name="p15930495812"></a><a name="p15930495812"></a>cbr:backups:sync</p>
</td>
<td class="cellrowborder" valign="top" width="25%" headers="mcps1.1.5.1.3 "><a name="ul10995256913"></a><a name="ul10995256913"></a><ul id="ul10995256913"><li>支持：<a name="ul3995851291"></a><a name="ul3995851291"></a><ul id="ul3995851291"><li>项目（Project）</li><li>企业项目（Enterprise Project）</li></ul>
</li></ul>
</td>
<td class="cellrowborder" valign="top" width="25%" headers="mcps1.1.5.1.4 "><p id="p17243122619915"><a name="p17243122619915"></a><a name="p17243122619915"></a>POST /v3/{project_id}/providers/{provider_id}/backups/sync</p>
</td>
</tr>
<tr id="row23371345814"><td class="cellrowborder" valign="top" width="25%" headers="mcps1.1.5.1.1 "><p id="p9625241185"><a name="p9625241185"></a><a name="p9625241185"></a>备份恢复</p>
</td>
<td class="cellrowborder" valign="top" width="25%" headers="mcps1.1.5.1.2 "><p id="p8935491180"><a name="p8935491180"></a><a name="p8935491180"></a>cbr:backups:restore</p>
<p id="p8934491288"><a name="p8934491288"></a><a name="p8934491288"></a>ecs:cloudServers:list/ecs:cloudServers:get</p>
<p id="p149384919812"><a name="p149384919812"></a><a name="p149384919812"></a>evs:volumes:list/evs:volumes:get</p>
</td>
<td class="cellrowborder" valign="top" width="25%" headers="mcps1.1.5.1.3 "><a name="ul1748711103918"></a><a name="ul1748711103918"></a><ul id="ul1748711103918"><li>支持：<a name="ul6487610391"></a><a name="ul6487610391"></a><ul id="ul6487610391"><li>项目（Project）</li><li>企业项目（Enterprise Project）</li></ul>
</li></ul>
</td>
<td class="cellrowborder" valign="top" width="25%" headers="mcps1.1.5.1.4 "><p id="p12243192612919"><a name="p12243192612919"></a><a name="p12243192612919"></a>POST /v3/{project_id}/providers/{provider_id}/backups/{backup_id}/restore</p>
</td>
</tr>
<tr id="row93379347810"><td class="cellrowborder" valign="top" width="25%" headers="mcps1.1.5.1.1 "><p id="p16625154112813"><a name="p16625154112813"></a><a name="p16625154112813"></a>复制备份</p>
</td>
<td class="cellrowborder" valign="top" width="25%" headers="mcps1.1.5.1.2 "><p id="p1693749785"><a name="p1693749785"></a><a name="p1693749785"></a>cbr:backups:replicate</p>
</td>
<td class="cellrowborder" valign="top" width="25%" headers="mcps1.1.5.1.3 "><a name="ul8369201317912"></a><a name="ul8369201317912"></a><ul id="ul8369201317912"><li>支持：<a name="ul143699133913"></a><a name="ul143699133913"></a><ul id="ul143699133913"><li>项目（Project）</li><li>企业项目（Enterprise Project）</li></ul>
</li></ul>
</td>
<td class="cellrowborder" valign="top" width="25%" headers="mcps1.1.5.1.4 "><p id="p2243626391"><a name="p2243626391"></a><a name="p2243626391"></a>POST /v3/{project_id}/providers/{provider_id}/backups/{backup_id}/replicate</p>
</td>
</tr>
</tbody>
</table>

## 策略<a name="section6573939992"></a>

<a name="table1568916520917"></a>
<table><thead align="left"><tr id="row891614521994"><th class="cellrowborder" valign="top" width="25%" id="mcps1.1.5.1.1"><p id="p8742733181014"><a name="p8742733181014"></a><a name="p8742733181014"></a>权限</p>
</th>
<th class="cellrowborder" valign="top" width="25%" id="mcps1.1.5.1.2"><p id="p9742143312105"><a name="p9742143312105"></a><a name="p9742143312105"></a>授权项</p>
</th>
<th class="cellrowborder" valign="top" width="25%" id="mcps1.1.5.1.3"><p id="p19743933151014"><a name="p19743933151014"></a><a name="p19743933151014"></a>授权范围</p>
</th>
<th class="cellrowborder" valign="top" width="25%" id="mcps1.1.5.1.4"><p id="p12743203351010"><a name="p12743203351010"></a><a name="p12743203351010"></a>对应API接口</p>
</th>
</tr>
</thead>
<tbody><tr id="row291615210919"><td class="cellrowborder" valign="top" width="25%" headers="mcps1.1.5.1.1 "><p id="p457833814105"><a name="p457833814105"></a><a name="p457833814105"></a>查询策略列表</p>
</td>
<td class="cellrowborder" valign="top" width="25%" headers="mcps1.1.5.1.2 "><p id="p14136114218106"><a name="p14136114218106"></a><a name="p14136114218106"></a>cbr:policies:list</p>
</td>
<td class="cellrowborder" valign="top" width="25%" headers="mcps1.1.5.1.3 "><a name="ul16243134801012"></a><a name="ul16243134801012"></a><ul id="ul16243134801012"><li>支持：<a name="ul1024334891013"></a><a name="ul1024334891013"></a><ul id="ul1024334891013"><li>项目（Project）</li><li>企业项目（Enterprise Project）</li></ul>
</li></ul>
</td>
<td class="cellrowborder" valign="top" width="25%" headers="mcps1.1.5.1.4 "><p id="p11936149161117"><a name="p11936149161117"></a><a name="p11936149161117"></a>GET /v3/{project_id}/policies</p>
</td>
</tr>
<tr id="row18917205220914"><td class="cellrowborder" valign="top" width="25%" headers="mcps1.1.5.1.1 "><p id="p65781738151017"><a name="p65781738151017"></a><a name="p65781738151017"></a>创建策略</p>
</td>
<td class="cellrowborder" valign="top" width="25%" headers="mcps1.1.5.1.2 "><p id="p1913710423108"><a name="p1913710423108"></a><a name="p1913710423108"></a>cbr:policies:create</p>
</td>
<td class="cellrowborder" valign="top" width="25%" headers="mcps1.1.5.1.3 "><a name="ul19794350101019"></a><a name="ul19794350101019"></a><ul id="ul19794350101019"><li>支持：<a name="ul77941850161013"></a><a name="ul77941850161013"></a><ul id="ul77941850161013"><li>项目（Project）</li><li>企业项目（Enterprise Project）</li></ul>
</li></ul>
</td>
<td class="cellrowborder" valign="top" width="25%" headers="mcps1.1.5.1.4 "><p id="p169366951114"><a name="p169366951114"></a><a name="p169366951114"></a>POST /v3/{project_id}/policies</p>
</td>
</tr>
<tr id="row129170520913"><td class="cellrowborder" valign="top" width="25%" headers="mcps1.1.5.1.1 "><p id="p17579193818101"><a name="p17579193818101"></a><a name="p17579193818101"></a>查询单个策略</p>
</td>
<td class="cellrowborder" valign="top" width="25%" headers="mcps1.1.5.1.2 "><p id="p81371420102"><a name="p81371420102"></a><a name="p81371420102"></a>cbr:policies:get</p>
</td>
<td class="cellrowborder" valign="top" width="25%" headers="mcps1.1.5.1.3 "><a name="ul138186539103"></a><a name="ul138186539103"></a><ul id="ul138186539103"><li>支持：<a name="ul15818125318105"></a><a name="ul15818125318105"></a><ul id="ul15818125318105"><li>项目（Project）</li><li>企业项目（Enterprise Project）</li></ul>
</li></ul>
</td>
<td class="cellrowborder" valign="top" width="25%" headers="mcps1.1.5.1.4 "><p id="p14936396114"><a name="p14936396114"></a><a name="p14936396114"></a>GET /v3/{project_id/policies/{policy_id}</p>
</td>
</tr>
<tr id="row89171052894"><td class="cellrowborder" valign="top" width="25%" headers="mcps1.1.5.1.1 "><p id="p19579203861012"><a name="p19579203861012"></a><a name="p19579203861012"></a>修改策略</p>
</td>
<td class="cellrowborder" valign="top" width="25%" headers="mcps1.1.5.1.2 "><p id="p8137942201017"><a name="p8137942201017"></a><a name="p8137942201017"></a>cbr:policies:update</p>
</td>
<td class="cellrowborder" valign="top" width="25%" headers="mcps1.1.5.1.3 "><a name="ul146410580107"></a><a name="ul146410580107"></a><ul id="ul146410580107"><li>支持：<a name="ul66514583106"></a><a name="ul66514583106"></a><ul id="ul66514583106"><li>项目（Project）</li><li>企业项目（Enterprise Project）</li></ul>
</li></ul>
</td>
<td class="cellrowborder" valign="top" width="25%" headers="mcps1.1.5.1.4 "><p id="p189361951114"><a name="p189361951114"></a><a name="p189361951114"></a>PUT /v3/{project_id}/policies/{policy_id}</p>
</td>
</tr>
<tr id="row179181552096"><td class="cellrowborder" valign="top" width="25%" headers="mcps1.1.5.1.1 "><p id="p3579538161013"><a name="p3579538161013"></a><a name="p3579538161013"></a>删除策略</p>
</td>
<td class="cellrowborder" valign="top" width="25%" headers="mcps1.1.5.1.2 "><p id="p13137154216107"><a name="p13137154216107"></a><a name="p13137154216107"></a>cbr:policies:delete</p>
</td>
<td class="cellrowborder" valign="top" width="25%" headers="mcps1.1.5.1.3 "><a name="ul195881308116"></a><a name="ul195881308116"></a><ul id="ul195881308116"><li>支持：<a name="ul1058870111112"></a><a name="ul1058870111112"></a><ul id="ul1058870111112"><li>项目（Project）</li><li>企业项目（Enterprise Project）</li></ul>
</li></ul>
</td>
<td class="cellrowborder" valign="top" width="25%" headers="mcps1.1.5.1.4 "><p id="p993615901119"><a name="p993615901119"></a><a name="p993615901119"></a>DELETE /v3/{project_id}/policies/{policy_id}</p>
</td>
</tr>
</tbody>
</table>

## 标签<a name="section2078614164119"></a>

<a name="table12877153818110"></a>
<table><thead align="left"><tr id="row1804203951115"><th class="cellrowborder" valign="top" width="25%" id="mcps1.1.5.1.1"><p id="p1460919416138"><a name="p1460919416138"></a><a name="p1460919416138"></a>权限</p>
</th>
<th class="cellrowborder" valign="top" width="25%" id="mcps1.1.5.1.2"><p id="p760924131319"><a name="p760924131319"></a><a name="p760924131319"></a>授权项</p>
</th>
<th class="cellrowborder" valign="top" width="25%" id="mcps1.1.5.1.3"><p id="p1060913416137"><a name="p1060913416137"></a><a name="p1060913416137"></a>授权范围</p>
</th>
<th class="cellrowborder" valign="top" width="25%" id="mcps1.1.5.1.4"><p id="p10610445138"><a name="p10610445138"></a><a name="p10610445138"></a>对应API接口</p>
</th>
</tr>
</thead>
<tbody><tr id="row15804163919116"><td class="cellrowborder" valign="top" width="25%" headers="mcps1.1.5.1.1 "><p id="p8871184818114"><a name="p8871184818114"></a><a name="p8871184818114"></a>查询存储库资源实例</p>
</td>
<td class="cellrowborder" valign="top" width="25%" headers="mcps1.1.5.1.2 "><p id="p12122155301114"><a name="p12122155301114"></a><a name="p12122155301114"></a>cbr:vaults:listResourceInstances</p>
</td>
<td class="cellrowborder" valign="top" width="25%" headers="mcps1.1.5.1.3 "><a name="ul52589761212"></a><a name="ul52589761212"></a><ul id="ul52589761212"><li>支持：<a name="ul525857191220"></a><a name="ul525857191220"></a><ul id="ul525857191220"><li>项目（Project）</li><li>企业项目（Enterprise Project）</li></ul>
</li></ul>
</td>
<td class="cellrowborder" valign="top" width="25%" headers="mcps1.1.5.1.4 "><p id="p884042917124"><a name="p884042917124"></a><a name="p884042917124"></a>POST /v3/{project_id}/vault/resource_instances/action</p>
</td>
</tr>
<tr id="row78051139181117"><td class="cellrowborder" valign="top" width="25%" headers="mcps1.1.5.1.1 "><p id="p08714483118"><a name="p08714483118"></a><a name="p08714483118"></a>批量添加删除存储库资源标签</p>
</td>
<td class="cellrowborder" valign="top" width="25%" headers="mcps1.1.5.1.2 "><p id="p81226533115"><a name="p81226533115"></a><a name="p81226533115"></a>cbr:vaults:bulkCreateOrDeleteTags</p>
</td>
<td class="cellrowborder" valign="top" width="25%" headers="mcps1.1.5.1.3 "><a name="ul325812717127"></a><a name="ul325812717127"></a><ul id="ul325812717127"><li>支持：<a name="ul92589714123"></a><a name="ul92589714123"></a><ul id="ul92589714123"><li>项目（Project）</li><li>企业项目（Enterprise Project）</li></ul>
</li></ul>
</td>
<td class="cellrowborder" valign="top" width="25%" headers="mcps1.1.5.1.4 "><p id="p118404296124"><a name="p118404296124"></a><a name="p118404296124"></a>POST /v3/{project_id}/vault/{vault_id}/tags/action</p>
</td>
</tr>
<tr id="row18051039201112"><td class="cellrowborder" valign="top" width="25%" headers="mcps1.1.5.1.1 "><p id="p17871048191113"><a name="p17871048191113"></a><a name="p17871048191113"></a>添加存储库资源标签</p>
</td>
<td class="cellrowborder" valign="top" width="25%" headers="mcps1.1.5.1.2 "><p id="p712216532115"><a name="p712216532115"></a><a name="p712216532115"></a>cbr:vaults:setTags</p>
</td>
<td class="cellrowborder" valign="top" width="25%" headers="mcps1.1.5.1.3 "><a name="ul18258478125"></a><a name="ul18258478125"></a><ul id="ul18258478125"><li>支持：<a name="ul92584716129"></a><a name="ul92584716129"></a><ul id="ul92584716129"><li>项目（Project）</li><li>企业项目（Enterprise Project）</li></ul>
</li></ul>
</td>
<td class="cellrowborder" valign="top" width="25%" headers="mcps1.1.5.1.4 "><p id="p584132941210"><a name="p584132941210"></a><a name="p584132941210"></a>POST /v3/{project_id/vault/{vault_id}/tags</p>
</td>
</tr>
<tr id="row12805139181111"><td class="cellrowborder" valign="top" width="25%" headers="mcps1.1.5.1.1 "><p id="p18711748101112"><a name="p18711748101112"></a><a name="p18711748101112"></a>删除存储库资源标签</p>
</td>
<td class="cellrowborder" valign="top" width="25%" headers="mcps1.1.5.1.2 "><p id="p16122175381115"><a name="p16122175381115"></a><a name="p16122175381115"></a>cbr:vaults:deleteTags</p>
</td>
<td class="cellrowborder" valign="top" width="25%" headers="mcps1.1.5.1.3 "><a name="ul125912713125"></a><a name="ul125912713125"></a><ul id="ul125912713125"><li>支持：<a name="ul22597714126"></a><a name="ul22597714126"></a><ul id="ul22597714126"><li>项目（Project）</li><li>企业项目（Enterprise Project）</li></ul>
</li></ul>
</td>
<td class="cellrowborder" valign="top" width="25%" headers="mcps1.1.5.1.4 "><p id="p1284117292122"><a name="p1284117292122"></a><a name="p1284117292122"></a>DELETE /v3/{project_id}/vault/{vault_id}/tags/{key}</p>
</td>
</tr>
<tr id="row10806133941110"><td class="cellrowborder" valign="top" width="25%" headers="mcps1.1.5.1.1 "><p id="p17872124851120"><a name="p17872124851120"></a><a name="p17872124851120"></a>查询存储库资源标签</p>
</td>
<td class="cellrowborder" valign="top" width="25%" headers="mcps1.1.5.1.2 "><p id="p13122185313117"><a name="p13122185313117"></a><a name="p13122185313117"></a>cbr:vaults:getTags</p>
</td>
<td class="cellrowborder" valign="top" width="25%" headers="mcps1.1.5.1.3 "><a name="ul122596715123"></a><a name="ul122596715123"></a><ul id="ul122596715123"><li>支持：<a name="ul525916731210"></a><a name="ul525916731210"></a><ul id="ul525916731210"><li>项目（Project）</li><li>企业项目（Enterprise Project）</li></ul>
</li></ul>
</td>
<td class="cellrowborder" valign="top" width="25%" headers="mcps1.1.5.1.4 "><p id="p48414293128"><a name="p48414293128"></a><a name="p48414293128"></a>GET /v3/{project_id}/vault/{vault_id}/tags</p>
</td>
</tr>
<tr id="row1880603915110"><td class="cellrowborder" valign="top" width="25%" headers="mcps1.1.5.1.1 "><p id="p16872144861111"><a name="p16872144861111"></a><a name="p16872144861111"></a>查询存储库项目标签</p>
</td>
<td class="cellrowborder" valign="top" width="25%" headers="mcps1.1.5.1.2 "><p id="p1812285311112"><a name="p1812285311112"></a><a name="p1812285311112"></a>cbr:vaults:listProjectTags</p>
</td>
<td class="cellrowborder" valign="top" width="25%" headers="mcps1.1.5.1.3 "><a name="ul718361412128"></a><a name="ul718361412128"></a><ul id="ul718361412128"><li>支持：<a name="ul17183141411126"></a><a name="ul17183141411126"></a><ul id="ul17183141411126"><li>项目（Project）</li><li>企业项目（Enterprise Project）</li></ul>
</li></ul>
</td>
<td class="cellrowborder" valign="top" width="25%" headers="mcps1.1.5.1.4 "><p id="p98411829191217"><a name="p98411829191217"></a><a name="p98411829191217"></a>GET /v3/{project_id}/vault/tags</p>
</td>
</tr>
</tbody>
</table>

## 计量<a name="section731275621512"></a>

<a name="table1267711282162"></a>
<table><thead align="left"><tr id="row8727122831619"><th class="cellrowborder" valign="top" width="25%" id="mcps1.1.5.1.1"><p id="p19285936191613"><a name="p19285936191613"></a><a name="p19285936191613"></a>权限</p>
</th>
<th class="cellrowborder" valign="top" width="25%" id="mcps1.1.5.1.2"><p id="p5285183661617"><a name="p5285183661617"></a><a name="p5285183661617"></a>授权项</p>
</th>
<th class="cellrowborder" valign="top" width="25%" id="mcps1.1.5.1.3"><p id="p14286136131611"><a name="p14286136131611"></a><a name="p14286136131611"></a>授权范围</p>
</th>
<th class="cellrowborder" valign="top" width="25%" id="mcps1.1.5.1.4"><p id="p828693681612"><a name="p828693681612"></a><a name="p828693681612"></a>对应API接口</p>
</th>
</tr>
</thead>
<tbody><tr id="row16728728101618"><td class="cellrowborder" valign="top" width="25%" headers="mcps1.1.5.1.1 "><p id="p196094011610"><a name="p196094011610"></a><a name="p196094011610"></a>查询容量统计</p>
</td>
<td class="cellrowborder" valign="top" width="25%" headers="mcps1.1.5.1.2 "><p id="p596474713167"><a name="p596474713167"></a><a name="p596474713167"></a>cbr:backups:listStorageUsage</p>
</td>
<td class="cellrowborder" valign="top" width="25%" headers="mcps1.1.5.1.3 "><a name="ul16824253171613"></a><a name="ul16824253171613"></a><ul id="ul16824253171613"><li>支持：<a name="ul68243530161"></a><a name="ul68243530161"></a><ul id="ul68243530161"><li>项目（Project）</li><li>企业项目（Enterprise Project）</li></ul>
</li></ul>
</td>
<td class="cellrowborder" valign="top" width="25%" headers="mcps1.1.5.1.4 "><p id="p4113222174"><a name="p4113222174"></a><a name="p4113222174"></a>GET /v3/{project_id}/storage_usage</p>
</td>
</tr>
</tbody>
</table>

## 运营<a name="section124615815178"></a>

<a name="table15721152521714"></a>
<table><thead align="left"><tr id="row208111325121716"><th class="cellrowborder" valign="top" width="25%" id="mcps1.1.5.1.1"><p id="p667193191715"><a name="p667193191715"></a><a name="p667193191715"></a>权限</p>
</th>
<th class="cellrowborder" valign="top" width="25%" id="mcps1.1.5.1.2"><p id="p116717312173"><a name="p116717312173"></a><a name="p116717312173"></a>授权项</p>
</th>
<th class="cellrowborder" valign="top" width="25%" id="mcps1.1.5.1.3"><p id="p1067631141715"><a name="p1067631141715"></a><a name="p1067631141715"></a>授权范围</p>
</th>
<th class="cellrowborder" valign="top" width="25%" id="mcps1.1.5.1.4"><p id="p1067153181718"><a name="p1067153181718"></a><a name="p1067153181718"></a>对应API接口</p>
</th>
</tr>
</thead>
<tbody><tr id="row881182521716"><td class="cellrowborder" valign="top" width="25%" headers="mcps1.1.5.1.1 "><p id="p10811325141720"><a name="p10811325141720"></a><a name="p10811325141720"></a>变更</p>
</td>
<td class="cellrowborder" valign="top" width="25%" headers="mcps1.1.5.1.2 "><p id="p88231641141718"><a name="p88231641141718"></a><a name="p88231641141718"></a>cbr:vaults:updateOrder</p>
</td>
<td class="cellrowborder" valign="top" width="25%" headers="mcps1.1.5.1.3 "><a name="ul173164815176"></a><a name="ul173164815176"></a><ul id="ul173164815176"><li>支持：<a name="ul8731154891714"></a><a name="ul8731154891714"></a><ul id="ul8731154891714"><li>项目（Project）</li><li>企业项目（Enterprise Project）</li></ul>
</li></ul>
</td>
<td class="cellrowborder" valign="top" width="25%" headers="mcps1.1.5.1.4 "><p id="p1812316565173"><a name="p1812316565173"></a><a name="p1812316565173"></a>PUT /v3/{project_id}/orders/{order_id}</p>
</td>
</tr>
</tbody>
</table>

