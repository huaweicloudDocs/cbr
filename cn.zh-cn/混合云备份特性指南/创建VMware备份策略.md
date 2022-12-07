# 创建VMware备份策略<a name="cbr_03_0074"></a>

备份策略定义了执行备份任务和生成备份副本的规则。对备份计划设置备份策略后，才能执行备份任务。您可以灵活地创建不同的备份策略，以满足不同的备份需求。

## 操作步骤<a name="zh-cn_topic_0000001213204038_zh-cn_topic_0170955590_section21305513"></a>

1.  在导航栏上选择“![](figures/icon-upload.png)  \> 备份策略”。
2.  单击“创建”。
3.  设置备份策略基本信息。

    **表 1**  备份策略参数说明

    <a name="zh-cn_topic_0000001213204038_zh-cn_topic_0170955590_table4173735161316"></a>
    <table><thead align="left"><tr id="zh-cn_topic_0000001213204038_zh-cn_topic_0170955590_row1416033514131"><th class="cellrowborder" valign="top" width="14.288571142885711%" id="mcps1.2.4.1.1"><p id="zh-cn_topic_0000001213204038_zh-cn_topic_0170955590_p19160173510137"><a name="zh-cn_topic_0000001213204038_zh-cn_topic_0170955590_p19160173510137"></a><a name="zh-cn_topic_0000001213204038_zh-cn_topic_0170955590_p19160173510137"></a>参数名称</p>
    </th>
    <th class="cellrowborder" valign="top" width="40.815918408159185%" id="mcps1.2.4.1.2"><p id="zh-cn_topic_0000001213204038_zh-cn_topic_0170955590_p19160835201314"><a name="zh-cn_topic_0000001213204038_zh-cn_topic_0170955590_p19160835201314"></a><a name="zh-cn_topic_0000001213204038_zh-cn_topic_0170955590_p19160835201314"></a>参数说明</p>
    </th>
    <th class="cellrowborder" valign="top" width="44.89551044895511%" id="mcps1.2.4.1.3"><p id="zh-cn_topic_0000001213204038_zh-cn_topic_0170955590_p6160435141319"><a name="zh-cn_topic_0000001213204038_zh-cn_topic_0170955590_p6160435141319"></a><a name="zh-cn_topic_0000001213204038_zh-cn_topic_0170955590_p6160435141319"></a>设置原则</p>
    </th>
    </tr>
    </thead>
    <tbody><tr id="zh-cn_topic_0000001213204038_zh-cn_topic_0170955590_row516033518135"><td class="cellrowborder" valign="top" width="14.288571142885711%" headers="mcps1.2.4.1.1 "><p id="zh-cn_topic_0000001213204038_zh-cn_topic_0170955590_p101603354137"><a name="zh-cn_topic_0000001213204038_zh-cn_topic_0170955590_p101603354137"></a><a name="zh-cn_topic_0000001213204038_zh-cn_topic_0170955590_p101603354137"></a>备份策略名称</p>
    </td>
    <td class="cellrowborder" valign="top" width="40.815918408159185%" headers="mcps1.2.4.1.2 "><p id="zh-cn_topic_0000001213204038_zh-cn_topic_0170955590_p1916014352135"><a name="zh-cn_topic_0000001213204038_zh-cn_topic_0170955590_p1916014352135"></a><a name="zh-cn_topic_0000001213204038_zh-cn_topic_0170955590_p1916014352135"></a>用户自定义的备份策略名称。</p>
    </td>
    <td class="cellrowborder" valign="top" width="44.89551044895511%" headers="mcps1.2.4.1.3 "><p id="zh-cn_topic_0000001213204038_zh-cn_topic_0170955590_p131601135161314"><a name="zh-cn_topic_0000001213204038_zh-cn_topic_0170955590_p131601135161314"></a><a name="zh-cn_topic_0000001213204038_zh-cn_topic_0170955590_p131601135161314"></a>名称长度范围为1到128位，只能由字母、数字、中文字符、“+”、“_”、“-”、“.”、“@”组成。</p>
    </td>
    </tr>
    <tr id="zh-cn_topic_0000001213204038_zh-cn_topic_0170955590_row1161113514139"><td class="cellrowborder" valign="top" width="14.288571142885711%" headers="mcps1.2.4.1.1 "><p id="zh-cn_topic_0000001213204038_zh-cn_topic_0170955590_p10160203511136"><a name="zh-cn_topic_0000001213204038_zh-cn_topic_0170955590_p10160203511136"></a><a name="zh-cn_topic_0000001213204038_zh-cn_topic_0170955590_p10160203511136"></a>描述</p>
    </td>
    <td class="cellrowborder" valign="top" width="40.815918408159185%" headers="mcps1.2.4.1.2 "><p id="zh-cn_topic_0000001213204038_zh-cn_topic_0170955590_p5161335161317"><a name="zh-cn_topic_0000001213204038_zh-cn_topic_0170955590_p5161335161317"></a><a name="zh-cn_topic_0000001213204038_zh-cn_topic_0170955590_p5161335161317"></a>备份策略的描述。</p>
    </td>
    <td class="cellrowborder" valign="top" width="44.89551044895511%" headers="mcps1.2.4.1.3 "><p id="zh-cn_topic_0000001213204038_zh-cn_topic_0170955590_p1016173514138"><a name="zh-cn_topic_0000001213204038_zh-cn_topic_0170955590_p1016173514138"></a><a name="zh-cn_topic_0000001213204038_zh-cn_topic_0170955590_p1016173514138"></a>描述信息不能超过1024个字符。</p>
    </td>
    </tr>
    <tr id="zh-cn_topic_0000001213204038_zh-cn_topic_0170955590_row7163193513135"><td class="cellrowborder" valign="top" width="14.288571142885711%" headers="mcps1.2.4.1.1 "><p id="zh-cn_topic_0000001213204038_zh-cn_topic_0170955590_p1316153514133"><a name="zh-cn_topic_0000001213204038_zh-cn_topic_0170955590_p1316153514133"></a><a name="zh-cn_topic_0000001213204038_zh-cn_topic_0170955590_p1316153514133"></a>调度计划</p>
    </td>
    <td class="cellrowborder" valign="top" width="40.815918408159185%" headers="mcps1.2.4.1.2 "><p id="zh-cn_topic_0000001213204038_zh-cn_topic_0170955590_p3161635131315"><a name="zh-cn_topic_0000001213204038_zh-cn_topic_0170955590_p3161635131315"></a><a name="zh-cn_topic_0000001213204038_zh-cn_topic_0170955590_p3161635131315"></a>备份策略的备份任务执行计划。可设置“周期执行”和“执行一次”两种状态。</p>
    <p id="zh-cn_topic_0000001213204038_zh-cn_topic_0170955590_p3161835191313"><a name="zh-cn_topic_0000001213204038_zh-cn_topic_0170955590_p3161835191313"></a><a name="zh-cn_topic_0000001213204038_zh-cn_topic_0170955590_p3161835191313"></a>“调度计划”设置为“周期执行”时，需要设置增量备份的调度计划，也可根据需要选择是否开启周期性全量备份，参数说明如下：</p>
    <div class="note" id="zh-cn_topic_0000001213204038_zh-cn_topic_0170955590_note61611735141316"><a name="zh-cn_topic_0000001213204038_zh-cn_topic_0170955590_note61611735141316"></a><a name="zh-cn_topic_0000001213204038_zh-cn_topic_0170955590_note61611735141316"></a><span class="notetitle"> 说明： </span><div class="notebody"><p class="textintable" id="zh-cn_topic_0000001213204038_zh-cn_topic_0170955590_p171611435141314"><a name="zh-cn_topic_0000001213204038_zh-cn_topic_0170955590_p171611435141314"></a><a name="zh-cn_topic_0000001213204038_zh-cn_topic_0170955590_p171611435141314"></a>在同一时间点同时设置了增量备份和全量备份调度计划，系统会优先执行全量备份。</p>
    </div></div>
    <a name="zh-cn_topic_0000001213204038_zh-cn_topic_0170955590_ul7162163515139"></a><a name="zh-cn_topic_0000001213204038_zh-cn_topic_0170955590_ul7162163515139"></a><ul id="zh-cn_topic_0000001213204038_zh-cn_topic_0170955590_ul7162163515139"><li>按周执行：按照每周或每月第几周的固定日期执行备份。</li><li>按天执行：按照指定的时间（星期几）执行备份，与“按周执行”配合进行设置。例如设置为“每月第一周的星期三和星期日执行备份”。</li><li>排除天：排除每月的指定日期，即系统将不会在设定的这些天内执行备份任务。</li><li>执行时间点：设置备份任务具体的执行时间点，系统将在指定时间自动进行调度。可以设置一个或者多个时间点。系统将按照用户设置的时间点依次执行备份任务。</li><li>执行时间段：设置在具体的时间范围内按照指定的时间间隔执行多次备份。可以设置一个或者多个时间段。</li></ul>
    <div class="note" id="zh-cn_topic_0000001213204038_zh-cn_topic_0170955590_note816317351138"><a name="zh-cn_topic_0000001213204038_zh-cn_topic_0170955590_note816317351138"></a><a name="zh-cn_topic_0000001213204038_zh-cn_topic_0170955590_note816317351138"></a><span class="notetitle"> 说明： </span><div class="notebody"><a name="zh-cn_topic_0000001213204038_zh-cn_topic_0170955590_ul111631835111315"></a><a name="zh-cn_topic_0000001213204038_zh-cn_topic_0170955590_ul111631835111315"></a><ul id="zh-cn_topic_0000001213204038_zh-cn_topic_0170955590_ul111631835111315"><li>如果一次备份任务M在指定的时间间隔内未执行完成，将不会启动下一次备份任务。直到备份任务M执行完成后，系统按照指定的时间间隔继续执行备份任务。</li><li>如果在指定的时间间隔内向备份计划关联的保护集中新增虚拟机VM1，当一次备份任务N在指定的时间间隔内未执行完成，在到达时间间隔后，系统将启动对虚拟机VM1的备份任务。</li><li>当超过指定的时间范围时，如果有备份任务正在执行，将继续执行完成；如果有备份任务处于“等待调度”状态，将不会再执行备份任务。</li></ul>
    </div></div>
    </td>
    <td class="cellrowborder" valign="top" width="44.89551044895511%" headers="mcps1.2.4.1.3 "><p id="zh-cn_topic_0000001213204038_zh-cn_topic_0170955590_p91638358134"><a name="zh-cn_topic_0000001213204038_zh-cn_topic_0170955590_p91638358134"></a><a name="zh-cn_topic_0000001213204038_zh-cn_topic_0170955590_p91638358134"></a>对数据的备份越频繁，对数据的保护越充分，但是备份的时间也越长，所需的备份时间越长，占用的空间也越大。请根据数据的重要级别和业务量综合考虑选择，重要的数据采用较高的备份频率。</p>
    </td>
    </tr>
    <tr id="zh-cn_topic_0000001213204038_zh-cn_topic_0170955590_row216443581316"><td class="cellrowborder" valign="top" width="14.288571142885711%" headers="mcps1.2.4.1.1 "><p id="zh-cn_topic_0000001213204038_zh-cn_topic_0170955590_p9163163541317"><a name="zh-cn_topic_0000001213204038_zh-cn_topic_0170955590_p9163163541317"></a><a name="zh-cn_topic_0000001213204038_zh-cn_topic_0170955590_p9163163541317"></a>执行一次</p>
    </td>
    <td class="cellrowborder" valign="top" width="40.815918408159185%" headers="mcps1.2.4.1.2 "><p id="zh-cn_topic_0000001213204038_zh-cn_topic_0170955590_p171641335171319"><a name="zh-cn_topic_0000001213204038_zh-cn_topic_0170955590_p171641335171319"></a><a name="zh-cn_topic_0000001213204038_zh-cn_topic_0170955590_p171641335171319"></a>备份策略的备份任务只执行一次，此时需要设置备份策略的执行时间。此类型仅针对全量备份。“调度计划”设置为“执行一次”时，该参数可见。</p>
    </td>
    <td class="cellrowborder" valign="top" width="44.89551044895511%" headers="mcps1.2.4.1.3 "><p id="zh-cn_topic_0000001213204038_zh-cn_topic_0170955590_p17164203561320"><a name="zh-cn_topic_0000001213204038_zh-cn_topic_0170955590_p17164203561320"></a><a name="zh-cn_topic_0000001213204038_zh-cn_topic_0170955590_p17164203561320"></a>设置的执行时间需要晚于当前系统时间。</p>
    </td>
    </tr>
    <tr id="zh-cn_topic_0000001213204038_zh-cn_topic_0170955590_row5168135191316"><td class="cellrowborder" valign="top" width="14.288571142885711%" headers="mcps1.2.4.1.1 "><p id="zh-cn_topic_0000001213204038_zh-cn_topic_0170955590_p101643352132"><a name="zh-cn_topic_0000001213204038_zh-cn_topic_0170955590_p101643352132"></a><a name="zh-cn_topic_0000001213204038_zh-cn_topic_0170955590_p101643352132"></a>保留策略</p>
    </td>
    <td class="cellrowborder" valign="top" width="40.815918408159185%" headers="mcps1.2.4.1.2 "><p id="zh-cn_topic_0000001213204038_zh-cn_topic_0170955590_p1164143571314"><a name="zh-cn_topic_0000001213204038_zh-cn_topic_0170955590_p1164143571314"></a><a name="zh-cn_topic_0000001213204038_zh-cn_topic_0170955590_p1164143571314"></a>备份副本保留策略定义了一个受保护对象生成的备份副本能够保留多长时间或者保留多少数量。系统提供了以下三种“保留策略”类型。</p>
    <a name="zh-cn_topic_0000001213204038_zh-cn_topic_0170955590_ul7166153510135"></a><a name="zh-cn_topic_0000001213204038_zh-cn_topic_0170955590_ul7166153510135"></a><ul id="zh-cn_topic_0000001213204038_zh-cn_topic_0170955590_ul7166153510135"><li>永久保留<p id="zh-cn_topic_0000001213204038_zh-cn_topic_0170955590_p8164135121319"><a name="zh-cn_topic_0000001213204038_zh-cn_topic_0170955590_p8164135121319"></a><a name="zh-cn_topic_0000001213204038_zh-cn_topic_0170955590_p8164135121319"></a>备份副本将被永久保留。</p>
    </li><li>按备份副本数量<p id="zh-cn_topic_0000001213204038_zh-cn_topic_0170955590_p41658355138"><a name="zh-cn_topic_0000001213204038_zh-cn_topic_0170955590_p41658355138"></a><a name="zh-cn_topic_0000001213204038_zh-cn_topic_0170955590_p41658355138"></a>总共保留的备份副本数量</p>
    <p id="zh-cn_topic_0000001213204038_zh-cn_topic_0170955590_p17165163518131"><a name="zh-cn_topic_0000001213204038_zh-cn_topic_0170955590_p17165163518131"></a><a name="zh-cn_topic_0000001213204038_zh-cn_topic_0170955590_p17165163518131"></a>指一个受保护对象产生的备份副本保留的总数量。一旦生成的备份副本数超过该值，系统将自动删除生成时间最早的备份副本（且该备份副本不在以下每年/每月/每周/每日保留备份副本数量的范围之内）。</p>
    <p id="zh-cn_topic_0000001213204038_zh-cn_topic_0170955590_p101651235101318"><a name="zh-cn_topic_0000001213204038_zh-cn_topic_0170955590_p101651235101318"></a><a name="zh-cn_topic_0000001213204038_zh-cn_topic_0170955590_p101651235101318"></a>每年/每月/每周/每日保留备份副本数量</p>
    <p id="zh-cn_topic_0000001213204038_zh-cn_topic_0170955590_p19165123510134"><a name="zh-cn_topic_0000001213204038_zh-cn_topic_0170955590_p19165123510134"></a><a name="zh-cn_topic_0000001213204038_zh-cn_topic_0170955590_p19165123510134"></a>即从当前时间倒推至设定的xx年/xx月/xx周/xx日之间，每年/每月/每周/每日需要保留一份备份副本。例如，当前年限为2014，设置“保留3年备份”的保留策略后，系统将保留2011年、2012年、2013年每年内最新的一份备份副本。</p>
    </li><li>按时间<p id="zh-cn_topic_0000001213204038_zh-cn_topic_0170955590_p20165153510133"><a name="zh-cn_topic_0000001213204038_zh-cn_topic_0170955590_p20165153510133"></a><a name="zh-cn_topic_0000001213204038_zh-cn_topic_0170955590_p20165153510133"></a>保留周期</p>
    <p id="zh-cn_topic_0000001213204038_zh-cn_topic_0170955590_p1165123501319"><a name="zh-cn_topic_0000001213204038_zh-cn_topic_0170955590_p1165123501319"></a><a name="zh-cn_topic_0000001213204038_zh-cn_topic_0170955590_p1165123501319"></a>即按照备份策略生成的备份副本将保留xx年/xx月/xx周/xx日。从备份副本生成的时间开始计算，一旦超过设定的保留周期后，系统将自动删除过期的备份副本。</p>
    <p id="zh-cn_topic_0000001213204038_zh-cn_topic_0170955590_p1516615351139"><a name="zh-cn_topic_0000001213204038_zh-cn_topic_0170955590_p1516615351139"></a><a name="zh-cn_topic_0000001213204038_zh-cn_topic_0170955590_p1516615351139"></a>保留至</p>
    <p id="zh-cn_topic_0000001213204038_zh-cn_topic_0170955590_p616633513135"><a name="zh-cn_topic_0000001213204038_zh-cn_topic_0170955590_p616633513135"></a><a name="zh-cn_topic_0000001213204038_zh-cn_topic_0170955590_p616633513135"></a>即按照备份策略生成的备份副本将保留至设定的时间。从备份副本生成的时间开始计算，一旦超过设定的时间后，系统将自动删除过期的备份副本。</p>
    </li></ul>
    </td>
    <td class="cellrowborder" valign="top" width="44.89551044895511%" headers="mcps1.2.4.1.3 "><a name="zh-cn_topic_0000001213204038_zh-cn_topic_0170955590_ul616663510131"></a><a name="zh-cn_topic_0000001213204038_zh-cn_topic_0170955590_ul616663510131"></a><ul id="zh-cn_topic_0000001213204038_zh-cn_topic_0170955590_ul616663510131"><li>总共保留的备份副本数量的取值范围为1～100，默认值为90。</li><li>每年保留的备份副本数量的取值范围为0～999，默认值为10。</li><li>每月保留的备份副本数量的取值范围为0～999，默认值为10。</li><li>每周保留的备份副本数量的取值范围为0～9999，默认值为10。</li><li>每日保留的备份副本数量的取值范围为0～99999，默认值为10。</li></ul>
    <div class="note" id="zh-cn_topic_0000001213204038_zh-cn_topic_0170955590_note51666350136"><a name="zh-cn_topic_0000001213204038_zh-cn_topic_0170955590_note51666350136"></a><a name="zh-cn_topic_0000001213204038_zh-cn_topic_0170955590_note51666350136"></a><span class="notetitle"> 说明： </span><div class="notebody"><p class="textintable" id="zh-cn_topic_0000001213204038_zh-cn_topic_0170955590_p121661335161313"><a name="zh-cn_topic_0000001213204038_zh-cn_topic_0170955590_p121661335161313"></a><a name="zh-cn_topic_0000001213204038_zh-cn_topic_0170955590_p121661335161313"></a>总共保留的备份副本数量和按周期保留的备份副本数量不能同时为空。</p>
    </div></div>
    <a name="zh-cn_topic_0000001213204038_zh-cn_topic_0170955590_ul1216715354131"></a><a name="zh-cn_topic_0000001213204038_zh-cn_topic_0170955590_ul1216715354131"></a><ul id="zh-cn_topic_0000001213204038_zh-cn_topic_0170955590_ul1216715354131"><li>保留周期按照年计算的取值范围为1～25，默认值为1。</li><li>保留周期按照月计算的取值范围为1～300，默认值为1。</li><li>保留周期按照周计算的取值范围为1～1300，默认值为1。</li><li>保留周期按照天计算的取值范围为1～9125，默认值为1。</li></ul>
    <p id="zh-cn_topic_0000001213204038_zh-cn_topic_0170955590_p13167193516134"><a name="zh-cn_topic_0000001213204038_zh-cn_topic_0170955590_p13167193516134"></a><a name="zh-cn_topic_0000001213204038_zh-cn_topic_0170955590_p13167193516134"></a>永久保留备份副本可以满足任何时刻的恢复需求，但是早期的备份副本会持续占用存储库容量，无法实现空间的再利用。一旦存储库容量被用尽，系统将不再产生新的备份副本。</p>
    <p id="zh-cn_topic_0000001213204038_zh-cn_topic_0170955590_p18167113514134"><a name="zh-cn_topic_0000001213204038_zh-cn_topic_0170955590_p18167113514134"></a><a name="zh-cn_topic_0000001213204038_zh-cn_topic_0170955590_p18167113514134"></a>请综合以下两个因素进行考虑备份副本保留数量和保留时间：</p>
    <a name="zh-cn_topic_0000001213204038_zh-cn_topic_0170955590_ul816811357130"></a><a name="zh-cn_topic_0000001213204038_zh-cn_topic_0170955590_ul816811357130"></a><ul id="zh-cn_topic_0000001213204038_zh-cn_topic_0170955590_ul816811357130"><li>数据的重要性及对容灾的要求。如要求必须保留最近一个月的数据量，则建议保留周期定位一个月或以上。</li><li>存储库的可用存储容量。当存储库可用容量充足时，建议将重要性较高的备份副本保留比较多的数量或比较长的时间。</li></ul>
    </td>
    </tr>
    <tr id="zh-cn_topic_0000001213204038_zh-cn_topic_0170955590_row19170163512139"><td class="cellrowborder" valign="top" width="14.288571142885711%" headers="mcps1.2.4.1.1 "><p id="zh-cn_topic_0000001213204038_zh-cn_topic_0170955590_p161691135121316"><a name="zh-cn_topic_0000001213204038_zh-cn_topic_0170955590_p161691135121316"></a><a name="zh-cn_topic_0000001213204038_zh-cn_topic_0170955590_p161691135121316"></a>创建校验数据</p>
    </td>
    <td class="cellrowborder" valign="top" width="40.815918408159185%" headers="mcps1.2.4.1.2 "><p id="zh-cn_topic_0000001213204038_zh-cn_topic_0170955590_p10169173561320"><a name="zh-cn_topic_0000001213204038_zh-cn_topic_0170955590_p10169173561320"></a><a name="zh-cn_topic_0000001213204038_zh-cn_topic_0170955590_p10169173561320"></a>启用该选项后，系统将对备份数据创建校验数据，将对备份数据进行完整性和一致性校验。不启用该选项，系统仅对备份元数据做一致性校验。当后续需要对备份副本进行完全校验时，该校验数据用于确保备份数据的完整性和一致性。</p>
    <div class="note" id="zh-cn_topic_0000001213204038_zh-cn_topic_0170955590_note1117013519137"><a name="zh-cn_topic_0000001213204038_zh-cn_topic_0170955590_note1117013519137"></a><a name="zh-cn_topic_0000001213204038_zh-cn_topic_0170955590_note1117013519137"></a><span class="notetitle"> 说明： </span><div class="notebody"><p class="textintable" id="zh-cn_topic_0000001213204038_zh-cn_topic_0170955590_p16169135121316"><a name="zh-cn_topic_0000001213204038_zh-cn_topic_0170955590_p16169135121316"></a><a name="zh-cn_topic_0000001213204038_zh-cn_topic_0170955590_p16169135121316"></a>备份数据是指用户真实的数据。备份元数据是指标识备份的数据块位置、磁盘数量等额外相关的信息。</p>
    </div></div>
    </td>
    <td class="cellrowborder" valign="top" width="44.89551044895511%" headers="mcps1.2.4.1.3 "><p id="zh-cn_topic_0000001213204038_zh-cn_topic_0170955590_p31702357132"><a name="zh-cn_topic_0000001213204038_zh-cn_topic_0170955590_p31702357132"></a><a name="zh-cn_topic_0000001213204038_zh-cn_topic_0170955590_p31702357132"></a>启用该选项后，系统备份性能将会受到一定影响。如果对备份数据的完整性和一致性有较高要求，且对系统备份性能无特殊要求时，建议启用该选项，以确保恢复后的数据可用。</p>
    </td>
    </tr>
    <tr id="zh-cn_topic_0000001213204038_zh-cn_topic_0170955590_row9172535101317"><td class="cellrowborder" valign="top" width="14.288571142885711%" headers="mcps1.2.4.1.1 "><p id="zh-cn_topic_0000001213204038_zh-cn_topic_0170955590_p817017353131"><a name="zh-cn_topic_0000001213204038_zh-cn_topic_0170955590_p817017353131"></a><a name="zh-cn_topic_0000001213204038_zh-cn_topic_0170955590_p817017353131"></a>数据布局</p>
    </td>
    <td class="cellrowborder" valign="top" width="40.815918408159185%" headers="mcps1.2.4.1.2 "><p id="zh-cn_topic_0000001213204038_zh-cn_topic_0170955590_p21701835111316"><a name="zh-cn_topic_0000001213204038_zh-cn_topic_0170955590_p21701835111316"></a><a name="zh-cn_topic_0000001213204038_zh-cn_topic_0170955590_p21701835111316"></a>备份数据在备份存储上保存的数据格式，包括：</p>
    <p id="zh-cn_topic_0000001213204038_p5827827182411"><a name="zh-cn_topic_0000001213204038_p5827827182411"></a><a name="zh-cn_topic_0000001213204038_p5827827182411"></a>压缩：对备份数据进行压缩，可以有效节约备份存储的使用空间。</p>
    <a name="zh-cn_topic_0000001213204038_zh-cn_topic_0170955590_ul1170123519133"></a><a name="zh-cn_topic_0000001213204038_zh-cn_topic_0170955590_ul1170123519133"></a>
    </td>
    <td class="cellrowborder" valign="top" width="44.89551044895511%" headers="mcps1.2.4.1.3 "><p id="zh-cn_topic_0000001213204038_p28231250193720"><a name="zh-cn_topic_0000001213204038_p28231250193720"></a><a name="zh-cn_topic_0000001213204038_p28231250193720"></a>-</p>
    </td>
    </tr>
    <tr id="zh-cn_topic_0000001213204038_zh-cn_topic_0170955590_row017312356134"><td class="cellrowborder" valign="top" width="14.288571142885711%" headers="mcps1.2.4.1.1 "><p id="zh-cn_topic_0000001213204038_zh-cn_topic_0170955590_p01721935111318"><a name="zh-cn_topic_0000001213204038_zh-cn_topic_0170955590_p01721935111318"></a><a name="zh-cn_topic_0000001213204038_zh-cn_topic_0170955590_p01721935111318"></a>重试</p>
    </td>
    <td class="cellrowborder" valign="top" width="40.815918408159185%" headers="mcps1.2.4.1.2 "><p id="zh-cn_topic_0000001213204038_zh-cn_topic_0170955590_p4172163513131"><a name="zh-cn_topic_0000001213204038_zh-cn_topic_0170955590_p4172163513131"></a><a name="zh-cn_topic_0000001213204038_zh-cn_topic_0170955590_p4172163513131"></a>备份任务失败后的重试次数。设置该参数为“开启”时，可设置“重试次数”和“重试窗口”。重试窗口指备份失败的任务能够重试的最大时间范围。</p>
    </td>
    <td class="cellrowborder" valign="top" width="44.89551044895511%" headers="mcps1.2.4.1.3 "><p id="zh-cn_topic_0000001213204038_zh-cn_topic_0170955590_p18173153561317"><a name="zh-cn_topic_0000001213204038_zh-cn_topic_0170955590_p18173153561317"></a><a name="zh-cn_topic_0000001213204038_zh-cn_topic_0170955590_p18173153561317"></a>重试次数的取值范围为1～10。</p>
    <p id="zh-cn_topic_0000001213204038_zh-cn_topic_0170955590_p2017319351136"><a name="zh-cn_topic_0000001213204038_zh-cn_topic_0170955590_p2017319351136"></a><a name="zh-cn_topic_0000001213204038_zh-cn_topic_0170955590_p2017319351136"></a>重试窗口的取值范围为1～168。</p>
    <p id="zh-cn_topic_0000001213204038_zh-cn_topic_0170955590_p617383520136"><a name="zh-cn_topic_0000001213204038_zh-cn_topic_0170955590_p617383520136"></a><a name="zh-cn_topic_0000001213204038_zh-cn_topic_0170955590_p617383520136"></a>例如：在9:00执行第一次备份任务，9:10备份任务执行失败。设置重试3次，重试窗口为1小时，系统默认在备份任务失败5分钟后启动重试任务，则将在9:15～10:10期间执行重试任务。</p>
    <a name="zh-cn_topic_0000001213204038_zh-cn_topic_0170955590_ul1173193514134"></a><a name="zh-cn_topic_0000001213204038_zh-cn_topic_0170955590_ul1173193514134"></a><ul id="zh-cn_topic_0000001213204038_zh-cn_topic_0170955590_ul1173193514134"><li>如果在时间范围内重试3次，备份任务仍然执行失败，系统将停止重试备份任务。如果超过时间范围，未达到3次重试任务，备份任务仍然执行失败，系统也将停止重试备份任务。</li><li>如果在时间范围内只要有一次重试成功，则系统将停止重试备份任务。</li></ul>
    </td>
    </tr>
    </tbody>
    </table>

4.  单击“确定”。

