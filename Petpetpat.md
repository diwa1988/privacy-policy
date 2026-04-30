<!DOCTYPE html>
<html lang="zh-CN">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Privacy Policy - Pet Woodfish</title>
    <style>
        :root {
            --primary-color: #2563eb;
            --text-color: #1f2937;
            --bg-color: #f9fafb;
            --card-bg: #ffffff;
        }
        body {
            font-family: -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, Helvetica, Arial, sans-serif;
            line-height: 1.6;
            color: var(--text-color);
            background-color: var(--bg-color);
            margin: 0;
            padding: 0;
        }
        .container {
            max-width: 800px;
            margin: 40px auto;
            padding: 40px;
            background: var(--card-bg);
            border-radius: 12px;
            box-shadow: 0 4px 6px -1px rgba(0, 0, 0, 0.1);
        }
        .lang-switch {
            position: sticky;
            top: 20px;
            display: flex;
            justify-content: flex-end;
            margin-bottom: 20px;
        }
        button {
            background-color: var(--primary-color);
            color: white;
            border: none;
            padding: 8px 16px;
            border-radius: 6px;
            cursor: pointer;
            font-weight: 600;
            transition: opacity 0.2s;
        }
        button:hover {
            opacity: 0.9;
        }
        h1 { border-bottom: 2px solid #eee; padding-bottom: 10px; color: #111; }
        h2 { margin-top: 30px; color: var(--primary-color); }
        .section { margin-bottom: 25px; }
        .email { font-weight: bold; color: var(--primary-color); }
        footer {
            text-align: center;
            margin-top: 40px;
            font-size: 0.9em;
            color: #6b7280;
        }
        /* 默认显示中文，隐藏英文 */
        [lang="en"] { display: none; }
        
        @media (max-width: 600px) {
            .container { margin: 10px; padding: 20px; }
        }
    </style>
</head>
<body>

<div class="container">
    <div class="lang-switch">
        <button onclick="toggleLang()">Switch to English / 切换语言</button>
    </div>

    <!-- 中文内容 -->
    <div id="content-zh" lang="zh">
        <h1>隐私政策</h1>
        <p><strong>最后更新日期：</strong> 2026年4月30日</p>
        
        <div class="section">
            <h2>1. 概述</h2>
            <p>本隐私政策旨在告知您，由我们（以下简称“开发团队”）开发的移动应用（以下简称“本应用”）在处理个人数据方面的政策。本应用是一款纯本地运行的木鱼互动工具。</p>
        </div>

        <div class="section">
            <h2>2. 信息收集与使用</h2>
            <p><strong>本应用不收集任何个人信息。</strong></p>
            <p>我们不会要求用户注册账号，也不会请求访问您的通讯录、精确地理位置、短信或任何其他敏感隐私权限。由于本应用完全在本地运行，没有任何服务器端功能，因此您的任何操作数据都不会被上传至云端。</p>
        </div>

        <div class="section">
            <h2>3. 数据保留政策 (重点)</h2>
            <p>由于我们不收集任何个人数据，因此在我们的服务器上不存在任何数据存储或保留：</p>
            <ul>
                <li><strong>本地数据：</strong> 本应用产生的任何交互数据（如点击统计、宠物状态）仅存储在您设备的受保护本地存储空间内。</li>
                <li><strong>保留时长：</strong> 只要应用安装在您的设备上，这些本地数据就会一直保留。我们无法从远程访问、备份或恢复这些数据。</li>
            </ul>
        </div>

        <div class="section">
            <h2>4. 数据删除政策 (重点)</h2>
            <p>您对自己的数据拥有完全的控制权：</p>
            <ul>
                <li><strong>卸载删除：</strong> 当您从设备中卸载本应用时，Android 系统会自动删除该应用本地存储文件夹中的所有相关数据。</li>
                <li><strong>手动清除：</strong> 您可以随时通过设备的“设置”->“应用管理”->“清除数据”来清空本应用的所有本地记录。</li>
            </ul>
        </div>

        <div class="section">
            <h2>5. 儿童隐私</h2>
            <p>本应用适合全年龄段使用。由于我们不收集任何个人信息，因此我们不会，也无法有意收集 13 岁以下儿童的任何个人数据。</p>
        </div>

        <div class="section">
            <h2>6. 联系我们</h2>
            <p>如果您对本政策有任何疑问，请通过以下电子邮件联系：</p>
            <p class="email">diwa49780@gamil.com</p>
        </div>
    </div>

    <!-- English Content -->
    <div id="content-en" lang="en">
        <h1>Privacy Policy</h1>
        <p><strong>Last Updated:</strong> April 30, 2026</p>
        
        <div class="section">
            <h2>1. Overview</h2>
            <p>This Privacy Policy is designed to inform you of our policies regarding the handling of personal data for the mobile application (hereinafter referred to as "the App") developed by our team. The App is a locally running interactive tool.</p>
        </div>

        <div class="section">
            <h2>2. Information Collection and Use</h2>
            <p><strong>The App does NOT collect any personal information.</strong></p>
            <p>We do not require users to register an account, nor do we request access to your contacts, precise location, SMS, or any other sensitive privacy permissions. Since the App operates entirely locally with no server-side functionality, none of your activity data is uploaded to the cloud.</p>
        </div>

        <div class="section">
            <h2>3. Data Retention Policy</h2>
            <p>Since we do not collect any personal data, no data storage or retention exists on our servers:</p>
            <ul>
                <li><strong>Local Data:</strong> Any interaction data generated by the App (e.g., tap statistics, pet status) is stored strictly within the protected local storage of your device.</li>
                <li><strong>Retention Period:</strong> This local data remains on your device as long as the App is installed. We cannot access, back up, or restore this data remotely.</li>
            </ul>
        </div>

        <div class="section">
            <h2>4. Data Deletion Policy</h2>
            <p>You have full control over your data:</p>
            <ul>
                <li><strong>Uninstallation:</strong> When you uninstall the App from your device, the Android system automatically deletes all associated data in the App's local storage folder.</li>
                <li><strong>Manual Clear:</strong> You can clear all local records of the App at any time via your device's "Settings" -> "Apps" -> "Clear Data".</li>
            </ul>
        </div>

        <div class="section">
            <h2>5. Children's Privacy</h2>
            <p>The App is suitable for all ages. Because we do not collect any personal information, we do not, and cannot, knowingly collect any personal data from children under the age of 13.</p>
        </div>

        <div class="section">
            <h2>6. Contact Us</h2>
            <p>If you have any questions regarding this policy, please contact us via email:</p>
            <p class="email">帝蛙9780@gamil.com</p>
        </div>
    </div>

    <footer>
        &copy; 2026 Pet Woodfish Team. All rights reserved.
    </footer>
</div>

<script>
    function toggleLang() {
        const zh = document.getElementById('content-zh');
        const en = document.getElementById('content-en');
        if (zh.style.display === 'none') {
            zh.style.display = 'block';
            en.style.display = 'none';
        } else {
            zh.style.display = 'none';
            en.style.display = 'block';
        }
    }
</script>

</body>
</html>
