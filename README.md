# 使用说明
此项目是一个基于canvas和原生js开发的游戏。整个文件夹直接下载下来即可运行，不需要安装任何插件。

你还可以[点这里去玩一下](http://luckykun.com/work/2016-05-30/tiny-heart-demo.html)

# 游戏规则
1. 大鱼跟着鼠标的位置移动而吃到果实，如吃到红色果实，身体变红，画布下方的个数加1；如吃到蓝色果实，身体变蓝，画布下方的倍数加1。
2. 画布右上角显示着小鱼的体力值，初始为10，身体为红色，随着时间的推移，体力值减小，身体颜色变淡。
3. 大鱼吃到果实之后可以喂小鱼，此时小鱼的体力值会根据大鱼果实的数量相应增加，画布上方的分值等于画布下方的倍数乘以个数的累加和。
4. 当小鱼体力值减到0时，游戏结束；点击画布，则可重新开始游戏。好了，拯救小鱼行动开始，躁起来吧！
