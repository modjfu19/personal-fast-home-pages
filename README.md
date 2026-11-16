# personal-fast-home-pages
<!DOCTYPE html>
<html lang="zh-CN">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>我的个人主页</title>
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            font-family: "Microsoft YaHei", sans-serif;
        }
        body {
            background-color: #f4f7fa;
            color: #333;
            line-height: 1.6;
        }
        .container {
            max-width: 900px;
            margin: 0 auto;
            padding: 20px;
        }
        header {
            background: linear-gradient(135deg, #409eff, #66b1ff);
            color: white;
            text-align: center;
            padding: 60px 20px;
            border-radius: 16px;
            margin-bottom: 30px;
        }
        .avatar {
            width: 120px;
            height: 120px;
            border-radius: 50%;
            border: 4px solid #fff;
            object-fit: cover;
            margin-bottom: 16px;
        }
        header h1 {
            font-size: 28px;
            margin-bottom: 8px;
        }
        header p {
            opacity: 0.9;
            font-size: 16px;
        }
        section {
            background: #fff;
            padding: 30px;
            border-radius: 16px;
            margin-bottom: 24px;
            box-shadow: 0 2px 12px rgba(0,0,0,0.06);
        }
        section h2 {
            color: #409eff;
            margin-bottom: 16px;
            border-left: 4px solid #409eff;
            padding-left: 12px;
        }
        .skill-list {
            display: flex;
            flex-wrap: wrap;
            gap: 12px;
        }
        .skill-tag {
            background: #ecf5ff;
            color: #409eff;
            padding: 6px 14px;
            border-radius: 20px;
            font-size: 14px;
        }
        .project-item {
            padding: 16px 0;
            border-bottom: 1px solid #eee;
        }
        .project-item:last-child {
            border-bottom: none;
        }
        .project-item h3 {
            margin-bottom: 6px;
        }
        .contact a {
            color: #409eff;
            text-decoration: none;
        }
        .contact a:hover {
            text-decoration: underline;
        }
        footer {
            text-align: center;
            padding: 20px;
            color: #666;
            font-size: 14px;
        }
        @media (max-width: 600px) {
            header {
                padding: 40px 16px;
            }
            section {
                padding: 20px;
            }
        }
    </style>
</head>
<body>
    <div class="container">
        <header>
            <!-- 把 src 换成你的头像图片链接 -->
            <img class="avatar" src="https://api.dicebear.com/7.x/avataaars/svg?seed=user" alt="头像">
            <h1>你的名字</h1>
            <p>前端爱好者 / 开发者 / 热爱生活</p>
        </header>

        <section>
            <h2>关于我</h2>
            <p>
                你好！我是一名热爱编程的开发者，喜欢折腾前端、写代码、做小项目。
                乐于学习新技术，喜欢简洁优雅的设计，持续沉淀，持续输出。
            </p>
        </section>

        <section>
            <h2>技能</h2>
            <div class="skill-list">
                <span class="skill-tag">HTML</span>
                <span class="skill-tag">CSS</span>
                <span class="skill-tag">JavaScript</span>
                <span class="skill-tag">Vue</span>
                <span class="skill-tag">Python</span>
                <span class="skill-tag">Git</span>
            </div>
        </section>

        <section>
            <h2>项目作品</h2>
            <div class="project-item">
                <h3>项目一：简易个人主页</h3>
                <p>响应式个人介绍页面，纯HTML+CSS实现，简洁美观。</p>
            </div>
            <div class="project-item">
                <h3>项目二：待办清单</h3>
                <p>JS本地存储待办工具，支持新增、删除、标记完成。</p>
            </div>
        </section>

        <section class="contact">
            <h2>联系我</h2>
            <p>邮箱：example@email.com</p>
            <p>GitHub：<a href="https://github.com/" target="_blank">github.com/xxx</a></p>
        </section>

        <footer>
            © 2026 你的名字 | All Rights Reserved
        </footer>
    </div>
</body>
</html>
