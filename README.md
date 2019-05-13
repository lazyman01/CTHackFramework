<h1>CTHackFramework 通用外挂框架</h1>

<h2>概述</h2>
    <p>
        &emsp;CTHackFramework是一个基于C++的通用外挂框架，可用于制作游戏外挂、修改器，软件破解机、注册机等程序。
    </p>
    <p>
        &emsp;该框架下包含了大量用于游戏外挂制作的类，函数与工具包，以供支持游戏外挂的快速开发。同时包含了一套外挂
        的软件架构，使该框架下的外挂具有稳定，高效的特性，同时使得外挂的扩展性与兼容性得以保证。
    </p>
        
<h2>框架结构</h2>
	<p>&emsp;框架的结构图如下。</p>
        <img src="https://github.com/CelestialTS/CTHackFramework/blob/master/res/arch.png" alt="Arch">
    <p>
        &emsp;<b>Memory</b>为内存模块，包含各类对目标进程的内存进行读取，写入，扫描等函数，负责对目标进程的内存进行操作。
    </p>
    <p>
        &emsp;<b>Process</b>为进程模块，包含对进程信息的获取与各类对进程的相关操作函数，如获取进程pid，句柄，查询
        进程加载的模块信息，进程的内存信息等等。并且包含一组封装好的进程内存数据读取函数，可以从目标进程中读取各种宽
        度的整形，浮点，布尔值等，同时也可以直接读取一段字节。反之，也可写入数据。
    </p>
    <p>
        &emsp;<b></b>
    </p>
    <p>
        &emsp;整个架构的核心是<b>Manager</b>，其负责整个架构的运转，其职能主要是：
        <ul>
            <li>与Process交互，对目标进程执行各项任务。</li>
            <li>将读取到的数据等存储进GameData中。</li>
        </ul>
    </p>
<h2>特性</h2>
<h2>使用方法</h2>
<h2>示例工程</h2>
    <p>Counter-Strike: Global Offensive 外挂: <a href="https://github.com/CelestialTS/CSGO">CSGO External Hack</a></p>
    <p>主要功能：ESP透视（DirectX Overlay）,Glow透视,雷达显人，bHop，自动扳机，自动压枪，自瞄等</p>
<h2>声明</h2>
    <p>
        <ul>
            <li>本程序仅为通用框架并非完整的具有功能的外挂，需要在该框架的基础上进行二次开发从而实现特定的功能。</li>
            <li>本程序作为外挂框架，并未将防检测纳入考量，请勿在受反外挂程序保护的服务器上使用。</li>
            <li>本程序作为游戏外挂使用时，仅限单机游戏使用，请勿在多人游戏中作弊。</li>
            <li>本程序作为其他用途时，请勿用于破坏网络安全，盗取个人信息等用途，产生的一切后果与本程序无关。</li>
            <li>本程序仅限交流学习使用，请勿用于商业活动，转载或使用代码，请注明出处。</li>
        </ul>  
    </p>
<h2>关于</h2>
    <img src="https://github.com/CelestialTS/CTHackFramework/blob/master/res/logo.png" alt="Celestial Tech" width=400 height="=100">
    <p>更多详情请见天师苍邪科技官方网站: <a href="http://www.tianshicangxie.com">Celestial Tech</a></p>
    <p>Copyright © 2019 Celestial Tech</p>
