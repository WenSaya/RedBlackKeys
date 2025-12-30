# RedBlackKeys
Project Introduction
RedBlackKeys is an Android-based instrument auxiliary tool for the game "Sky: Children of the Light". By parsing song JSON files and leveraging the Android Accessibility Service, it achieves high-precision automated performance. It supports multi-finger chords and provides a highly flexible UI calibration solution.
Key Features
3x5 Anchor Box Calibration: A semi-transparent red grid that supports free dragging and resizing, perfectly adapting to instrument key positions on various device models.
Multi-touch Chord Support: Optimized via GestureDescription to trigger multiple notes simultaneously, reproducing complex musical scores accurately.
Side Search Drawer: A hidden search bar on the right side supporting fuzzy matching of the Assets song library, allowing quick song switching without leaving the game.
High-Precision Playback Engine: Utilizes a virtual timeline alignment algorithm to ensure perfect rhythm synchronization after pause, resume, or reset operations.
Click-Through Mechanism: In locked mode, the anchor box becomes transparent to touches, ensuring it doesn't interfere with game visibility or manual play.
Usage Guide
Grant Permissions: Launch the app and grant "Display over other apps (Overlay)" and "Accessibility Service" permissions.
Accept Terms: Read and agree to the "Terms of Use" upon first run.
Align Keys:
Enter the game and open the instrument interface.
Use the Move Icon on the floating console to reposition the panel.
Use the Resize Icon to adjust the red grid so that its 15 cells precisely cover the 15 keys in the game.
Select & Play:
Click the Small Handle on the right edge of the screen to expand the search drawer.
Enter keywords and click a song to load it.
Click the Play Button on the main console to start the performance.
<a name="chinese"></a>
项目简介
RedBlackKeys 是一款专为游戏《光遇》（Sky: Children of the Light）设计的安卓端乐器辅助演奏工具。通过解析乐谱 JSON 文件，利用安卓无障碍服务（Accessibility Service）实现高精度的自动点击，支持多指和弦演奏，并提供高度自由的 UI 校准方案。
核心功能
3x5 锚框校准：内置半透明红框网格，支持自由拖动与缩放，完美适配不同机型的琴键位置。
多指和弦支持：基于 GestureDescription 优化，可同时触发多个音符，还原真实复杂的乐谱。
侧边搜索抽屉：右侧隐藏式搜索栏，支持 Assets 曲库模糊匹配，无需切出游戏即可快速换歌。
高精度播放引擎：采用虚拟时间轴对齐算法，确保暂停、继续、重置操作后的音律准确无误。
点击穿透机制：在锁定模式下，锚框对触摸透明，不干扰游戏本身的视线与操作。
使用指南
权限授予：启动应用后，请依次授予“显示在其他应用上（悬浮窗）”权限和“无障碍服务”权限。
协议确认：首次运行需阅读并同意《服务条款》。
对齐琴键：
进入游戏并打开乐器界面。
使用悬浮窗中的 移动图标 挪动面板。
使用 缩放图标 调整红色网格，使其 15 个格子精准覆盖游戏中的 15 个按键。
选曲与播放：
点击屏幕右边缘的 小手柄 展开搜索抽屉。
输入关键词并点击曲目加载。
点击主面板的 播放按钮 开始演奏。
开发环境
语言：Java
平台：Android (支持 API 24+，建议使用物理机以获得最佳精度)
技术栈：WindowManager, AccessibilityService, JSON, TreeMap, SharedPreferences.
