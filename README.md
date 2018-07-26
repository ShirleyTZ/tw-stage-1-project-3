# tw-stage-1-project-3
第一阶段第三题

### 需求
![](whack-a-mole.gif)

实现一个上图所示的"打地鼠"游戏. 


游戏初始界面，标题"WHACK-A-MOLE！"，旁边跟着分数框，得分为0，下面有6个洞，按钮显示"Start！"

点击Start按钮，按钮文字变为Replay，地鼠开始**一个接一个**地出洞，每个地鼠**随机选择地洞出来，停留时间也随机**，停留时间到达后地鼠入洞，下一个地鼠出洞，如此反复，直到设定的游戏时间到达为止，期间用户使用鼠标点击出洞的地鼠，得分增加1分。

游戏时间到达后，标题"WHACK-A-MOLE"变为"TIME UP！", 分数框显示总得分。

### 说明（必读）
- 游戏中的地鼠、地洞等图片都以给好，初始界面也以写好，你不需要关心显示，只需要**完成逻辑部分**即可。

- 根据所给提示不同，作业划分为**两个**难度，**你需要二选一完成**
    - game-normal.js（推荐），除了基本页面外没有任何逻辑提示
    - game-easy.js，所有逻辑框架都以写好，只需补充相应函数实现。如果你选择此版本，务必仔细阅读已给出的代码，所有实现都有可参照的写法，需要自己思考分析每个逻辑相似的地方

- 地鼠出洞使用js代码控制css实现，将元素的class设置为'up'，则为出来，remove掉'up',则为下去。你可以参考start按钮的动态效果部分代码实现该控制

