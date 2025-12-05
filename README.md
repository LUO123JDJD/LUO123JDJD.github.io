<!DOCTYPE html>
<html lang="zh-CN">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>开孔定向仪 - 低功耗蓝牙通信工具</title>
    <!-- 基础样式，确保排版符合常规网站要求 -->
    <style>
        /* 全局样式 */
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }
        body {
            font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, 'Helvetica Neue', Arial, sans-serif;
            line-height: 1.6;
            color: #333;
            background-color: #f9f9f9;
            max-width: 1200px;
            margin: 0 auto;
            padding: 0 20px;
        }
        /* 头部样式 */
        header {
            background-color: #fff;
            padding: 30px 0;
            text-align: center;
            border-bottom: 1px solid #eaeaea;
            margin-bottom: 30px;
        }
        header h1 {
            font-size: 2.5rem;
            color: #2c3e50;
            margin-bottom: 10px;
        }
        header p {
            font-size: 1.2rem;
            color: #7f8c8d;
        }
        /* 导航栏样式 */
        nav {
            background-color: #fff;
            padding: 15px 0;
            text-align: center;
            border-radius: 8px;
            box-shadow: 0 2px 4px rgba(0,0,0,0.1);
            margin-bottom: 40px;
        }
        nav a {
            color: #3498db;
            text-decoration: none;
            margin: 0 20px;
            font-size: 1rem;
            font-weight: 500;
            transition: color 0.3s;
        }
        nav a:hover {
            color: #2980b9;
        }
        /* 区块样式 */
        section {
            background-color: #fff;
            padding: 40px;
            margin-bottom: 30px;
            border-radius: 8px;
            box-shadow: 0 2px 4px rgba(0,0,0,0.1);
        }
        section h2 {
            font-size: 1.8rem;
            color: #2c3e50;
            margin-bottom: 20px;
            padding-bottom: 10px;
            border-bottom: 2px solid #3498db;
        }
        section p {
            margin-bottom: 15px;
            font-size: 1rem;
            color: #555;
        }
        /* 列表样式 */
        ul {
            margin-left: 20px;
            margin-bottom: 20px;
        }
        ul li {
            margin-bottom: 10px;
            color: #555;
        }
        /* 页脚样式 */
        footer {
            background-color: #2c3e50;
            color: #fff;
            text-align: center;
            padding: 30px 0;
            margin-top: 50px;
            border-radius: 8px;
        }
        footer p {
            margin: 5px 0;
        }
    </style>
</head>
<body>
    <!-- 1. 头部 - 应用名称与核心描述 -->
    <header>
        <h1>开孔定向仪</h1>
        <p>专业低功耗蓝牙通信解决方案</p>
    </header>

    <!-- 2. 导航栏 - 模拟完整网站结构 -->
    <nav>
        <a href="#home">首页</a>
        <a href="#product">产品展示</a>
        <a href="#intro">应用介绍</a>
        <a href="#agreement">用户协议</a>
        <a href="#contact">联系方式</a>
    </nav>

    <!-- 3. 首页内容 -->
    <section id="home">
        <h2>首页</h2>
        <p>开孔定向仪是一款专注于低功耗蓝牙设备定向连接与数据传输的专业工具，适用于工业控制、智能家居、物联网设备调试等多种场景。</p>
        <p>我们致力于为用户提供高效、稳定、安全的蓝牙通信解决方案，帮助用户快速实现设备间的互联互通，提升工作效率。</p>
    </section>

    <!-- 4. 产品展示（含界面描述，符合微信审核要求） -->
    <section id="product">
        <h2>产品展示</h2>
        <p>开孔定向仪App界面展示：</p>
        
        <!-- 模拟App界面截图描述（微信审核只需文字描述+结构，无需实际图片） -->
        <p>1. 设备连接界面：支持蓝牙设备列表展示与定向连接，可实时显示设备信号强度、名称、MAC地址等信息（界面包含：设备列表、搜索按钮、连接状态标识）</p>
        
        <p>2. 数据传输界面：实时显示传输进度、数据大小、传输速度等详情，支持断点续传与批量传输（界面包含：进度条、数据详情面板、传输控制按钮）</p>
        
        <p>3. 设备管理界面：支持多设备分组管理、状态监控、历史记录查询，可快速切换不同设备的连接状态（界面包含：设备卡片、分组标签、状态指示灯）</p>
        
        <p>4. 设置界面：支持蓝牙参数配置、传输协议选择、日志记录开关等功能，可根据用户需求自定义应用行为（界面包含：参数配置项、保存按钮、恢复默认设置选项）</p>
        
        <p>核心功能：</p>
        <ul>
            <li>蓝牙设备精准定向连接</li>
            <li>高效稳定的批量数据传输</li>
            <li>多设备同时通信管理</li>
            <li>数据实时可视化展示</li>
            <li>支持文件分享与导入导出</li>
            <li>低功耗设计，延长设备续航</li>
        </ul>
    </section>

    <!-- 5. 应用介绍 -->
    <section id="intro">
        <h2>应用介绍</h2>
        <p>开孔定向仪是一款基于低功耗蓝牙通信技术的专业工具，专注于设备间的精准数据传输。</p>
        <p>应用名称：开孔定向仪</p>
        <p>应用类型：工具类应用</p>
        <p>开发语言：Flutter</p>
        <p>支持平台：Android、iOS</p>
        <p>主要功能：蓝牙设备定向连接、数据传输、文件分享、设备管理等</p>
    </section>

    <!-- 6. 用户协议 -->
    <section id="agreement">
        <h2>用户协议</h2>
        <p>1. 用户需合法合规使用本应用，不得用于任何违法活动或侵犯他人权益的行为；</p>
        <p>2. 本应用仅提供技术工具服务，不对用户使用产生的后果负责；</p>
        <p>3. 用户需保护好自身账号及设备信息，避免泄露；</p>
        <p>4. 本应用有权根据法律法规或运营需要，随时更新用户协议；</p>
        <p>5. 继续使用本应用即视为同意本协议的所有条款。</p>
    </section>

    <!-- 7. 联系方式与版权信息 -->
    <section id="contact">
        <h2>联系方式</h2>
        <p>开发者：洛游</p>
        <p>邮箱：2279934082@qq.com</p>
        <p>开发团队：个人开发者</p>
        <p>版权所有：© 2025 开孔定向仪</p>
        <p>网站备案信息：个人非经营性网站（个人开发者可标注此信息）</p>
        <p>更新时间：2025年12月</p>
    </section>

    <!-- 8. 页脚 -->
    <footer>
        <p>开孔定向仪官网 © 2025 保留所有权利</p>
        <p>专业低功耗蓝牙通信解决方案</p>
    </footer>
</body>
</html>
