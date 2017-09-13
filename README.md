# Light-it-up
Simple 2D game by Construct 2<br>

How to play: open index.html<br>

Core Gameplay: When player starts, the whole scene will be completely dark. Any time player collects a star, the scene will light up for 2 sec. Player score 1 point each time he collects a star.<br>

Gameplay Objects:<br>
Star: Can light up scene and score point<br>
Black Barrier: Block player's avater. When avater hits it, a 'Stuck' mark shows up to indicate.<br>
Heart: Appear every 5 sec. Add time limit to 5 sec if player collects one.<br>
Portal: Two-way portal that help player cross barrier instead of a detour.<br>

Suppliment Trick:<br>
1. Player can press 'L' to force lighting up for 2 sec, with maximum 3 times usage in a game.<br>
2. Avatar appear in the opposite direction of the scene if it goes cross the boundary.<br>

打开方式：使用Firefox浏览器打开index.html文件可以开始游戏<br>

核心玩法：当玩家开始移动角色后，场景会完全变黑。每当角色吃掉一个星星，可以使场景点亮两秒。玩家分数为在限定时间内吃掉的星星总数。<br>

要素讲解：<br>
星星：可以点亮屏幕2s，同时也是分值标准。<br>
心：每5s出现，保持存在2s。不会点亮屏幕，角色吃掉可以获得额外的5s奖励。<br>
黑色障碍物：角色不可跨越，当角色接触，接触位置会出现“stuck”的标志。<br>
传送门：每一对相同颜色的小圆点就是一个传送门，可以实现双向传送，缩短路程。<br>

补充规则：<br>
1、当玩家在场景变黑却无法想起星星位置的时候，可以按L键点亮场景2s。使用限制最大为3次，每十秒可以增加1次使用机会，使用次数以闪电图标在屏幕左上角显示。<br>
2、当角色走出场景，便会直接移动到场景的另一端（类似吃豆人）<br>
