# CBR授权项分类<a name="cbr_04_0018"></a>

## 任务<a name="section20433131231818"></a>

<a name="table144113417188"></a>
<table><thead align="left"><tr id="row19131841161810"><th class="cellrowborder" valign="top" width="15.568443155684433%" id="mcps1.1.6.1.1"><p id="p6975162710197"><a name="p6975162710197"></a><a name="p6975162710197"></a>权限</p>
</th>
<th class="cellrowborder" valign="top" width="22.17778222177782%" id="mcps1.1.6.1.2"><p id="p097617278193"><a name="p097617278193"></a><a name="p097617278193"></a>对应API接口</p>
</th>
<th class="cellrowborder" valign="top" width="17.27827217278272%" id="mcps1.1.6.1.3"><p id="p199751827141918"><a name="p199751827141918"></a><a name="p199751827141918"></a>授权项</p>
</th>
<th class="cellrowborder" valign="top" width="18.118188181181882%" id="mcps1.1.6.1.4"><p id="p11824413353"><a name="p11824413353"></a><a name="p11824413353"></a>IAM项目</p>
<p id="p1115175017349"><a name="p1115175017349"></a><a name="p1115175017349"></a><span>(Project)</span></p>
</th>
<th class="cellrowborder" valign="top" width="26.857314268573145%" id="mcps1.1.6.1.5"><p id="p195365993414"><a name="p195365993414"></a><a name="p195365993414"></a>企业项目</p>
<p id="p6536595349"><a name="p6536595349"></a><a name="p6536595349"></a><span>(Enterprise Project)</span></p>
</th>
</tr>
</thead>
<tbody><tr id="row1132134119186"><td class="cellrowborder" valign="top" width="15.568443155684433%" headers="mcps1.1.6.1.1 "><p id="p10297641161912"><a name="p10297641161912"></a><a name="p10297641161912"></a>查询任务列表</p>
</td>
<td class="cellrowborder" valign="top" width="22.17778222177782%" headers="mcps1.1.6.1.2 "><p id="p1432417062011"><a name="p1432417062011"></a><a name="p1432417062011"></a>GET /v3/{project_id}/operation_logs</p>
</td>
<td class="cellrowborder" valign="top" width="17.27827217278272%" headers="mcps1.1.6.1.3 "><p id="p1745304771919"><a name="p1745304771919"></a><a name="p1745304771919"></a>cbr:tasks:list</p>
</td>
<td class="cellrowborder" valign="top" width="18.118188181181882%" headers="mcps1.1.6.1.4 "><p id="p196271245349"><a name="p196271245349"></a><a name="p196271245349"></a>√</p>
</td>
<td class="cellrowborder" valign="top" width="26.857314268573145%" headers="mcps1.1.6.1.5 "><p id="p121721910347"><a name="p121721910347"></a><a name="p121721910347"></a>√</p>
</td>
</tr>
<tr id="row7132164110184"><td class="cellrowborder" valign="top" width="15.568443155684433%" headers="mcps1.1.6.1.1 "><p id="p192971641111911"><a name="p192971641111911"></a><a name="p192971641111911"></a>查询单个任务</p>
</td>
<td class="cellrowborder" valign="top" width="22.17778222177782%" headers="mcps1.1.6.1.2 "><p id="p832416019209"><a name="p832416019209"></a><a name="p832416019209"></a>GET /v3/{project_id}/operation_logs/{operation_log_id}</p>
</td>
<td class="cellrowborder" valign="top" width="17.27827217278272%" headers="mcps1.1.6.1.3 "><p id="p184531847101912"><a name="p184531847101912"></a><a name="p184531847101912"></a>cbr:tasks:get</p>
</td>
<td class="cellrowborder" valign="top" width="18.118188181181882%" headers="mcps1.1.6.1.4 "><p id="p562702416345"><a name="p562702416345"></a><a name="p562702416345"></a>√</p>
</td>
<td class="cellrowborder" valign="top" width="26.857314268573145%" headers="mcps1.1.6.1.5 "><p id="p19170131193411"><a name="p19170131193411"></a><a name="p19170131193411"></a>√</p>
</td>
</tr>
</tbody>
</table>

## 可保护性<a name="section181615140268"></a>

<a name="table1829853692613"></a>
<table><thead align="left"><tr id="row74271936162611"><th class="cellrowborder" valign="top" width="15.310000000000002%" id="mcps1.1.7.1.1"><p id="p129917445262"><a name="p129917445262"></a><a name="p129917445262"></a>权限</p>
</th>
<th class="cellrowborder" valign="top" width="17.57%" id="mcps1.1.7.1.2"><p id="p21001644172615"><a name="p21001644172615"></a><a name="p21001644172615"></a>对应API接口</p>
</th>
<th class="cellrowborder" valign="top" width="15.15%" id="mcps1.1.7.1.3"><p id="p141006445268"><a name="p141006445268"></a><a name="p141006445268"></a>授权项</p>
</th>
<th class="cellrowborder" valign="top" width="20.23%" id="mcps1.1.7.1.4"><p id="p963910434415"><a name="p963910434415"></a><a name="p963910434415"></a>依赖的授权项</p>
</th>
<th class="cellrowborder" valign="top" width="15.939999999999998%" id="mcps1.1.7.1.5"><p id="p194222296423"><a name="p194222296423"></a><a name="p194222296423"></a>IAM项目</p>
<p id="p9422829124218"><a name="p9422829124218"></a><a name="p9422829124218"></a><span>(Project)</span></p>
</th>
<th class="cellrowborder" valign="top" width="15.8%" id="mcps1.1.7.1.6"><p id="p1821354134219"><a name="p1821354134219"></a><a name="p1821354134219"></a>企业项目</p>
<p id="p2021384114421"><a name="p2021384114421"></a><a name="p2021384114421"></a><span>(Enterprise Project)</span></p>
</th>
</tr>
</thead>
<tbody><tr id="row1242753632616"><td class="cellrowborder" valign="top" width="15.310000000000002%" headers="mcps1.1.7.1.1 "><p id="p690065416265"><a name="p690065416265"></a><a name="p690065416265"></a>查询可保护资源</p>
</td>
<td class="cellrowborder" valign="top" width="17.57%" headers="mcps1.1.7.1.2 "><p id="p06811538172717"><a name="p06811538172717"></a><a name="p06811538172717"></a>GET /v3/{project_id}/protectables/{protectable_type}</p>
</td>
<td class="cellrowborder" valign="top" width="15.15%" headers="mcps1.1.7.1.3 "><p id="p1413617169274"><a name="p1413617169274"></a><a name="p1413617169274"></a>cbr:vaults:listProtectables</p>
</td>
<td class="cellrowborder" valign="top" width="20.23%" headers="mcps1.1.7.1.4 "><p id="p28032191215"><a name="p28032191215"></a><a name="p28032191215"></a>ecs:cloudServers:list</p>
<p id="p1513671602711"><a name="p1513671602711"></a><a name="p1513671602711"></a>evs:volumes:list</p>
</td>
<td class="cellrowborder" valign="top" width="15.939999999999998%" headers="mcps1.1.7.1.5 "><p id="p11157133104310"><a name="p11157133104310"></a><a name="p11157133104310"></a>√</p>
</td>
<td class="cellrowborder" valign="top" width="15.8%" headers="mcps1.1.7.1.6 "><p id="p122357322410"><a name="p122357322410"></a><a name="p122357322410"></a>√</p>
</td>
</tr>
<tr id="row84277366267"><td class="cellrowborder" valign="top" width="15.310000000000002%" headers="mcps1.1.7.1.1 "><p id="p99001354192611"><a name="p99001354192611"></a><a name="p99001354192611"></a>查询指定可保护资源</p>
</td>
<td class="cellrowborder" valign="top" width="17.57%" headers="mcps1.1.7.1.2 "><p id="p1868173822713"><a name="p1868173822713"></a><a name="p1868173822713"></a>GET /v3/{project_id}/protectables/{protectable_type}/instances/{instance_id}</p>
</td>
<td class="cellrowborder" valign="top" width="15.15%" headers="mcps1.1.7.1.3 "><p id="p0136116132719"><a name="p0136116132719"></a><a name="p0136116132719"></a>cbr:vaults:getProtectables</p>
</td>
<td class="cellrowborder" valign="top" width="20.23%" headers="mcps1.1.7.1.4 "><p id="p8136316192713"><a name="p8136316192713"></a><a name="p8136316192713"></a>ecs:cloudServers:list</p>
<p id="p1713661662720"><a name="p1713661662720"></a><a name="p1713661662720"></a>evs:volumes:list</p>
</td>
<td class="cellrowborder" valign="top" width="15.939999999999998%" headers="mcps1.1.7.1.5 "><p id="p12868182811431"><a name="p12868182811431"></a><a name="p12868182811431"></a>√</p>
</td>
<td class="cellrowborder" valign="top" width="15.8%" headers="mcps1.1.7.1.6 "><p id="p172355323413"><a name="p172355323413"></a><a name="p172355323413"></a>√</p>
</td>
</tr>
<tr id="row1542813692618"><td class="cellrowborder" valign="top" width="15.310000000000002%" headers="mcps1.1.7.1.1 "><p id="p1990114544263"><a name="p1990114544263"></a><a name="p1990114544263"></a>查询agent状态</p>
</td>
<td class="cellrowborder" valign="top" width="17.57%" headers="mcps1.1.7.1.2 "><p id="p56814382274"><a name="p56814382274"></a><a name="p56814382274"></a>POST /v3/{project_id}/providers/{provider_id}/agent/check</p>
</td>
<td class="cellrowborder" valign="top" width="15.15%" headers="mcps1.1.7.1.3 "><p id="p2013610165277"><a name="p2013610165277"></a><a name="p2013610165277"></a>cbr:backups:checkAgent</p>
</td>
<td class="cellrowborder" valign="top" width="20.23%" headers="mcps1.1.7.1.4 "><p id="p56461840102120"><a name="p56461840102120"></a><a name="p56461840102120"></a>ecs:cloudServers:list</p>
</td>
<td class="cellrowborder" valign="top" width="15.939999999999998%" headers="mcps1.1.7.1.5 "><p id="p14189172517438"><a name="p14189172517438"></a><a name="p14189172517438"></a>√</p>
</td>
<td class="cellrowborder" valign="top" width="15.8%" headers="mcps1.1.7.1.6 "><p id="p42341032174113"><a name="p42341032174113"></a><a name="p42341032174113"></a>√</p>
</td>
</tr>
<tr id="row10428113632612"><td class="cellrowborder" valign="top" width="15.310000000000002%" headers="mcps1.1.7.1.1 "><p id="p2901354132610"><a name="p2901354132610"></a><a name="p2901354132610"></a>查询复制能力</p>
</td>
<td class="cellrowborder" valign="top" width="17.57%" headers="mcps1.1.7.1.2 "><p id="p3681123812274"><a name="p3681123812274"></a><a name="p3681123812274"></a>GET /v3/{project_id/replication_capabilities</p>
</td>
<td class="cellrowborder" valign="top" width="15.15%" headers="mcps1.1.7.1.3 "><p id="p813613162276"><a name="p813613162276"></a><a name="p813613162276"></a>cbr:backups:queryReplicationCapability</p>
</td>
<td class="cellrowborder" valign="top" width="20.23%" headers="mcps1.1.7.1.4 "><p id="p1863915431419"><a name="p1863915431419"></a><a name="p1863915431419"></a>-</p>
</td>
<td class="cellrowborder" valign="top" width="15.939999999999998%" headers="mcps1.1.7.1.5 "><p id="p456892111439"><a name="p456892111439"></a><a name="p456892111439"></a>√</p>
</td>
<td class="cellrowborder" valign="top" width="15.8%" headers="mcps1.1.7.1.6 "><p id="p19215732144119"><a name="p19215732144119"></a><a name="p19215732144119"></a>√</p>
</td>
</tr>
</tbody>
</table>

## 存储库<a name="section16923143918296"></a>

<a name="table784617325307"></a>
<table><thead align="left"><tr id="row92133314303"><th class="cellrowborder" valign="top" width="14.331433143314332%" id="mcps1.1.7.1.1"><p id="p16203154693018"><a name="p16203154693018"></a><a name="p16203154693018"></a>权限</p>
</th>
<th class="cellrowborder" valign="top" width="16.84168416841684%" id="mcps1.1.7.1.2"><p id="p13203446113018"><a name="p13203446113018"></a><a name="p13203446113018"></a>对应API接口</p>
</th>
<th class="cellrowborder" valign="top" width="17.511751175117514%" id="mcps1.1.7.1.3"><p id="p62032464302"><a name="p62032464302"></a><a name="p62032464302"></a>授权项</p>
</th>
<th class="cellrowborder" valign="top" width="16.53165316531653%" id="mcps1.1.7.1.4"><p id="p169312765818"><a name="p169312765818"></a><a name="p169312765818"></a>依赖的授权项</p>
</th>
<th class="cellrowborder" valign="top" width="18.391839183918393%" id="mcps1.1.7.1.5"><p id="p193068441599"><a name="p193068441599"></a><a name="p193068441599"></a>IAM项目</p>
<p id="p2306944175914"><a name="p2306944175914"></a><a name="p2306944175914"></a><span>(Project)</span></p>
</th>
<th class="cellrowborder" valign="top" width="16.39163916391639%" id="mcps1.1.7.1.6"><p id="p1159312397596"><a name="p1159312397596"></a><a name="p1159312397596"></a>企业项目</p>
<p id="p259353916598"><a name="p259353916598"></a><a name="p259353916598"></a><span>(Enterprise Project)</span></p>
</th>
</tr>
</thead>
<tbody><tr id="row18283333020"><td class="cellrowborder" valign="top" width="14.331433143314332%" headers="mcps1.1.7.1.1 "><p id="p18724017123110"><a name="p18724017123110"></a><a name="p18724017123110"></a>设置存储库策略</p>
</td>
<td class="cellrowborder" valign="top" width="16.84168416841684%" headers="mcps1.1.7.1.2 "><p id="p696803113217"><a name="p696803113217"></a><a name="p696803113217"></a>POST /v3/{project_id}/vaults/{vault_id}/associate_policy</p>
</td>
<td class="cellrowborder" valign="top" width="17.511751175117514%" headers="mcps1.1.7.1.3 "><p id="p727372843115"><a name="p727372843115"></a><a name="p727372843115"></a>cbr:vaults:associatePolicy</p>
</td>
<td class="cellrowborder" valign="top" width="16.53165316531653%" headers="mcps1.1.7.1.4 "><p id="p166991855585"><a name="p166991855585"></a><a name="p166991855585"></a>-</p>
</td>
<td class="cellrowborder" valign="top" width="18.391839183918393%" headers="mcps1.1.7.1.5 "><p id="p24162346020"><a name="p24162346020"></a><a name="p24162346020"></a>√</p>
</td>
<td class="cellrowborder" valign="top" width="16.39163916391639%" headers="mcps1.1.7.1.6 "><p id="p1373475135711"><a name="p1373475135711"></a><a name="p1373475135711"></a>√</p>
</td>
</tr>
<tr id="row1722333305"><td class="cellrowborder" valign="top" width="14.331433143314332%" headers="mcps1.1.7.1.1 "><p id="p1872420179319"><a name="p1872420179319"></a><a name="p1872420179319"></a>查询指定存储库</p>
</td>
<td class="cellrowborder" valign="top" width="16.84168416841684%" headers="mcps1.1.7.1.2 "><p id="p6968337328"><a name="p6968337328"></a><a name="p6968337328"></a>GET /v3/{project_id}/vaults/{vault_id}</p>
</td>
<td class="cellrowborder" valign="top" width="17.511751175117514%" headers="mcps1.1.7.1.3 "><p id="p3273122803113"><a name="p3273122803113"></a><a name="p3273122803113"></a>cbr:vaults:get</p>
</td>
<td class="cellrowborder" valign="top" width="16.53165316531653%" headers="mcps1.1.7.1.4 "><p id="p1269918575810"><a name="p1269918575810"></a><a name="p1269918575810"></a>-</p>
</td>
<td class="cellrowborder" valign="top" width="18.391839183918393%" headers="mcps1.1.7.1.5 "><p id="p1247693116012"><a name="p1247693116012"></a><a name="p1247693116012"></a>√</p>
</td>
<td class="cellrowborder" valign="top" width="16.39163916391639%" headers="mcps1.1.7.1.6 "><p id="p17733195120577"><a name="p17733195120577"></a><a name="p17733195120577"></a>√</p>
</td>
</tr>
<tr id="row83733123019"><td class="cellrowborder" valign="top" width="14.331433143314332%" headers="mcps1.1.7.1.1 "><p id="p7724141743111"><a name="p7724141743111"></a><a name="p7724141743111"></a>修改存储库</p>
</td>
<td class="cellrowborder" valign="top" width="16.84168416841684%" headers="mcps1.1.7.1.2 "><p id="p1896815315327"><a name="p1896815315327"></a><a name="p1896815315327"></a>PUT /v3/{project_id}/vaults/{vault_id}</p>
</td>
<td class="cellrowborder" valign="top" width="17.511751175117514%" headers="mcps1.1.7.1.3 "><p id="p182731528173118"><a name="p182731528173118"></a><a name="p182731528173118"></a>cbr:vaults:update</p>
</td>
<td class="cellrowborder" valign="top" width="16.53165316531653%" headers="mcps1.1.7.1.4 "><p id="p869918585817"><a name="p869918585817"></a><a name="p869918585817"></a>-</p>
</td>
<td class="cellrowborder" valign="top" width="18.391839183918393%" headers="mcps1.1.7.1.5 "><p id="p9629132714012"><a name="p9629132714012"></a><a name="p9629132714012"></a>√</p>
</td>
<td class="cellrowborder" valign="top" width="16.39163916391639%" headers="mcps1.1.7.1.6 "><p id="p19733195125715"><a name="p19733195125715"></a><a name="p19733195125715"></a>√</p>
</td>
</tr>
<tr id="row12313314302"><td class="cellrowborder" valign="top" width="14.331433143314332%" headers="mcps1.1.7.1.1 "><p id="p172416171313"><a name="p172416171313"></a><a name="p172416171313"></a>删除存储库</p>
</td>
<td class="cellrowborder" valign="top" width="16.84168416841684%" headers="mcps1.1.7.1.2 "><p id="p1396810353213"><a name="p1396810353213"></a><a name="p1396810353213"></a>DELETE /v3/{project_id}/vaults/{vault_id}</p>
</td>
<td class="cellrowborder" valign="top" width="17.511751175117514%" headers="mcps1.1.7.1.3 "><p id="p22731328193113"><a name="p22731328193113"></a><a name="p22731328193113"></a>cbr:vaults:delete</p>
</td>
<td class="cellrowborder" valign="top" width="16.53165316531653%" headers="mcps1.1.7.1.4 "><p id="p12699852581"><a name="p12699852581"></a><a name="p12699852581"></a>-</p>
</td>
<td class="cellrowborder" valign="top" width="18.391839183918393%" headers="mcps1.1.7.1.5 "><p id="p753732318019"><a name="p753732318019"></a><a name="p753732318019"></a>√</p>
</td>
<td class="cellrowborder" valign="top" width="16.39163916391639%" headers="mcps1.1.7.1.6 "><p id="p1273385117578"><a name="p1273385117578"></a><a name="p1273385117578"></a>√</p>
</td>
</tr>
<tr id="row2315331306"><td class="cellrowborder" valign="top" width="14.331433143314332%" headers="mcps1.1.7.1.1 "><p id="p1472419171312"><a name="p1472419171312"></a><a name="p1472419171312"></a>移除资源</p>
</td>
<td class="cellrowborder" valign="top" width="16.84168416841684%" headers="mcps1.1.7.1.2 "><p id="p4968535326"><a name="p4968535326"></a><a name="p4968535326"></a>POST /v3/{project_id}/vaults/{vault_id}/remove_resources</p>
</td>
<td class="cellrowborder" valign="top" width="17.511751175117514%" headers="mcps1.1.7.1.3 "><p id="p12731328143116"><a name="p12731328143116"></a><a name="p12731328143116"></a>cbr:vaults:removeResources</p>
</td>
<td class="cellrowborder" valign="top" width="16.53165316531653%" headers="mcps1.1.7.1.4 "><p id="p1869918575812"><a name="p1869918575812"></a><a name="p1869918575812"></a>-</p>
</td>
<td class="cellrowborder" valign="top" width="18.391839183918393%" headers="mcps1.1.7.1.5 "><p id="p1750181917016"><a name="p1750181917016"></a><a name="p1750181917016"></a>√</p>
</td>
<td class="cellrowborder" valign="top" width="16.39163916391639%" headers="mcps1.1.7.1.6 "><p id="p1373213515577"><a name="p1373213515577"></a><a name="p1373213515577"></a>√</p>
</td>
</tr>
<tr id="row174143333013"><td class="cellrowborder" valign="top" width="14.331433143314332%" headers="mcps1.1.7.1.1 "><p id="p1972441720318"><a name="p1972441720318"></a><a name="p1972441720318"></a>添加资源</p>
</td>
<td class="cellrowborder" valign="top" width="16.84168416841684%" headers="mcps1.1.7.1.2 "><p id="p09681239329"><a name="p09681239329"></a><a name="p09681239329"></a>POST /v3/{project_id}/vaults/{vault_id}/add_resources</p>
</td>
<td class="cellrowborder" valign="top" width="17.511751175117514%" headers="mcps1.1.7.1.3 "><p id="p52731728103111"><a name="p52731728103111"></a><a name="p52731728103111"></a>cbr:vaults:addResources</p>
</td>
<td class="cellrowborder" valign="top" width="16.53165316531653%" headers="mcps1.1.7.1.4 "><p id="p17273328103110"><a name="p17273328103110"></a><a name="p17273328103110"></a>ecs:cloudServers:list</p>
<p id="p6273132813116"><a name="p6273132813116"></a><a name="p6273132813116"></a>evs:volumes:list</p>
</td>
<td class="cellrowborder" valign="top" width="18.391839183918393%" headers="mcps1.1.7.1.5 "><p id="p12292151619017"><a name="p12292151619017"></a><a name="p12292151619017"></a>√</p>
</td>
<td class="cellrowborder" valign="top" width="16.39163916391639%" headers="mcps1.1.7.1.6 "><p id="p10732145145718"><a name="p10732145145718"></a><a name="p10732145145718"></a>√</p>
</td>
</tr>
<tr id="row74193313308"><td class="cellrowborder" valign="top" width="14.331433143314332%" headers="mcps1.1.7.1.1 "><p id="p072417171317"><a name="p072417171317"></a><a name="p072417171317"></a>查询存储库列表</p>
</td>
<td class="cellrowborder" valign="top" width="16.84168416841684%" headers="mcps1.1.7.1.2 "><p id="p119681131329"><a name="p119681131329"></a><a name="p119681131329"></a>GET /v3/{project_id}/vaults</p>
</td>
<td class="cellrowborder" valign="top" width="17.511751175117514%" headers="mcps1.1.7.1.3 "><p id="p427316289314"><a name="p427316289314"></a><a name="p427316289314"></a>cbr:vaults:list</p>
</td>
<td class="cellrowborder" valign="top" width="16.53165316531653%" headers="mcps1.1.7.1.4 "><p id="p3699751581"><a name="p3699751581"></a><a name="p3699751581"></a>-</p>
</td>
<td class="cellrowborder" valign="top" width="18.391839183918393%" headers="mcps1.1.7.1.5 "><p id="p13500131116011"><a name="p13500131116011"></a><a name="p13500131116011"></a>√</p>
</td>
<td class="cellrowborder" valign="top" width="16.39163916391639%" headers="mcps1.1.7.1.6 "><p id="p5731155165710"><a name="p5731155165710"></a><a name="p5731155165710"></a>√</p>
</td>
</tr>
<tr id="row135133318307"><td class="cellrowborder" valign="top" width="14.331433143314332%" headers="mcps1.1.7.1.1 "><p id="p972441733119"><a name="p972441733119"></a><a name="p972441733119"></a>创建存储库</p>
</td>
<td class="cellrowborder" valign="top" width="16.84168416841684%" headers="mcps1.1.7.1.2 "><p id="p9969232324"><a name="p9969232324"></a><a name="p9969232324"></a>POST /v3/{project_id}/vaults</p>
</td>
<td class="cellrowborder" valign="top" width="17.511751175117514%" headers="mcps1.1.7.1.3 "><p id="p927317289316"><a name="p927317289316"></a><a name="p927317289316"></a>cbr:vaults:create</p>
</td>
<td class="cellrowborder" valign="top" width="16.53165316531653%" headers="mcps1.1.7.1.4 "><p id="p19273152803119"><a name="p19273152803119"></a><a name="p19273152803119"></a>ecs:cloudServers:list</p>
<p id="p172731228203112"><a name="p172731228203112"></a><a name="p172731228203112"></a>evs:volumes:list</p>
</td>
<td class="cellrowborder" valign="top" width="18.391839183918393%" headers="mcps1.1.7.1.5 "><p id="p77821369012"><a name="p77821369012"></a><a name="p77821369012"></a>√</p>
</td>
<td class="cellrowborder" valign="top" width="16.39163916391639%" headers="mcps1.1.7.1.6 "><p id="p173116511577"><a name="p173116511577"></a><a name="p173116511577"></a>√</p>
</td>
</tr>
<tr id="row185203373014"><td class="cellrowborder" valign="top" width="14.331433143314332%" headers="mcps1.1.7.1.1 "><p id="p17725151714316"><a name="p17725151714316"></a><a name="p17725151714316"></a>查询其他区域存储库列表</p>
</td>
<td class="cellrowborder" valign="top" width="16.84168416841684%" headers="mcps1.1.7.1.2 "><p id="p1596983103215"><a name="p1596983103215"></a><a name="p1596983103215"></a>GET /v3/{project_id}/external_vaults</p>
</td>
<td class="cellrowborder" valign="top" width="17.511751175117514%" headers="mcps1.1.7.1.3 "><p id="p4274122823114"><a name="p4274122823114"></a><a name="p4274122823114"></a>cbr:vaults:listExternalVaults</p>
</td>
<td class="cellrowborder" valign="top" width="16.53165316531653%" headers="mcps1.1.7.1.4 "><p id="p827412283319"><a name="p827412283319"></a><a name="p827412283319"></a>cbr:vaults:listVaults</p>
</td>
<td class="cellrowborder" valign="top" width="18.391839183918393%" headers="mcps1.1.7.1.5 "><p id="p8615031209"><a name="p8615031209"></a><a name="p8615031209"></a>√</p>
</td>
<td class="cellrowborder" valign="top" width="16.39163916391639%" headers="mcps1.1.7.1.6 "><p id="p27306517579"><a name="p27306517579"></a><a name="p27306517579"></a>√</p>
</td>
</tr>
<tr id="row1593343017"><td class="cellrowborder" valign="top" width="14.331433143314332%" headers="mcps1.1.7.1.1 "><p id="p472512171315"><a name="p472512171315"></a><a name="p472512171315"></a>解除存储库策略</p>
</td>
<td class="cellrowborder" valign="top" width="16.84168416841684%" headers="mcps1.1.7.1.2 "><p id="p29699353212"><a name="p29699353212"></a><a name="p29699353212"></a>POST /v3/{project_id/vaults/{vault_id}/dissociate_policy</p>
</td>
<td class="cellrowborder" valign="top" width="17.511751175117514%" headers="mcps1.1.7.1.3 "><p id="p1327462818312"><a name="p1327462818312"></a><a name="p1327462818312"></a>cbr:vaults:dissociatePolicy</p>
</td>
<td class="cellrowborder" valign="top" width="16.53165316531653%" headers="mcps1.1.7.1.4 "><p id="p9699125155813"><a name="p9699125155813"></a><a name="p9699125155813"></a>-</p>
</td>
<td class="cellrowborder" valign="top" width="18.391839183918393%" headers="mcps1.1.7.1.5 "><p id="p57151059145913"><a name="p57151059145913"></a><a name="p57151059145913"></a>√</p>
</td>
<td class="cellrowborder" valign="top" width="16.39163916391639%" headers="mcps1.1.7.1.6 "><p id="p2073025105720"><a name="p2073025105720"></a><a name="p2073025105720"></a>√</p>
</td>
</tr>
</tbody>
</table>

## 还原点<a name="section2888611163913"></a>

<a name="table14941156153912"></a>
<table><thead align="left"><tr id="row1412215578392"><th class="cellrowborder" valign="top" width="14.62146214621462%" id="mcps1.1.7.1.1"><p id="p195441761406"><a name="p195441761406"></a><a name="p195441761406"></a>权限</p>
</th>
<th class="cellrowborder" valign="top" width="19.74197419741974%" id="mcps1.1.7.1.2"><p id="p10545267402"><a name="p10545267402"></a><a name="p10545267402"></a>对应API接口</p>
</th>
<th class="cellrowborder" valign="top" width="15.701570157015698%" id="mcps1.1.7.1.3"><p id="p1954514674015"><a name="p1954514674015"></a><a name="p1954514674015"></a>授权项</p>
</th>
<th class="cellrowborder" valign="top" width="17.42174217421742%" id="mcps1.1.7.1.4"><p id="p15760113818325"><a name="p15760113818325"></a><a name="p15760113818325"></a>依赖的授权项</p>
</th>
<th class="cellrowborder" valign="top" width="16.291629162916287%" id="mcps1.1.7.1.5"><p id="p1211444423219"><a name="p1211444423219"></a><a name="p1211444423219"></a>IAM项目</p>
<p id="p11148443320"><a name="p11148443320"></a><a name="p11148443320"></a><span>(Project)</span></p>
</th>
<th class="cellrowborder" valign="top" width="16.22162216221622%" id="mcps1.1.7.1.6"><p id="p2486948133214"><a name="p2486948133214"></a><a name="p2486948133214"></a>企业项目</p>
<p id="p1348616486325"><a name="p1348616486325"></a><a name="p1348616486325"></a><span>(Enterprise Project)</span></p>
</th>
</tr>
</thead>
<tbody><tr id="row0122175720392"><td class="cellrowborder" valign="top" width="14.62146214621462%" headers="mcps1.1.7.1.1 "><p id="p1482951612403"><a name="p1482951612403"></a><a name="p1482951612403"></a>同步备份还原点</p>
</td>
<td class="cellrowborder" valign="top" width="19.74197419741974%" headers="mcps1.1.7.1.2 "><p id="p18770173224019"><a name="p18770173224019"></a><a name="p18770173224019"></a>POST /v3/{project_id}/providers/{provider_id}/checkpoints/sync</p>
</td>
<td class="cellrowborder" valign="top" width="15.701570157015698%" headers="mcps1.1.7.1.3 "><p id="p177902115408"><a name="p177902115408"></a><a name="p177902115408"></a>cbr:vaults:sync</p>
</td>
<td class="cellrowborder" valign="top" width="17.42174217421742%" headers="mcps1.1.7.1.4 "><p id="p0287118143211"><a name="p0287118143211"></a><a name="p0287118143211"></a>-</p>
</td>
<td class="cellrowborder" valign="top" width="16.291629162916287%" headers="mcps1.1.7.1.5 "><p id="p14391239103510"><a name="p14391239103510"></a><a name="p14391239103510"></a>√</p>
</td>
<td class="cellrowborder" valign="top" width="16.22162216221622%" headers="mcps1.1.7.1.6 "><p id="p1579781192315"><a name="p1579781192315"></a><a name="p1579781192315"></a>√</p>
</td>
</tr>
<tr id="row13122175703915"><td class="cellrowborder" valign="top" width="14.62146214621462%" headers="mcps1.1.7.1.1 "><p id="p882913169402"><a name="p882913169402"></a><a name="p882913169402"></a>复制备份还原点</p>
</td>
<td class="cellrowborder" valign="top" width="19.74197419741974%" headers="mcps1.1.7.1.2 "><p id="p67701532184019"><a name="p67701532184019"></a><a name="p67701532184019"></a>POST /v3/{project_id}/providers/{provider_id}/checkpoints/replicate</p>
</td>
<td class="cellrowborder" valign="top" width="15.701570157015698%" headers="mcps1.1.7.1.3 "><p id="p477972113402"><a name="p477972113402"></a><a name="p477972113402"></a>cbr:vaults:replicate</p>
</td>
<td class="cellrowborder" valign="top" width="17.42174217421742%" headers="mcps1.1.7.1.4 "><p id="p12287198153215"><a name="p12287198153215"></a><a name="p12287198153215"></a>-</p>
</td>
<td class="cellrowborder" valign="top" width="16.291629162916287%" headers="mcps1.1.7.1.5 "><p id="p8144735123514"><a name="p8144735123514"></a><a name="p8144735123514"></a>√</p>
</td>
<td class="cellrowborder" valign="top" width="16.22162216221622%" headers="mcps1.1.7.1.6 "><p id="p57961217238"><a name="p57961217238"></a><a name="p57961217238"></a>√</p>
</td>
</tr>
<tr id="row12122125703914"><td class="cellrowborder" valign="top" width="14.62146214621462%" headers="mcps1.1.7.1.1 "><p id="p0829101615404"><a name="p0829101615404"></a><a name="p0829101615404"></a>创建备份还原点</p>
</td>
<td class="cellrowborder" valign="top" width="19.74197419741974%" headers="mcps1.1.7.1.2 "><p id="p57711832144012"><a name="p57711832144012"></a><a name="p57711832144012"></a>POST /v3/{project_id}/providers/{provider_id}/checkpoints</p>
</td>
<td class="cellrowborder" valign="top" width="15.701570157015698%" headers="mcps1.1.7.1.3 "><p id="p17779192144016"><a name="p17779192144016"></a><a name="p17779192144016"></a>cbr:vaults:backup</p>
</td>
<td class="cellrowborder" valign="top" width="17.42174217421742%" headers="mcps1.1.7.1.4 "><p id="p157791821144014"><a name="p157791821144014"></a><a name="p157791821144014"></a>ecs:cloudServers:list</p>
<p id="p977942117404"><a name="p977942117404"></a><a name="p977942117404"></a>evs:volumes:list</p>
</td>
<td class="cellrowborder" valign="top" width="16.291629162916287%" headers="mcps1.1.7.1.5 "><p id="p122813011352"><a name="p122813011352"></a><a name="p122813011352"></a>√</p>
</td>
<td class="cellrowborder" valign="top" width="16.22162216221622%" headers="mcps1.1.7.1.6 "><p id="p1379619118235"><a name="p1379619118235"></a><a name="p1379619118235"></a>√</p>
</td>
</tr>
</tbody>
</table>

## 备份共享<a name="section86041763166"></a>

<a name="table3636133011616"></a>
<table><thead align="left"><tr id="row6783113021611"><th class="cellrowborder" valign="top" width="15.06%" id="mcps1.1.6.1.1"><p id="p4568193812167"><a name="p4568193812167"></a><a name="p4568193812167"></a>权限</p>
</th>
<th class="cellrowborder" valign="top" width="24.34%" id="mcps1.1.6.1.2"><p id="p13568143851617"><a name="p13568143851617"></a><a name="p13568143851617"></a>对应API接口</p>
</th>
<th class="cellrowborder" valign="top" width="21.81%" id="mcps1.1.6.1.3"><p id="p1556818388166"><a name="p1556818388166"></a><a name="p1556818388166"></a>授权项</p>
</th>
<th class="cellrowborder" valign="top" width="18.73%" id="mcps1.1.6.1.4"><p id="p16260155843716"><a name="p16260155843716"></a><a name="p16260155843716"></a>IAM项目</p>
<p id="p1726017586376"><a name="p1726017586376"></a><a name="p1726017586376"></a><span>(Project)</span></p>
</th>
<th class="cellrowborder" valign="top" width="20.06%" id="mcps1.1.6.1.5"><p id="p35241046386"><a name="p35241046386"></a><a name="p35241046386"></a>企业项目</p>
<p id="p65240413816"><a name="p65240413816"></a><a name="p65240413816"></a><span>(Enterprise Project)</span></p>
</th>
</tr>
</thead>
<tbody><tr id="row2783143061611"><td class="cellrowborder" valign="top" width="15.06%" headers="mcps1.1.6.1.1 "><p id="p1893785571616"><a name="p1893785571616"></a><a name="p1893785571616"></a>添加备份成员</p>
</td>
<td class="cellrowborder" valign="top" width="24.34%" headers="mcps1.1.6.1.2 "><p id="p195811653491"><a name="p195811653491"></a><a name="p195811653491"></a>POST /v3/{project_id}/backups/{backup_id}/members</p>
</td>
<td class="cellrowborder" valign="top" width="21.81%" headers="mcps1.1.6.1.3 "><p id="p1742412178"><a name="p1742412178"></a><a name="p1742412178"></a>cbr:member:create</p>
</td>
<td class="cellrowborder" valign="top" width="18.73%" headers="mcps1.1.6.1.4 "><p id="p16318173216383"><a name="p16318173216383"></a><a name="p16318173216383"></a>√</p>
</td>
<td class="cellrowborder" valign="top" width="20.06%" headers="mcps1.1.6.1.5 "><p id="p1529844113710"><a name="p1529844113710"></a><a name="p1529844113710"></a>√</p>
</td>
</tr>
<tr id="row3783163019161"><td class="cellrowborder" valign="top" width="15.06%" headers="mcps1.1.6.1.1 "><p id="p179371355111613"><a name="p179371355111613"></a><a name="p179371355111613"></a>更新备份成员状态</p>
</td>
<td class="cellrowborder" valign="top" width="24.34%" headers="mcps1.1.6.1.2 "><p id="p7581057498"><a name="p7581057498"></a><a name="p7581057498"></a>PUT</p>
<p id="p115811574911"><a name="p115811574911"></a><a name="p115811574911"></a>/v3/{project_id}/backups/{backup_id}/members/{member_id}</p>
</td>
<td class="cellrowborder" valign="top" width="21.81%" headers="mcps1.1.6.1.3 "><p id="p47513431713"><a name="p47513431713"></a><a name="p47513431713"></a>cbr:member:update</p>
</td>
<td class="cellrowborder" valign="top" width="18.73%" headers="mcps1.1.6.1.4 "><p id="p983819288383"><a name="p983819288383"></a><a name="p983819288383"></a>√</p>
</td>
<td class="cellrowborder" valign="top" width="20.06%" headers="mcps1.1.6.1.5 "><p id="p145282440379"><a name="p145282440379"></a><a name="p145282440379"></a>√</p>
</td>
</tr>
<tr id="row178415304165"><td class="cellrowborder" valign="top" width="15.06%" headers="mcps1.1.6.1.1 "><p id="p1093775519165"><a name="p1093775519165"></a><a name="p1093775519165"></a>获取备份成员详情</p>
</td>
<td class="cellrowborder" valign="top" width="24.34%" headers="mcps1.1.6.1.2 "><p id="p1658112524919"><a name="p1658112524919"></a><a name="p1658112524919"></a>GET</p>
<p id="p858175194915"><a name="p858175194915"></a><a name="p858175194915"></a>/v3/{project_id}/backups/{backup_id}/members/{member_id}</p>
</td>
<td class="cellrowborder" valign="top" width="21.81%" headers="mcps1.1.6.1.3 "><p id="p87554171713"><a name="p87554171713"></a><a name="p87554171713"></a>cbr:member:get</p>
</td>
<td class="cellrowborder" valign="top" width="18.73%" headers="mcps1.1.6.1.4 "><p id="p15344325133816"><a name="p15344325133816"></a><a name="p15344325133816"></a>√</p>
</td>
<td class="cellrowborder" valign="top" width="20.06%" headers="mcps1.1.6.1.5 "><p id="p5527194414377"><a name="p5527194414377"></a><a name="p5527194414377"></a>√</p>
</td>
</tr>
<tr id="row17847309167"><td class="cellrowborder" valign="top" width="15.06%" headers="mcps1.1.6.1.1 "><p id="p19937145511165"><a name="p19937145511165"></a><a name="p19937145511165"></a>获取备份成员列表</p>
</td>
<td class="cellrowborder" valign="top" width="24.34%" headers="mcps1.1.6.1.2 "><p id="p0581195164912"><a name="p0581195164912"></a><a name="p0581195164912"></a>GET</p>
<p id="p95811351494"><a name="p95811351494"></a><a name="p95811351494"></a>/v3/{project_id}/backups/{backup_id}/members</p>
</td>
<td class="cellrowborder" valign="top" width="21.81%" headers="mcps1.1.6.1.3 "><p id="p127534191714"><a name="p127534191714"></a><a name="p127534191714"></a>cbr:member:list</p>
</td>
<td class="cellrowborder" valign="top" width="18.73%" headers="mcps1.1.6.1.4 "><p id="p1552522116388"><a name="p1552522116388"></a><a name="p1552522116388"></a>√</p>
</td>
<td class="cellrowborder" valign="top" width="20.06%" headers="mcps1.1.6.1.5 "><p id="p1152611445375"><a name="p1152611445375"></a><a name="p1152611445375"></a>√</p>
</td>
</tr>
<tr id="row4784830191617"><td class="cellrowborder" valign="top" width="15.06%" headers="mcps1.1.6.1.1 "><p id="p89381555151611"><a name="p89381555151611"></a><a name="p89381555151611"></a>删除指定的备份成员</p>
</td>
<td class="cellrowborder" valign="top" width="24.34%" headers="mcps1.1.6.1.2 "><p id="p12581125194911"><a name="p12581125194911"></a><a name="p12581125194911"></a>DELETE</p>
<p id="p19581175164910"><a name="p19581175164910"></a><a name="p19581175164910"></a>/v3/{project_id}/backups/{backup_id}/members/{member_id}</p>
</td>
<td class="cellrowborder" valign="top" width="21.81%" headers="mcps1.1.6.1.3 "><p id="p16751244173"><a name="p16751244173"></a><a name="p16751244173"></a>cbr:member:delete</p>
</td>
<td class="cellrowborder" valign="top" width="18.73%" headers="mcps1.1.6.1.4 "><p id="p144971617133810"><a name="p144971617133810"></a><a name="p144971617133810"></a>√</p>
</td>
<td class="cellrowborder" valign="top" width="20.06%" headers="mcps1.1.6.1.5 "><p id="p75261244193713"><a name="p75261244193713"></a><a name="p75261244193713"></a>√</p>
</td>
</tr>
</tbody>
</table>

## 备份<a name="section711017126813"></a>

<a name="table318611341082"></a>
<table><thead align="left"><tr id="row10335234582"><th class="cellrowborder" valign="top" width="13.36%" id="mcps1.1.7.1.1"><p id="p4143152891018"><a name="p4143152891018"></a><a name="p4143152891018"></a>权限</p>
</th>
<th class="cellrowborder" valign="top" width="16.520000000000003%" id="mcps1.1.7.1.2"><p id="p01439281106"><a name="p01439281106"></a><a name="p01439281106"></a>对应API接口</p>
</th>
<th class="cellrowborder" valign="top" width="17.080000000000002%" id="mcps1.1.7.1.3"><p id="p17143132841011"><a name="p17143132841011"></a><a name="p17143132841011"></a>授权项</p>
</th>
<th class="cellrowborder" valign="top" width="16.2%" id="mcps1.1.7.1.4"><p id="p15427851173912"><a name="p15427851173912"></a><a name="p15427851173912"></a>依赖的授权项</p>
</th>
<th class="cellrowborder" valign="top" width="20.62%" id="mcps1.1.7.1.5"><p id="p932772174014"><a name="p932772174014"></a><a name="p932772174014"></a>IAM项目</p>
<p id="p17327321134016"><a name="p17327321134016"></a><a name="p17327321134016"></a><span>(Project)</span></p>
</th>
<th class="cellrowborder" valign="top" width="16.220000000000002%" id="mcps1.1.7.1.6"><p id="p5852162494011"><a name="p5852162494011"></a><a name="p5852162494011"></a>企业项目</p>
<p id="p168520243401"><a name="p168520243401"></a><a name="p168520243401"></a><span>(Enterprise Project)</span></p>
</th>
</tr>
</thead>
<tbody><tr id="row11336143419818"><td class="cellrowborder" valign="top" width="13.36%" headers="mcps1.1.7.1.1 "><p id="p126249413815"><a name="p126249413815"></a><a name="p126249413815"></a>查询所有备份</p>
</td>
<td class="cellrowborder" valign="top" width="16.520000000000003%" headers="mcps1.1.7.1.2 "><p id="p182421326699"><a name="p182421326699"></a><a name="p182421326699"></a>GET /v3/{project_id}/providers/{provider_id}/backups</p>
</td>
<td class="cellrowborder" valign="top" width="17.080000000000002%" headers="mcps1.1.7.1.3 "><p id="p20921491681"><a name="p20921491681"></a><a name="p20921491681"></a>cbr:backups:list</p>
</td>
<td class="cellrowborder" valign="top" width="16.2%" headers="mcps1.1.7.1.4 "><p id="p19129191923915"><a name="p19129191923915"></a><a name="p19129191923915"></a>-</p>
</td>
<td class="cellrowborder" valign="top" width="20.62%" headers="mcps1.1.7.1.5 "><p id="p11522185614014"><a name="p11522185614014"></a><a name="p11522185614014"></a>√</p>
</td>
<td class="cellrowborder" valign="top" width="16.220000000000002%" headers="mcps1.1.7.1.6 "><p id="p17539819392"><a name="p17539819392"></a><a name="p17539819392"></a>√</p>
</td>
</tr>
<tr id="row143361349816"><td class="cellrowborder" valign="top" width="13.36%" headers="mcps1.1.7.1.1 "><p id="p15624541186"><a name="p15624541186"></a><a name="p15624541186"></a>查询指定备份</p>
</td>
<td class="cellrowborder" valign="top" width="16.520000000000003%" headers="mcps1.1.7.1.2 "><p id="p202429269913"><a name="p202429269913"></a><a name="p202429269913"></a>GET /v3/{project_id}/providers/{provider_id}/backups/{backup_id}</p>
</td>
<td class="cellrowborder" valign="top" width="17.080000000000002%" headers="mcps1.1.7.1.3 "><p id="p39234917820"><a name="p39234917820"></a><a name="p39234917820"></a>cbr:backups:get</p>
</td>
<td class="cellrowborder" valign="top" width="16.2%" headers="mcps1.1.7.1.4 "><p id="p1512951911394"><a name="p1512951911394"></a><a name="p1512951911394"></a>-</p>
</td>
<td class="cellrowborder" valign="top" width="20.62%" headers="mcps1.1.7.1.5 "><p id="p2724352184016"><a name="p2724352184016"></a><a name="p2724352184016"></a>√</p>
</td>
<td class="cellrowborder" valign="top" width="16.220000000000002%" headers="mcps1.1.7.1.6 "><p id="p155214833919"><a name="p155214833919"></a><a name="p155214833919"></a>√</p>
</td>
</tr>
<tr id="row133362349816"><td class="cellrowborder" valign="top" width="13.36%" headers="mcps1.1.7.1.1 "><p id="p10624541088"><a name="p10624541088"></a><a name="p10624541088"></a>删除备份</p>
</td>
<td class="cellrowborder" valign="top" width="16.520000000000003%" headers="mcps1.1.7.1.2 "><p id="p1242152613919"><a name="p1242152613919"></a><a name="p1242152613919"></a>DELETE /v3/{project_id}/providers/{provider_id}/backups/{backup_id}</p>
</td>
<td class="cellrowborder" valign="top" width="17.080000000000002%" headers="mcps1.1.7.1.3 "><p id="p159211491280"><a name="p159211491280"></a><a name="p159211491280"></a>cbr:backups:delete</p>
</td>
<td class="cellrowborder" valign="top" width="16.2%" headers="mcps1.1.7.1.4 "><p id="p151291219133914"><a name="p151291219133914"></a><a name="p151291219133914"></a>-</p>
</td>
<td class="cellrowborder" valign="top" width="20.62%" headers="mcps1.1.7.1.5 "><p id="p492994804011"><a name="p492994804011"></a><a name="p492994804011"></a>√</p>
</td>
<td class="cellrowborder" valign="top" width="16.220000000000002%" headers="mcps1.1.7.1.6 "><p id="p352198193911"><a name="p352198193911"></a><a name="p352198193911"></a>√</p>
</td>
</tr>
<tr id="row53371234881"><td class="cellrowborder" valign="top" width="13.36%" headers="mcps1.1.7.1.1 "><p id="p126251341188"><a name="p126251341188"></a><a name="p126251341188"></a>同步备份</p>
</td>
<td class="cellrowborder" valign="top" width="16.520000000000003%" headers="mcps1.1.7.1.2 "><p id="p17243122619915"><a name="p17243122619915"></a><a name="p17243122619915"></a>POST /v3/{project_id}/providers/{provider_id}/backups/sync</p>
</td>
<td class="cellrowborder" valign="top" width="17.080000000000002%" headers="mcps1.1.7.1.3 "><p id="p15930495812"><a name="p15930495812"></a><a name="p15930495812"></a>cbr:backups:sync</p>
</td>
<td class="cellrowborder" valign="top" width="16.2%" headers="mcps1.1.7.1.4 "><p id="p5129141983910"><a name="p5129141983910"></a><a name="p5129141983910"></a>-</p>
</td>
<td class="cellrowborder" valign="top" width="20.62%" headers="mcps1.1.7.1.5 "><p id="p119861245174013"><a name="p119861245174013"></a><a name="p119861245174013"></a>√</p>
</td>
<td class="cellrowborder" valign="top" width="16.220000000000002%" headers="mcps1.1.7.1.6 "><p id="p15119883915"><a name="p15119883915"></a><a name="p15119883915"></a>√</p>
</td>
</tr>
<tr id="row23371345814"><td class="cellrowborder" valign="top" width="13.36%" headers="mcps1.1.7.1.1 "><p id="p9625241185"><a name="p9625241185"></a><a name="p9625241185"></a>备份恢复</p>
</td>
<td class="cellrowborder" valign="top" width="16.520000000000003%" headers="mcps1.1.7.1.2 "><p id="p12243192612919"><a name="p12243192612919"></a><a name="p12243192612919"></a>POST /v3/{project_id}/providers/{provider_id}/backups/{backup_id}/restore</p>
</td>
<td class="cellrowborder" valign="top" width="17.080000000000002%" headers="mcps1.1.7.1.3 "><p id="p8935491180"><a name="p8935491180"></a><a name="p8935491180"></a>cbr:backups:restore</p>
</td>
<td class="cellrowborder" valign="top" width="16.2%" headers="mcps1.1.7.1.4 "><p id="p8934491288"><a name="p8934491288"></a><a name="p8934491288"></a>ecs:cloudServers:list</p>
<p id="p149384919812"><a name="p149384919812"></a><a name="p149384919812"></a>evs:volumes:list</p>
</td>
<td class="cellrowborder" valign="top" width="20.62%" headers="mcps1.1.7.1.5 "><p id="p6105943184020"><a name="p6105943184020"></a><a name="p6105943184020"></a>√</p>
</td>
<td class="cellrowborder" valign="top" width="16.220000000000002%" headers="mcps1.1.7.1.6 "><p id="p125048143919"><a name="p125048143919"></a><a name="p125048143919"></a>√</p>
</td>
</tr>
<tr id="row93379347810"><td class="cellrowborder" valign="top" width="13.36%" headers="mcps1.1.7.1.1 "><p id="p16625154112813"><a name="p16625154112813"></a><a name="p16625154112813"></a>复制备份</p>
</td>
<td class="cellrowborder" valign="top" width="16.520000000000003%" headers="mcps1.1.7.1.2 "><p id="p2243626391"><a name="p2243626391"></a><a name="p2243626391"></a>POST /v3/{project_id}/providers/{provider_id}/backups/{backup_id}/replicate</p>
</td>
<td class="cellrowborder" valign="top" width="17.080000000000002%" headers="mcps1.1.7.1.3 "><p id="p1693749785"><a name="p1693749785"></a><a name="p1693749785"></a>cbr:backups:replicate</p>
</td>
<td class="cellrowborder" valign="top" width="16.2%" headers="mcps1.1.7.1.4 "><p id="p12129519203917"><a name="p12129519203917"></a><a name="p12129519203917"></a>-</p>
</td>
<td class="cellrowborder" valign="top" width="20.62%" headers="mcps1.1.7.1.5 "><p id="p13248407405"><a name="p13248407405"></a><a name="p13248407405"></a>√</p>
</td>
<td class="cellrowborder" valign="top" width="16.220000000000002%" headers="mcps1.1.7.1.6 "><p id="p125068133911"><a name="p125068133911"></a><a name="p125068133911"></a>√</p>
</td>
</tr>
</tbody>
</table>

## 策略<a name="section6573939992"></a>

<a name="table1568916520917"></a>
<table><thead align="left"><tr id="row891614521994"><th class="cellrowborder" valign="top" width="14.540000000000001%" id="mcps1.1.6.1.1"><p id="p8742733181014"><a name="p8742733181014"></a><a name="p8742733181014"></a>权限</p>
</th>
<th class="cellrowborder" valign="top" width="23.03%" id="mcps1.1.6.1.2"><p id="p12743203351010"><a name="p12743203351010"></a><a name="p12743203351010"></a>对应API接口</p>
</th>
<th class="cellrowborder" valign="top" width="21.8%" id="mcps1.1.6.1.3"><p id="p9742143312105"><a name="p9742143312105"></a><a name="p9742143312105"></a>授权项</p>
</th>
<th class="cellrowborder" valign="top" width="19.35%" id="mcps1.1.6.1.4"><p id="p913035811419"><a name="p913035811419"></a><a name="p913035811419"></a>IAM项目</p>
<p id="p613025817411"><a name="p613025817411"></a><a name="p613025817411"></a><span>(Project)</span></p>
</th>
<th class="cellrowborder" valign="top" width="21.279999999999998%" id="mcps1.1.6.1.5"><p id="p33714204216"><a name="p33714204216"></a><a name="p33714204216"></a>企业项目</p>
<p id="p43717234213"><a name="p43717234213"></a><a name="p43717234213"></a><span>(Enterprise Project)</span></p>
</th>
</tr>
</thead>
<tbody><tr id="row291615210919"><td class="cellrowborder" valign="top" width="14.540000000000001%" headers="mcps1.1.6.1.1 "><p id="p457833814105"><a name="p457833814105"></a><a name="p457833814105"></a>查询策略列表</p>
</td>
<td class="cellrowborder" valign="top" width="23.03%" headers="mcps1.1.6.1.2 "><p id="p11936149161117"><a name="p11936149161117"></a><a name="p11936149161117"></a>GET /v3/{project_id}/policies</p>
</td>
<td class="cellrowborder" valign="top" width="21.8%" headers="mcps1.1.6.1.3 "><p id="p14136114218106"><a name="p14136114218106"></a><a name="p14136114218106"></a>cbr:policies:list</p>
</td>
<td class="cellrowborder" valign="top" width="19.35%" headers="mcps1.1.6.1.4 "><p id="p780143320426"><a name="p780143320426"></a><a name="p780143320426"></a>√</p>
</td>
<td class="cellrowborder" valign="top" width="21.279999999999998%" headers="mcps1.1.6.1.5 "><p id="p5756193834114"><a name="p5756193834114"></a><a name="p5756193834114"></a>√</p>
</td>
</tr>
<tr id="row18917205220914"><td class="cellrowborder" valign="top" width="14.540000000000001%" headers="mcps1.1.6.1.1 "><p id="p65781738151017"><a name="p65781738151017"></a><a name="p65781738151017"></a>创建策略</p>
</td>
<td class="cellrowborder" valign="top" width="23.03%" headers="mcps1.1.6.1.2 "><p id="p169366951114"><a name="p169366951114"></a><a name="p169366951114"></a>POST /v3/{project_id}/policies</p>
</td>
<td class="cellrowborder" valign="top" width="21.8%" headers="mcps1.1.6.1.3 "><p id="p1913710423108"><a name="p1913710423108"></a><a name="p1913710423108"></a>cbr:policies:create</p>
</td>
<td class="cellrowborder" valign="top" width="19.35%" headers="mcps1.1.6.1.4 "><p id="p9785142944219"><a name="p9785142944219"></a><a name="p9785142944219"></a>√</p>
</td>
<td class="cellrowborder" valign="top" width="21.279999999999998%" headers="mcps1.1.6.1.5 "><p id="p10756133834117"><a name="p10756133834117"></a><a name="p10756133834117"></a>√</p>
</td>
</tr>
<tr id="row129170520913"><td class="cellrowborder" valign="top" width="14.540000000000001%" headers="mcps1.1.6.1.1 "><p id="p17579193818101"><a name="p17579193818101"></a><a name="p17579193818101"></a>查询单个策略</p>
</td>
<td class="cellrowborder" valign="top" width="23.03%" headers="mcps1.1.6.1.2 "><p id="p14936396114"><a name="p14936396114"></a><a name="p14936396114"></a>GET /v3/{project_id/policies/{policy_id}</p>
</td>
<td class="cellrowborder" valign="top" width="21.8%" headers="mcps1.1.6.1.3 "><p id="p81371420102"><a name="p81371420102"></a><a name="p81371420102"></a>cbr:policies:get</p>
</td>
<td class="cellrowborder" valign="top" width="19.35%" headers="mcps1.1.6.1.4 "><p id="p13872322144210"><a name="p13872322144210"></a><a name="p13872322144210"></a>√</p>
</td>
<td class="cellrowborder" valign="top" width="21.279999999999998%" headers="mcps1.1.6.1.5 "><p id="p1775513386419"><a name="p1775513386419"></a><a name="p1775513386419"></a>√</p>
</td>
</tr>
<tr id="row89171052894"><td class="cellrowborder" valign="top" width="14.540000000000001%" headers="mcps1.1.6.1.1 "><p id="p19579203861012"><a name="p19579203861012"></a><a name="p19579203861012"></a>修改策略</p>
</td>
<td class="cellrowborder" valign="top" width="23.03%" headers="mcps1.1.6.1.2 "><p id="p189361951114"><a name="p189361951114"></a><a name="p189361951114"></a>PUT /v3/{project_id}/policies/{policy_id}</p>
</td>
<td class="cellrowborder" valign="top" width="21.8%" headers="mcps1.1.6.1.3 "><p id="p8137942201017"><a name="p8137942201017"></a><a name="p8137942201017"></a>cbr:policies:update</p>
</td>
<td class="cellrowborder" valign="top" width="19.35%" headers="mcps1.1.6.1.4 "><p id="p540661674210"><a name="p540661674210"></a><a name="p540661674210"></a>√</p>
</td>
<td class="cellrowborder" valign="top" width="21.279999999999998%" headers="mcps1.1.6.1.5 "><p id="p12754103804119"><a name="p12754103804119"></a><a name="p12754103804119"></a>√</p>
</td>
</tr>
<tr id="row179181552096"><td class="cellrowborder" valign="top" width="14.540000000000001%" headers="mcps1.1.6.1.1 "><p id="p3579538161013"><a name="p3579538161013"></a><a name="p3579538161013"></a>删除策略</p>
</td>
<td class="cellrowborder" valign="top" width="23.03%" headers="mcps1.1.6.1.2 "><p id="p993615901119"><a name="p993615901119"></a><a name="p993615901119"></a>DELETE /v3/{project_id}/policies/{policy_id}</p>
</td>
<td class="cellrowborder" valign="top" width="21.8%" headers="mcps1.1.6.1.3 "><p id="p13137154216107"><a name="p13137154216107"></a><a name="p13137154216107"></a>cbr:policies:delete</p>
</td>
<td class="cellrowborder" valign="top" width="19.35%" headers="mcps1.1.6.1.4 "><p id="p54021219421"><a name="p54021219421"></a><a name="p54021219421"></a>√</p>
</td>
<td class="cellrowborder" valign="top" width="21.279999999999998%" headers="mcps1.1.6.1.5 "><p id="p15753113812411"><a name="p15753113812411"></a><a name="p15753113812411"></a>√</p>
</td>
</tr>
</tbody>
</table>

## 标签<a name="section2078614164119"></a>

<a name="table12877153818110"></a>
<table><thead align="left"><tr id="row1804203951115"><th class="cellrowborder" valign="top" width="18.39%" id="mcps1.1.6.1.1"><p id="p1460919416138"><a name="p1460919416138"></a><a name="p1460919416138"></a>权限</p>
</th>
<th class="cellrowborder" valign="top" width="19.09%" id="mcps1.1.6.1.2"><p id="p10610445138"><a name="p10610445138"></a><a name="p10610445138"></a>对应API接口</p>
</th>
<th class="cellrowborder" valign="top" width="20.49%" id="mcps1.1.6.1.3"><p id="p760924131319"><a name="p760924131319"></a><a name="p760924131319"></a>授权项</p>
</th>
<th class="cellrowborder" valign="top" width="22.07%" id="mcps1.1.6.1.4"><p id="p11938182816438"><a name="p11938182816438"></a><a name="p11938182816438"></a>IAM项目</p>
<p id="p9938112815439"><a name="p9938112815439"></a><a name="p9938112815439"></a><span>(Project)</span></p>
</th>
<th class="cellrowborder" valign="top" width="19.96%" id="mcps1.1.6.1.5"><p id="p61871632204319"><a name="p61871632204319"></a><a name="p61871632204319"></a>企业项目</p>
<p id="p618710328431"><a name="p618710328431"></a><a name="p618710328431"></a><span>(Enterprise Project)</span></p>
</th>
</tr>
</thead>
<tbody><tr id="row15804163919116"><td class="cellrowborder" valign="top" width="18.39%" headers="mcps1.1.6.1.1 "><p id="p8871184818114"><a name="p8871184818114"></a><a name="p8871184818114"></a>查询存储库资源实例</p>
</td>
<td class="cellrowborder" valign="top" width="19.09%" headers="mcps1.1.6.1.2 "><p id="p884042917124"><a name="p884042917124"></a><a name="p884042917124"></a>POST /v3/{project_id}/vault/resource_instances/action</p>
</td>
<td class="cellrowborder" valign="top" width="20.49%" headers="mcps1.1.6.1.3 "><p id="p12122155301114"><a name="p12122155301114"></a><a name="p12122155301114"></a>cbr:vaults:listResourceInstances</p>
</td>
<td class="cellrowborder" valign="top" width="22.07%" headers="mcps1.1.6.1.4 "><p id="p131711536447"><a name="p131711536447"></a><a name="p131711536447"></a>√</p>
</td>
<td class="cellrowborder" valign="top" width="19.96%" headers="mcps1.1.6.1.5 "><p id="p7681053433"><a name="p7681053433"></a><a name="p7681053433"></a>√</p>
</td>
</tr>
<tr id="row78051139181117"><td class="cellrowborder" valign="top" width="18.39%" headers="mcps1.1.6.1.1 "><p id="p08714483118"><a name="p08714483118"></a><a name="p08714483118"></a>批量添加删除存储库资源标签</p>
</td>
<td class="cellrowborder" valign="top" width="19.09%" headers="mcps1.1.6.1.2 "><p id="p118404296124"><a name="p118404296124"></a><a name="p118404296124"></a>POST /v3/{project_id}/vault/{vault_id}/tags/action</p>
</td>
<td class="cellrowborder" valign="top" width="20.49%" headers="mcps1.1.6.1.3 "><p id="p81226533115"><a name="p81226533115"></a><a name="p81226533115"></a>cbr:vaults:bulkCreateOrDeleteTags</p>
</td>
<td class="cellrowborder" valign="top" width="22.07%" headers="mcps1.1.6.1.4 "><p id="p17410592433"><a name="p17410592433"></a><a name="p17410592433"></a>√</p>
</td>
<td class="cellrowborder" valign="top" width="19.96%" headers="mcps1.1.6.1.5 "><p id="p10682574318"><a name="p10682574318"></a><a name="p10682574318"></a>√</p>
</td>
</tr>
<tr id="row18051039201112"><td class="cellrowborder" valign="top" width="18.39%" headers="mcps1.1.6.1.1 "><p id="p17871048191113"><a name="p17871048191113"></a><a name="p17871048191113"></a>添加存储库资源标签</p>
</td>
<td class="cellrowborder" valign="top" width="19.09%" headers="mcps1.1.6.1.2 "><p id="p584132941210"><a name="p584132941210"></a><a name="p584132941210"></a>POST /v3/{project_id/vault/{vault_id}/tags</p>
</td>
<td class="cellrowborder" valign="top" width="20.49%" headers="mcps1.1.6.1.3 "><p id="p712216532115"><a name="p712216532115"></a><a name="p712216532115"></a>cbr:vaults:setTags</p>
</td>
<td class="cellrowborder" valign="top" width="22.07%" headers="mcps1.1.6.1.4 "><p id="p737011556431"><a name="p737011556431"></a><a name="p737011556431"></a>√</p>
</td>
<td class="cellrowborder" valign="top" width="19.96%" headers="mcps1.1.6.1.5 "><p id="p66795114312"><a name="p66795114312"></a><a name="p66795114312"></a>√</p>
</td>
</tr>
<tr id="row12805139181111"><td class="cellrowborder" valign="top" width="18.39%" headers="mcps1.1.6.1.1 "><p id="p18711748101112"><a name="p18711748101112"></a><a name="p18711748101112"></a>删除存储库资源标签</p>
</td>
<td class="cellrowborder" valign="top" width="19.09%" headers="mcps1.1.6.1.2 "><p id="p1284117292122"><a name="p1284117292122"></a><a name="p1284117292122"></a>DELETE /v3/{project_id}/vault/{vault_id}/tags/{key}</p>
</td>
<td class="cellrowborder" valign="top" width="20.49%" headers="mcps1.1.6.1.3 "><p id="p16122175381115"><a name="p16122175381115"></a><a name="p16122175381115"></a>cbr:vaults:deleteTags</p>
</td>
<td class="cellrowborder" valign="top" width="22.07%" headers="mcps1.1.6.1.4 "><p id="p17296651124312"><a name="p17296651124312"></a><a name="p17296651124312"></a>√</p>
</td>
<td class="cellrowborder" valign="top" width="19.96%" headers="mcps1.1.6.1.5 "><p id="p166713515436"><a name="p166713515436"></a><a name="p166713515436"></a>√</p>
</td>
</tr>
<tr id="row10806133941110"><td class="cellrowborder" valign="top" width="18.39%" headers="mcps1.1.6.1.1 "><p id="p17872124851120"><a name="p17872124851120"></a><a name="p17872124851120"></a>查询存储库资源标签</p>
</td>
<td class="cellrowborder" valign="top" width="19.09%" headers="mcps1.1.6.1.2 "><p id="p48414293128"><a name="p48414293128"></a><a name="p48414293128"></a>GET /v3/{project_id}/vault/{vault_id}/tags</p>
</td>
<td class="cellrowborder" valign="top" width="20.49%" headers="mcps1.1.6.1.3 "><p id="p13122185313117"><a name="p13122185313117"></a><a name="p13122185313117"></a>cbr:vaults:getTags</p>
</td>
<td class="cellrowborder" valign="top" width="22.07%" headers="mcps1.1.6.1.4 "><p id="p19337347124314"><a name="p19337347124314"></a><a name="p19337347124314"></a>√</p>
</td>
<td class="cellrowborder" valign="top" width="19.96%" headers="mcps1.1.6.1.5 "><p id="p10673514436"><a name="p10673514436"></a><a name="p10673514436"></a>√</p>
</td>
</tr>
<tr id="row1880603915110"><td class="cellrowborder" valign="top" width="18.39%" headers="mcps1.1.6.1.1 "><p id="p16872144861111"><a name="p16872144861111"></a><a name="p16872144861111"></a>查询存储库项目标签</p>
</td>
<td class="cellrowborder" valign="top" width="19.09%" headers="mcps1.1.6.1.2 "><p id="p98411829191217"><a name="p98411829191217"></a><a name="p98411829191217"></a>GET /v3/{project_id}/vault/tags</p>
</td>
<td class="cellrowborder" valign="top" width="20.49%" headers="mcps1.1.6.1.3 "><p id="p1812285311112"><a name="p1812285311112"></a><a name="p1812285311112"></a>cbr:vaults:listProjectTags</p>
</td>
<td class="cellrowborder" valign="top" width="22.07%" headers="mcps1.1.6.1.4 "><p id="p2408164304315"><a name="p2408164304315"></a><a name="p2408164304315"></a>√</p>
</td>
<td class="cellrowborder" valign="top" width="19.96%" headers="mcps1.1.6.1.5 "><p id="p8471357432"><a name="p8471357432"></a><a name="p8471357432"></a>√</p>
</td>
</tr>
</tbody>
</table>

## 计量<a name="section731275621512"></a>

<a name="table1267711282162"></a>
<table><thead align="left"><tr id="row8727122831619"><th class="cellrowborder" valign="top" width="14.800000000000002%" id="mcps1.1.6.1.1"><p id="p19285936191613"><a name="p19285936191613"></a><a name="p19285936191613"></a>权限</p>
</th>
<th class="cellrowborder" valign="top" width="17.510000000000005%" id="mcps1.1.6.1.2"><p id="p828693681612"><a name="p828693681612"></a><a name="p828693681612"></a>对应API接口</p>
</th>
<th class="cellrowborder" valign="top" width="21.450000000000003%" id="mcps1.1.6.1.3"><p id="p5285183661617"><a name="p5285183661617"></a><a name="p5285183661617"></a>授权项</p>
</th>
<th class="cellrowborder" valign="top" width="23.12%" id="mcps1.1.6.1.4"><p id="p1436704104612"><a name="p1436704104612"></a><a name="p1436704104612"></a>IAM项目</p>
<p id="p17367114124614"><a name="p17367114124614"></a><a name="p17367114124614"></a><span>(Project)</span></p>
</th>
<th class="cellrowborder" valign="top" width="23.12%" id="mcps1.1.6.1.5"><p id="p112901095464"><a name="p112901095464"></a><a name="p112901095464"></a>企业项目</p>
<p id="p729012974614"><a name="p729012974614"></a><a name="p729012974614"></a><span>(Enterprise Project)</span></p>
</th>
</tr>
</thead>
<tbody><tr id="row16728728101618"><td class="cellrowborder" valign="top" width="14.800000000000002%" headers="mcps1.1.6.1.1 "><p id="p196094011610"><a name="p196094011610"></a><a name="p196094011610"></a>查询容量统计</p>
</td>
<td class="cellrowborder" valign="top" width="17.510000000000005%" headers="mcps1.1.6.1.2 "><p id="p4113222174"><a name="p4113222174"></a><a name="p4113222174"></a>GET /v3/{project_id}/storage_usage</p>
</td>
<td class="cellrowborder" valign="top" width="21.450000000000003%" headers="mcps1.1.6.1.3 "><p id="p596474713167"><a name="p596474713167"></a><a name="p596474713167"></a>cbr:backups:listStorageUsage</p>
</td>
<td class="cellrowborder" valign="top" width="23.12%" headers="mcps1.1.6.1.4 "><p id="p1464381513466"><a name="p1464381513466"></a><a name="p1464381513466"></a>√</p>
</td>
<td class="cellrowborder" valign="top" width="23.12%" headers="mcps1.1.6.1.5 "><p id="p6474185494517"><a name="p6474185494517"></a><a name="p6474185494517"></a>√</p>
</td>
</tr>
</tbody>
</table>

## 运营<a name="section124615815178"></a>

<a name="table15721152521714"></a>
<table><thead align="left"><tr id="row208111325121716"><th class="cellrowborder" valign="top" width="14.710000000000004%" id="mcps1.1.6.1.1"><p id="p667193191715"><a name="p667193191715"></a><a name="p667193191715"></a>权限</p>
</th>
<th class="cellrowborder" valign="top" width="17.950000000000003%" id="mcps1.1.6.1.2"><p id="p1067153181718"><a name="p1067153181718"></a><a name="p1067153181718"></a>对应API接口</p>
</th>
<th class="cellrowborder" valign="top" width="21.1%" id="mcps1.1.6.1.3"><p id="p116717312173"><a name="p116717312173"></a><a name="p116717312173"></a>授权项</p>
</th>
<th class="cellrowborder" valign="top" width="23.12%" id="mcps1.1.6.1.4"><p id="p165791944194611"><a name="p165791944194611"></a><a name="p165791944194611"></a>IAM项目</p>
<p id="p125791444184614"><a name="p125791444184614"></a><a name="p125791444184614"></a><span>(Project)</span></p>
</th>
<th class="cellrowborder" valign="top" width="23.12%" id="mcps1.1.6.1.5"><p id="p1343864834616"><a name="p1343864834616"></a><a name="p1343864834616"></a>企业项目</p>
<p id="p2043816489466"><a name="p2043816489466"></a><a name="p2043816489466"></a><span>(Enterprise Project)</span></p>
</th>
</tr>
</thead>
<tbody><tr id="row881182521716"><td class="cellrowborder" valign="top" width="14.710000000000004%" headers="mcps1.1.6.1.1 "><p id="p10811325141720"><a name="p10811325141720"></a><a name="p10811325141720"></a>变更</p>
</td>
<td class="cellrowborder" valign="top" width="17.950000000000003%" headers="mcps1.1.6.1.2 "><p id="p1812316565173"><a name="p1812316565173"></a><a name="p1812316565173"></a>PUT /v3/{project_id}/orders/{order_id}</p>
</td>
<td class="cellrowborder" valign="top" width="21.1%" headers="mcps1.1.6.1.3 "><p id="p88231641141718"><a name="p88231641141718"></a><a name="p88231641141718"></a>cbr:vaults:updateOrder</p>
</td>
<td class="cellrowborder" valign="top" width="23.12%" headers="mcps1.1.6.1.4 "><p id="p1249235216462"><a name="p1249235216462"></a><a name="p1249235216462"></a>√</p>
</td>
<td class="cellrowborder" valign="top" width="23.12%" headers="mcps1.1.6.1.5 "><p id="p29212355468"><a name="p29212355468"></a><a name="p29212355468"></a>√</p>
</td>
</tr>
</tbody>
</table>

