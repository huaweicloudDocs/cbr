# API概览<a name="cbr_04_0007"></a>

云备份所提供的接口均为CBR接口，您可以通过这些接口完整的使用云备份的所有功能。

**表 1**  接口说明

<a name="table5876102613294"></a>
<table><thead align="left"><tr id="row3878122616298"><th class="cellrowborder" valign="top" width="22.89%" id="mcps1.2.3.1.1"><p id="p68781126182914"><a name="p68781126182914"></a><a name="p68781126182914"></a><strong id="b125201844173712"><a name="b125201844173712"></a><a name="b125201844173712"></a>类型</strong></p>
</th>
<th class="cellrowborder" valign="top" width="77.11%" id="mcps1.2.3.1.2"><p id="p158781726112914"><a name="p158781726112914"></a><a name="p158781726112914"></a><strong id="b15203449370"><a name="b15203449370"></a><a name="b15203449370"></a>说明</strong></p>
</th>
</tr>
</thead>
<tbody><tr id="row148781026122919"><td class="cellrowborder" valign="top" width="22.89%" headers="mcps1.2.3.1.1 "><p id="p19919713138"><a name="p19919713138"></a><a name="p19919713138"></a>任务</p>
</td>
<td class="cellrowborder" valign="top" width="77.11%" headers="mcps1.2.3.1.2 "><p id="p14101184217244"><a name="p14101184217244"></a><a name="p14101184217244"></a>可以查询任务列表和单个任务的情况。</p>
</td>
</tr>
<tr id="row9878726192911"><td class="cellrowborder" valign="top" width="22.89%" headers="mcps1.2.3.1.1 "><p id="p691614136316"><a name="p691614136316"></a><a name="p691614136316"></a>可保护性</p>
</td>
<td class="cellrowborder" valign="top" width="77.11%" headers="mcps1.2.3.1.2 "><p id="p10914131310310"><a name="p10914131310310"></a><a name="p10914131310310"></a>可以查询所在区域的复制能力，本区域是否支持复制备份和存储库。</p>
</td>
</tr>
<tr id="row9878172662914"><td class="cellrowborder" valign="top" width="22.89%" headers="mcps1.2.3.1.1 "><p id="p159145137312"><a name="p159145137312"></a><a name="p159145137312"></a>存储库</p>
</td>
<td class="cellrowborder" valign="top" width="77.11%" headers="mcps1.2.3.1.2 "><p id="p1291313132038"><a name="p1291313132038"></a><a name="p1291313132038"></a>可以实现创建存储库、存储库查询、为存储库绑定策略等操作。</p>
</td>
</tr>
<tr id="row117351143103220"><td class="cellrowborder" valign="top" width="22.89%" headers="mcps1.2.3.1.1 "><p id="p10912181316314"><a name="p10912181316314"></a><a name="p10912181316314"></a>备份共享</p>
</td>
<td class="cellrowborder" valign="top" width="77.11%" headers="mcps1.2.3.1.2 "><p id="p18911161316313"><a name="p18911161316313"></a><a name="p18911161316313"></a>用户可以将备份共享给其他用户使用。通过备份共享的接口完成备份共享的相关操作。</p>
</td>
</tr>
<tr id="row11736144363213"><td class="cellrowborder" valign="top" width="22.89%" headers="mcps1.2.3.1.1 "><p id="p179101131133"><a name="p179101131133"></a><a name="p179101131133"></a>还原点</p>
</td>
<td class="cellrowborder" valign="top" width="77.11%" headers="mcps1.2.3.1.2 "><p id="p19092013235"><a name="p19092013235"></a><a name="p19092013235"></a>可以实现对存储库执行备份、执行复制的操作，以及查询备份和复制创建的时间。</p>
</td>
</tr>
<tr id="row1685181354019"><td class="cellrowborder" valign="top" width="22.89%" headers="mcps1.2.3.1.1 "><p id="p11906013935"><a name="p11906013935"></a><a name="p11906013935"></a>备份</p>
</td>
<td class="cellrowborder" valign="top" width="77.11%" headers="mcps1.2.3.1.2 "><p id="p290481315319"><a name="p290481315319"></a><a name="p290481315319"></a>可以实现查询备份、同步备份副本、使用备份恢复数据等操作。</p>
</td>
</tr>
<tr id="row20988122813712"><td class="cellrowborder" valign="top" width="22.89%" headers="mcps1.2.3.1.1 "><p id="p1299013285371"><a name="p1299013285371"></a><a name="p1299013285371"></a>策略</p>
</td>
<td class="cellrowborder" valign="top" width="77.11%" headers="mcps1.2.3.1.2 "><p id="p499052810377"><a name="p499052810377"></a><a name="p499052810377"></a>绑定策略的存储库可以定期执行备份。通过策略相关接口完成创建策略、修改策略、查询策略等操作。</p>
</td>
</tr>
</tbody>
</table>

