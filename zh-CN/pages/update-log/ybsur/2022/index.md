# 更新日志 经典生存 2022年

## 1月

### 2022-1-26
1. 程序更新
  1. 修复闪电
  2. 修复一个离线传送的问题
  3. 修复骑乘生物时失去+Y方向的运动
  4. 修复一些其他错误
2. 移除了用于1.17中对log4j2的修补措施（因为不再需要，过时的）

### 2022-1-14
  1. 更新插件
  2.
  潜影贝重生机制得到了更新，现在可以运行在1.18中
  3.
  渲染距离调整至16，模拟距离调整至10。无运算距离为11到16。
  4.
  更新NEWS中的信息
  5.
  主世界地图升级，增加-64地形
  6.
  主程序更新：1.17.1->1.18.1，撒花✿✿ヽ(°▽°)ノ✿

## 2月

### 2022-2-10
  1. 增加对1.17以下版本保护，使其不会卡入负高度*
  2. 增加/kit命令，添加“纪念品·桃源岛·二代 黄桑摸鱼”，每天会增加一个可以领取的项目，每个项目有效期24小时，只要当天黄桑摸鱼了就会增加
  3. 主程序更新*：
    1. 完全治愈时使铁傀儡不再愤怒
    2. 修复敌对生物在互动过程中消失的问题
    3. 修复幻翼在白天可能不会燃烧的问题
    4. 修复MC-50647、MC-238526
    5. [重要]修复因为升级导致地狱门的链接被破坏

注：带*号的条目将在次日重启后生效

## 3月

### 2022-3-3~4
  1. 【数据删除】
    1. 【数据删除】
    2. 修复管理员命令“tppos”y轴不能高于256的问题
    3. 修复聊天过滤器无法正确加载的小问题
    4. 修复管理员命令“tpall”的一些问题
  2. 【数据删除】
  3. 增加了一个新的命令：/menu，用于打开菜单
  4. 菜单中的“返回大厅”功能已可用
  5. 更新部分功能提示，使其适配格式
  6. 菜单-个人设置中新增“私信开关”功能，可以关闭私信接受：该功能从大厅移动至各子服务器
  7. 菜单中将可以看到你所拥有的“经典生存硬币”数量
  8. 【反恶意破坏】程序更新：强化爆炸跟踪、强化物品展示框记录
  9. 服务端主程序】更新：【数据删除】
  10. 【跨版本系统】更新：支持1.18.2客户端进入、修复花盆放置动画、修复一些其他问题
  11. 调整了“区块加载器”，新增【迷你加载器（半径2区块）】12小时、24小时

### 2022-3-7

1. 更新了部分死亡消息：这是一个大工程，我们会逐步推进

### 2022-3-8
1. 修复因【反恶意破坏】程序的更新，导致TNT复制故障的问题（感谢wwt_19、Leaves的反馈）
2. 更新了部分死亡消息p2：这是一个大工程，我们会逐步推进

### 2022-3-9
1. [数据删除]
2. 权限更新：现在玩家可以放置以激活区块加载器
3. 更新了部分死亡消息p3：这是一个大工程，我们会逐步推进


### 2022-3-10
1. 新增/help命令
2. 在线时间中的奖励“硬币”已由“经典生存硬币”代替
3. 设置菜单中增加了“启用额外功能”的按钮，开启后将会激活一些不影响原版游戏的额外功能
4. 修复了/menu命令的一些问题：但好像并没有完全修好
5. 在线时间奖励的经典生存硬币数量由25提高至50
6. 修正“额外功能”按钮的文本错误
7. 死亡不掉落机制现在由另一个程序控制
8. 在设置菜单中增加了“死亡不掉落”的修改按钮，可以选择是否开启死亡不掉落：默认开启，想要增加难度的话可以修改它～

### 2022-3-11
1. 更新了部分死亡消息p4：基本上已经完成，如果大家对消息内容有什么建议的话欢迎提出～
2. 调整了一部分的文本信息
3. 菜单中的“硬币兑换”和“硬币商店”已基本可用
4. 现在硬币商店中可以购买区块加载器：半径2区块持续5小时，小规模测试一下，更多内容后续扩充

### 2022-3-15
1. 【反恶意破坏】程序更新：修复了一些错误，对记录的覆盖面更加广泛，改进了回滚和查找的性能
2. 非玩家箭矢的消失时间调整：20->60（3秒）
3. 玩家箭矢的消失时间调整：20->1200（20秒，默认值）：黄桑桑的抱怨～

### 2022-3-16
1. 修正死亡信息：“在战斗时 XXX” 为 “在与 XXX 战斗时”
2. 服务端主程序更新：
  1. 游戏版本更新：1.18.1->1.18.2
  2. 修复当视距设置为32时，实际并达不到32的问题
  3. 临时修复关于【反透视】的一些问题
  4. 修复关服保存时的一些问题
  5. 修复大量其他问题

### 2022-3-17
1. 死亡消息改进：对两个需要改进的消息添加了标记，便于玩家反馈
2. 死亡消息更新：增加了 被僵尸村民击杀时的新提示[3条]，被幻翼击杀时的新提示[1条]，被僵尸击杀时的新提示[2条]，被恶魂击杀时的新提示[1条]，被烈焰人击杀时的新提示[1条]，被凋零击杀时的新提示[1条]，被铁傀儡击杀时的新提示[1条]
3. 对“挂机”进行调整，取消了基于原版的挂机检测（即无行动30分钟后踢出服务器），现在挂机不会踢出玩家，但会停止计算游戏时长，同时，进入AFK状态后，将不会被推动。
4. [数据删除]

### 2022-3-18
1. 反作弊系统更新
2. 权限组系统更新[tagV5410]:必要的组件更新；这是一个统一更新，对所有正在运行的服务端都会更改
3. 基础核心组件更新[tagV9131]：必要的组件更新
  1. 修复了被甜浆果丛戳死时丢失的死亡信息
  2. 添加了AFK时间和AFK原因
  3. 修复了大量错误
  4. 支持1.18.2
  5. 修复死于熔岩时的死亡信息
4. 基础核心支持库更新[tagV1123]：必要的组件更新
5. 多语言翻译系统[tagV372]更新
6. 修复一个导致主线程卡死的问题：[数据删除]



## 4月