#声明

该游戏demo的美术资源绝大部分是取自目前已经上线的游戏[富饶之城](http://game.173zy.com/modules/pfweb/view.php?gameid=26).因而不便将该游戏demo上线展示.

#CityOfPomelo介绍

<img src="https://raw.githubusercontent.com/toppro/ImageRepo/master/Help.png"></img>

##登录界面

<img src="https://raw.githubusercontent.com/toppro/ImageRepo/master/Login.png"></img>
如上图所示, 输入用户名和密码之后就可以登录了. 如果该用户名未被注册则向服务器注册该用户名然后登录, 并以MD5加密的方式存储用户密码. 如果该用户名已被注册, 则校验密码, 如果校验通过则登录服务器. 进入房间列表界面.

##房间列表界面

<img src="https://raw.githubusercontent.com/toppro/ImageRepo/master/CreateRoom.png"></img>
如上图所示, 玩家可以创建房间并等待其他玩家进入一起游戏; 也可在创建房间时'人数'一栏填写'1', 则该房间只有1个真实玩家, 服务器会自动为该房间添加5个机器人与玩家一起游戏, 该模式主要是为了玩家能够快速地体验游戏.

##雇佣角色界面

<img src="https://raw.githubusercontent.com/toppro/ImageRepo/master/EmployRole.png"></img>
如上图所示, 每一轮游戏, 玩家都要重新雇佣角色为自己建设富饶的城市.

##建造房子界面

<img src="https://raw.githubusercontent.com/toppro/ImageRepo/master/ConstructBuilding.png"></img>
如上图所示, 玩家点击'设计图纸'中的其中一张后, 会弹出该图纸的详细信息. 再点击该图纸的名称, 如'庄园', 就可以建造这个房子了. 当然, 这需要玩家有足够的金币.

##暗杀和偷取技能

<img src="https://raw.githubusercontent.com/toppro/ImageRepo/master/SkillKillAndSteal.png"></img>
如上图所示, 如果玩家雇佣了'刺客'或者'盗贼', 则可以点击'人物技能'下面的'暗杀'或者'偷取'技能按钮使用该角色的特殊技能.

##换手牌技能

<img src="https://raw.githubusercontent.com/toppro/ImageRepo/master/ExchangeCardWithPlayer.png"></img>
如上图所示, 如果玩家雇佣了'魔术师', 则可以与其他玩家或者系统交换手牌. 当选择与其他玩家交换手牌后, 再点击对应玩家头像上的准星图标即可与该玩家交换手牌. 该技能在'魔术师'没有手牌时能发挥最大效果.

##摧毁技能

<img src="https://raw.githubusercontent.com/toppro/ImageRepo/master/Dismantle.png"></img>
如上图所示, 如果玩家雇佣了'军阀', 则可以点击'人物技能'下面的'摧毁'按钮, 然后再点击想要摧毁的房子图标, 然后点击'拆', 就可以摧毁这座房子了.  当然, 这需要玩家有足够的金币(摧毁房子的所需花费比建造它少一个金币).

##游戏结束界面

<img src="https://raw.githubusercontent.com/toppro/ImageRepo/master/GameOver.png"></img>
如上图所示, 每当一轮游戏结束后(皇后出场并行动后)则统计对战双方队伍所建造出的房子总数. 如果该房间中有机器人, 则只要某个队伍总共建造出8个房子则游戏宣告结束; 如果该房间中都是真实玩家, 则需要某个队伍总共建造出15个房子游戏才宣告结束. 当然, 这两个数值在服务器端都是可以修改的.

##CityOfPomelo 服务器代码结构图

<img src="https://raw.githubusercontent.com/toppro/ImageRepo/master/SvrStructure.png"></img>
