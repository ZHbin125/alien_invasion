# alien_invasion
Alien Invasion (双发魔改版)

这是一个基于 Python 和 Pygame 开发的经典射击游戏《外星人入侵》。本项目在原作基础上进行了修改，增加了双发子弹机制和更快的游戏节奏。

🎮 游戏特色 (Features)

与原版相比，本版本包含以下独特修改：

🔥 双重火力 (Double Shot)：

飞船经过改装，现在每次射击会同时发射两枚子弹（左右各一枚），极大增强了火力覆盖范围。

⚡ 极速体验 (High Speed)：

子弹飞行速度大幅提升 (10.0)。

屏幕上允许同时存在的子弹数量增加至 30 发，支持高密度弹幕输出。

💀 硬核模式 (Hardcore Mode)：

生命值限制极为严苛，玩家只有 1 次机会。一旦飞船被击中或外星人入侵到底部，游戏立即结束。

🛠️ 环境要求 (Requirements)

Python 3.x

Pygame 库

🚀 安装与运行 (Installation & Usage)

克隆或下载本项目到本地。

安装依赖：
确保你已经安装了 pygame。如果未安装，请在终端/命令行运行：

pip install pygame


启动游戏：
在终端中运行主程序文件：

python alienInvasion.py


🕹️ 操作说明 (Controls)

⬅️ 左箭头 / ➡️ 右箭头：控制飞船左右移动。

␣ 空格键 (Space)：开火（发射双排子弹）。

Q 键：退出游戏。

📂 文件结构说明 (File Structure)

alienInvasion.py: 主程序入口，包含游戏主循环和事件处理逻辑。

settings.py: 配置文件，包含屏幕大小、飞船速度、子弹参数等设置。

ship.py: 定义飞船的行为和属性。

bullet.py: 定义子弹的行为（包含修改后的偏移逻辑）。

alien.py: 定义外星人的行为。

game_stats.py: 统计游戏信息（得分、等级、剩余飞船）。

scoreboard.py: 负责在屏幕上显示得分和等级。

⚠️ 注意事项

图片资源：请确保项目根目录下有一个名为 images 的文件夹，其中包含 ship.bmp 和 alien.bmp，否则游戏启动时会报错。

Based on the project from "Python Crash Course".
