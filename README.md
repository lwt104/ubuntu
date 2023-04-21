# ubuntu
ubuntu 命令简化改写：source devel/setup.bash    sdb   alias sdb='source devel/setup.bash'
nx未联网时，时间不更新，每次需要同步时间。 使用ntpdate
解决问题时，更新思路比调参重要
可视化程序输出，用此反馈消息重重新设计或改正现有方法
利用脚本，和terminater中的 
import numpy  使用时np.pi
from numpy import pi  直接写pi
ubuntu不同版本换源不一样
开机自启动： 将需要启动的脚本路径写在 /etc/rc.loal中  chmod +x 脚本路径
terminate 分组 alt+a （all） alt+g（group） alt+o取消
ssh 切换成root用户   su -




#ros
launch中的group标签，可以给节点赋予命名空间，一般加/的表示全局空间
多机器人中，用tf_prefix来表征不同机器人的tf
use_sim_time：通常用于回放bag中，true表示用的是仿真时间
