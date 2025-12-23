# 30天网页开发学习计划

## 学习路径概览

### 五个难度等级
- **入门级 (Day 1-5)**: HTML基础结构
- **初级 (Day 6-10)**: CSS样式与布局
- **中级 (Day 11-20)**: JavaScript交互编程
- **高级 (Day 21-25)**: 现代前端框架与技术
- **专家级 (Day 26-30)**: 综合项目实战

---

## 🌱 入门级 (Day 1-5) - HTML基础

### Day 1: 个人简介页面
**难度**: ⭐  
**知识点**: HTML基础标签、文本排版
**项目描述**: 创建一个简单的个人简介网页

**代码示例**:
```html
<!DOCTYPE html>
<html lang="zh-CN">
<head>
    <meta charset="UTF-8">
    <title>个人简介 - 你的名字</title>
</head>
<body>
    <h1>你好，我是[你的名字]</h1>
    <h2>关于我</h2>
    <p>我是一名前端开发学习者，热爱编程和设计。</p>
    
    <h3>技能</h3>
    <ul>
        <li>HTML</li>
        <li>CSS</li>
        <li>JavaScript</li>
    </ul>
    
    <h3>联系方式</h3>
    <p>邮箱: your@email.com</p>
</body>
</html>
```

**AI辅助学习**:
- 💡 提示词: "帮我检查这个HTML页面的语义化标签使用是否正确"
- 🔧 调试技巧: 使用浏览器开发者工具检查元素结构
- 📚 扩展阅读: 搜索"HTML语义化标签"

**每日挑战**: 添加一个你喜欢的名言或座右铭

---

### Day 2: 文章排版页面
**难度**: ⭐  
**知识点**: 标题层级、段落、列表、强调标签
**项目描述**: 创建一个美观的文章阅读页面

**代码示例**:
```html
<!DOCTYPE html>
<html lang="zh-CN">
<head>
    <meta charset="UTF-8">
    <title>学习心得分享</title>
</head>
<body>
    <article>
        <header>
            <h1>如何高效学习前端开发</h1>
            <p><time>2025-12-23</time> | 作者: 你的名字</p>
        </header>
        
        <section>
            <h2>学习路线图</h2>
            <p>前端开发学习可以分为<strong>三个核心阶段</strong>:</p>
            
            <ol>
                <li>
                    <h3>HTML结构</h3>
                    <p>掌握网页的<strong>骨架</strong>搭建</p>
                </li>
                <li>
                    <h3>CSS样式</h3>
                    <p>学习网页的<em>美化</em>技巧</p>
                </li>
                <li>
                    <h3>JavaScript交互</h3>
                    <p>实现网页的<u>动态</u>功能</p>
                </li>
            </ol>
        </section>
        
        <blockquote>
            <p>"Practice makes perfect - 熟能生巧"</p>
        </blockquote>
    </article>
</body>
</html>
```

**AI辅助学习**:
- 💡 提示词: "展示更多HTML文本格式化标签的用法"
- 🔧 调试技巧: 尝试不同的标题层级，观察视觉效果
- 📚 扩展阅读: 搜索"HTML5语义化标签详解"

**每日挑战**: 添加一个引用块(blockquote)和相关链接

---

### Day 3: 图片画廊
**难度**: ⭐⭐  
**知识点**: img标签、图片属性、基础布局
**项目描述**: 创建一个展示3-6张图片的画廊页面

**代码示例**:
```html
<!DOCTYPE html>
<html lang="zh-CN">
<head>
    <meta charset="UTF-8">
    <title>我的图片画廊</title>
</head>
<body>
    <h1>精选摄影作品</h1>
    
    <figure>
        <img src="https://picsum.photos/400/300?random=1" 
             alt="随机风景照片1"
             width="400" 
             height="300">
        <figcaption>风景摄影 - 山川湖泊</figcaption>
    </figure>
    
    <figure>
        <img src="https://picsum.photos/400/300?random=2" 
             alt="随机风景照片2"
             width="400" 
             height="300">
        <figcaption>城市风光 - 都市夜景</figcaption>
    </figure>
    
    <figure>
        <img src="https://picsum.photos/400/300?random=3" 
             alt="随机风景照片3"
             width="400" 
             height="300">
        <figcaption>自然之美 - 森林小径</figcaption>
    </figure>
    
    <!-- 添加更多图片... -->
</body>
</html>
```

**AI辅助学习**:
- 💡 提示词: "如何使用占位图片服务来测试网页设计？"
- 🔧 调试技巧: 尝试修改width和height属性，观察变化
- 📚 扩展阅读: 搜索"HTML图片优化技巧"

**每日挑战**: 为每张图片添加描述文字，并尝试使用figure和figcaption标签

---

### Day 4: 简单表单
**难度**: ⭐⭐  
**知识点**: 表单元素、输入框、按钮、标签
**项目描述**: 创建一个联系表单或调查问卷

**代码示例**:
```html
<!DOCTYPE html>
<html lang="zh-CN">
<head>
    <meta charset="UTF-8">
    <title>联系我们</title>
</head>
<body>
    <h1>联系我们</h1>
    
    <form action="#" method="post">
        <fieldset>
            <legend>个人信息</legend>
            
            <label for="name">姓名:</label>
            <input type="text" id="name" name="name" required>
            <br><br>
            
            <label for="email">邮箱:</label>
            <input type="email" id="email" name="email" required>
            <br><br>
            
            <label for="age">年龄:</label>
            <input type="number" id="age" name="age" min="1" max="120">
            <br><br>
            
            <label for="gender">性别:</label>
            <select id="gender" name="gender">
                <option value="">请选择</option>
                <option value="male">男</option>
                <option value="female">女</option>
                <option value="other">其他</option>
            </select>
        </fieldset>
        
        <fieldset>
            <legend>您的需求</legend>
            
            <label>感兴趣的主题:</label><br>
            <input type="checkbox" id="html" name="interests" value="html">
            <label for="html">HTML</label><br>
            
            <input type="checkbox" id="css" name="interests" value="css">
            <label for="css">CSS</label><br>
            
            <input type="checkbox" id="js" name="interests" value="js">
            <label for="js">JavaScript</label><br><br>
            
            <label for="message">留言:</label><br>
            <textarea id="message" name="message" rows="4" cols="50" 
                      placeholder="请在此输入您的留言..."></textarea>
        </fieldset>
        
        <button type="submit">提交表单</button>
        <button type="reset">重置</button>
    </form>
</body>
</html>
```

**AI辅助学习**:
- 💡 提示词: "HTML表单中各种input类型的用途和区别"
- 🔧 调试技巧: 尝试提交表单，观察浏览器如何验证必填字段
- 📚 扩展阅读: 搜索"HTML5表单新特性"

**每日挑战**: 添加更多表单字段，如电话号码、日期选择、颜色选择器等

---

### Day 5: 响应式基础
**难度**: ⭐⭐⭐  
**知识点**: meta viewport、CSS媒体查询基础、流式布局
**项目描述**: 创建一个在手机和电脑上都能良好显示的页面

**代码示例**:
```html
<!DOCTYPE html>
<html lang="zh-CN">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>响应式设计示例</title>
    <style>
        /* 基础样式 */
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }
        
        body {
            font-family: Arial, sans-serif;
            line-height: 1.6;
            padding: 20px;
        }
        
        .container {
            max-width: 1200px;
            margin: 0 auto;
        }
        
        .card {
            background: #f4f4f4;
            padding: 20px;
            margin-bottom: 20px;
            border-radius: 8px;
        }
        
        /* 响应式布局 */
        .grid {
            display: grid;
            grid-template-columns: 1fr;
            gap: 20px;
        }
        
        /* 平板设备 */
        @media (min-width: 768px) {
            .grid {
                grid-template-columns: repeat(2, 1fr);
            }
        }
        
        /* 桌面设备 */
        @media (min-width: 1024px) {
            .grid {
                grid-template-columns: repeat(3, 1fr);
            }
        }
    </style>
</head>
<body>
    <div class="container">
        <h1>响应式网格布局</h1>
        <p>调整浏览器窗口大小，观察卡片布局的变化！</p>
        
        <div class="grid">
            <div class="card">
                <h2>卡片 1</h2>
                <p>这是第一个卡片的内容。</p>
            </div>
            <div class="card">
                <h2>卡片 2</h2>
                <p>这是第二个卡片的内容。</p>
            </div>
            <div class="card">
                <h2>卡片 3</h2>
                <p>这是第三个卡片的内容。</p>
            </div>
            <div class="card">
                <h2>卡片 4</h2>
                <p>这是第四个卡片的内容。</p>
            </div>
            <div class="card">
                <h2>卡片 5</h2>
                <p>这是第五个卡片的内容。</p>
            </div>
            <div class="card">
                <h2>卡片 6</h2>
                <p>这是第六个卡片的内容。</p>
            </div>
        </div>
    </div>
</body>
</html>
```

**AI辅助学习**:
- 💡 提示词: "解释CSS媒体查询的工作原理和常见断点设置"
- 🔧 调试技巧: 使用浏览器开发者工具的"设备切换"功能测试响应式效果
- 📚 扩展阅读: 搜索"移动优先设计原则"

**每日挑战**: 尝试添加导航栏，并让它在手机上变成汉堡菜单

---

## 🌿 初级 (Day 6-10) - CSS进阶

### Day 6: 导航栏设计
**难度**: ⭐⭐⭐  
**知识点**: CSS选择器、Flexbox布局、伪类、过渡效果
**项目描述**: 创建一个美观的响应式导航栏

**代码示例**:
```html
<!DOCTYPE html>
<html lang="zh-CN">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>导航栏设计</title>
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }
        
        body {
            font-family: 'Arial', sans-serif;
            background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
            min-height: 100vh;
        }
        
        /* 导航栏样式 */
        nav {
            background: rgba(255, 255, 255, 0.95);
            padding: 1rem 2rem;
            box-shadow: 0 2px 10px rgba(0,0,0,0.1);
        }
        
        .nav-container {
            max-width: 1200px;
            margin: 0 auto;
            display: flex;
            justify-content: space-between;
            align-items: center;
        }
        
        .logo {
            font-size: 1.5rem;
            font-weight: bold;
            color: #667eea;
        }
        
        .nav-links {
            display: flex;
            list-style: none;
            gap: 2rem;
        }
        
        .nav-links a {
            text-decoration: none;
            color: #333;
            font-weight: 500;
            padding: 0.5rem 1rem;
            border-radius: 5px;
            transition: all 0.3s ease;
            position: relative;
        }
        
        .nav-links a:hover {
            background: #667eea;
            color: white;
            transform: translateY(-2px);
        }
        
        /* 活动状态 */
        .nav-links a.active {
            background: #667eea;
            color: white;
        }
        
        /* 响应式设计 */
        @media (max-width: 768px) {
            .nav-links {
                gap: 1rem;
            }
            
            .nav-links a {
                padding: 0.5rem;
                font-size: 0.9rem;
            }
        }
    </style>
</head>
<body>
    <nav>
        <div class="nav-container">
            <div class="logo">我的网站</div>
            <ul class="nav-links">
                <li><a href="#" class="active">首页</a></li>
                <li><a href="#">关于</a></li>
                <li><a href="#">服务</a></li>
                <li><a href="#">作品集</a></li>
                <li><a href="#">联系</a></li>
            </ul>
        </div>
    </nav>
    
    <main style="padding: 2rem; color: white; text-align: center;">
        <h1>欢迎来到我的网站</h1>
        <p>这是一个漂亮的导航栏示例</p>
    </main>
</body>
</html>
```

**AI辅助学习**:
- 💡 提示词: "解释CSS Flexbox布局的各种属性和使用场景"
- 🔧 调试技巧: 在浏览器中实时修改CSS属性，观察Flexbox布局的变化
- 📚 扩展阅读: 搜索"CSS Flexbox完全指南"

**每日挑战**: 添加下拉菜单或汉堡菜单（移动端）

---

### Day 7: 卡片组件设计
**难度**: ⭐⭐⭐  
**知识点**: CSS阴影、边框半径、悬停效果、内容组织
**项目描述**: 创建美观的卡片组件，可用于展示产品、文章等

**代码示例**:
```html
<!DOCTYPE html>
<html lang="zh-CN">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>卡片组件设计</title>
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }
        
        body {
            font-family: 'Arial', sans-serif;
            background: #f5f7fa;
            padding: 2rem;
            min-height: 100vh;
        }
        
        .container {
            max-width: 1200px;
            margin: 0 auto;
        }
        
        h1 {
            text-align: center;
            margin-bottom: 3rem;
            color: #2d3748;
        }
        
        .cards-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
            gap: 2rem;
        }
        
        .card {
            background: white;
            border-radius: 12px;
            overflow: hidden;
            box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
            transition: all 0.3s ease;
            cursor: pointer;
        }
        
        .card:hover {
            transform: translateY(-8px);
            box-shadow: 0 12px 25px rgba(0, 0, 0, 0.15);
        }
        
        .card-image {
            width: 100%;
            height: 200px;
            object-fit: cover;
        }
        
        .card-content {
            padding: 1.5rem;
        }
        
        .card-title {
            font-size: 1.25rem;
            font-weight: bold;
            margin-bottom: 0.5rem;
            color: #2d3748;
        }
        
        .card-description {
            color: #4a5568;
            line-height: 1.6;
            margin-bottom: 1rem;
        }
        
        .card-meta {
            display: flex;
            justify-content: space-between;
            align-items: center;
            font-size: 0.875rem;
            color: #718096;
        }
        
        .card-tag {
            background: #667eea;
            color: white;
            padding: 0.25rem 0.75rem;
            border-radius: 20px;
            font-size: 0.75rem;
        }
        
        .card-button {
            background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
            color: white;
            border: none;
            padding: 0.75rem 1.5rem;
            border-radius: 8px;
            font-weight: 500;
            cursor: pointer;
            transition: all 0.3s ease;
            width: 100%;
            margin-top: 1rem;
        }
        
        .card-button:hover {
            transform: translateY(-2px);
            box-shadow: 0 4px 12px rgba(102, 126, 234, 0.4);
        }
    </style>
</head>
<body>
    <div class="container">
        <h1>精选项目展示</h1>
        
        <div class="cards-grid">
            <div class="card">
                <img src="https://picsum.photos/400/200?random=1" alt="项目1" class="card-image">
                <div class="card-content">
                    <h3 class="card-title">电商网站</h3>
                    <p class="card-description">使用现代前端技术栈开发的响应式电商平台，支持购物车、支付等功能。</p>
                    <div class="card-meta">
                        <span class="card-tag">React</span>
                        <span>2025-12-23</span>
                    </div>
                    <button class="card-button">查看详情</button>
                </div>
            </div>
            
            <div class="card">
                <img src="https://picsum.photos/400/200?random=2" alt="项目2" class="card-image">
                <div class="card-content">
                    <h3 class="card-title">任务管理应用</h3>
                    <p class="card-description">简洁高效的任务管理工具，支持拖拽排序、标签分类、团队协作等功能。</p>
                    <div class="card-meta">
                        <span class="card-tag">Vue.js</span>
                        <span>2025-12-20</span>
                    </div>
                    <button class="card-button">查看详情</button>
                </div>
            </div>
            
            <div class="card">
                <img src="https://picsum.photos/400/200?random=3" alt="项目3" class="card-image">
                <div class="card-content">
                    <h3 class="card-title">数据可视化平台</h3>
                    <p class="card-description">基于ECharts的数据可视化解决方案，提供丰富的图表类型和交互功能。</p>
                    <div class="card-meta">
                        <span class="card-tag">JavaScript</span>
                        <span>2025-12-18</span>
                    </div>
                    <button class="card-button">查看详情</button>
                </div>
            </div>
        </div>
    </div>
</body>
</html>
```

**AI辅助学习**:
- 💡 提示词: "CSS Grid布局与Flexbox的区别和适用场景"
- 🔧 调试技巧: 使用浏览器开发者工具查看Grid布局的可视化效果
- 📚 扩展阅读: 搜索"CSS Grid完整教程"

**每日挑战**: 添加卡片翻转效果或图片放大效果

---

### Day 8: CSS动画效果
**难度**: ⭐⭐⭐⭐  
**知识点**: CSS过渡、关键帧动画、transform变换
**项目描述**: 创建各种CSS动画效果，让页面更生动

**代码示例**:
```html
<!DOCTYPE html>
<html lang="zh-CN">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>CSS动画效果合集</title>
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }
        
        body {
            font-family: 'Arial', sans-serif;
            background: #0f0c29;
            background: linear-gradient(to right, #24243f, #302b63, #0f0c29);
            color: white;
            padding: 2rem;
            min-height: 100vh;
        }
        
        .container {
            max-width: 1200px;
            margin: 0 auto;
        }
        
        h1 {
            text-align: center;
            margin-bottom: 3rem;
            font-size: 2.5rem;
        }
        
        .animations-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
            gap: 2rem;
        }
        
        .animation-demo {
            background: rgba(255, 255, 255, 0.1);
            border-radius: 12px;
            padding: 2rem;
            text-align: center;
            backdrop-filter: blur(10px);
            border: 1px solid rgba(255, 255, 255, 0.2);
        }
        
        /* 1. 脉冲动画 */
        .pulse {
            width: 100px;
            height: 100px;
            background: #ff6b6b;
            border-radius: 50%;
            margin: 1rem auto;
            animation: pulse 2s infinite;
        }
        
        @keyframes pulse {
            0% { transform: scale(1); opacity: 1; }
            50% { transform: scale(1.2); opacity: 0.7; }
            100% { transform: scale(1); opacity: 1; }
        }
        
        /* 2. 旋转动画 */
        .rotate {
            width: 100px;
            height: 100px;
            background: #4ecdc4;
            margin: 1rem auto;
            animation: rotate 3s linear infinite;
        }
        
        @keyframes rotate {
            from { transform: rotate(0deg); }
            to { transform: rotate(360deg); }
        }
        
        /* 3. 弹跳动画 */
        .bounce {
            width: 100px;
            height: 100px;
            background: #ffe66d;
            border-radius: 50%;
            margin: 1rem auto;
            animation: bounce 2s ease-in-out infinite;
        }
        
        @keyframes bounce {
            0%, 20%, 50%, 80%, 100% { transform: translateY(0); }
            40% { transform: translateY(-30px); }
            60% { transform: translateY(-15px); }
        }
        
        /* 4. 渐变动画 */
        .gradient {
            width: 100px;
            height: 100px;
            margin: 1rem auto;
            background: linear-gradient(45deg, #ff6b6b, #4ecdc4, #45b7d1, #96ceb4);
            background-size: 400% 400%;
            animation: gradient 3s ease infinite;
        }
        
        @keyframes gradient {
            0% { background-position: 0% 50%; }
            50% { background-position: 100% 50%; }
            100% { background-position: 0% 50%; }
        }
        
        /* 5. 打字机效果 */
        .typewriter {
            font-family: monospace;
            font-size: 1.2rem;
            margin: 1rem 0;
            white-space: nowrap;
            overflow: hidden;
            border-right: 3px solid #4ecdc4;
            animation: typing 3s steps(20) 1s forwards, blink 1s infinite;
            width: 0;
        }
        
        @keyframes typing {
            to { width: 20ch; }
        }
        
        @keyframes blink {
            50% { border-color: transparent; }
        }
        
        /* 6. 悬停3D效果 */
        .hover-3d {
            width: 100px;
            height: 100px;
            background: #667eea;
            margin: 1rem auto;
            transition: transform 0.3s ease;
        }
        
        .hover-3d:hover {
            transform: perspective(1000px) rotateX(45deg) rotateY(45deg) scale(1.2);
        }
        
        /* 7. 加载动画 */
        .loading {
            display: flex;
            justify-content: center;
            gap: 5px;
            margin: 1rem 0;
        }
        
        .loading-dot {
            width: 15px;
            height: 15px;
            background: #4ecdc4;
            border-radius: 50%;
            animation: loading 1.4s ease-in-out infinite both;
        }
        
        .loading-dot:nth-child(1) { animation-delay: -0.32s; }
        .loading-dot:nth-child(2) { animation-delay: -0.16s; }
        
        @keyframes loading {
            0%, 80%, 100% { transform: scale(0); }
            40% { transform: scale(1); }
        }
    </style>
</head>
<body>
    <div class="container">
        <h1>CSS动画效果合集</h1>
        
        <div class="animations-grid">
            <div class="animation-demo">
                <h3>脉冲效果</h3>
                <div class="pulse"></div>
                <p>呼吸式动画</p>
            </div>
            
            <div class="animation-demo">
                <h3>旋转效果</h3>
                <div class="rotate"></div>
                <p>持续旋转动画</p>
            </div>
            
            <div class="animation-demo">
                <h3>弹跳效果</h3>
                <div class="bounce"></div>
                <p>可爱的弹跳球</p>
            </div>
            
            <div class="animation-demo">
                <h3>渐变动画</h3>
                <div class="gradient"></div>
                <p>颜色流动效果</p>
            </div>
            
            <div class="animation-demo">
                <h3>打字机效果</h3>
                <div class="typewriter">Hello, World!</div>
                <p>文字逐字显示</p>
            </div>
            
            <div class="animation-demo">
                <h3>3D悬停效果</h3>
                <div class="hover-3d"></div>
                <p>鼠标悬停查看</p>
            </div>
            
            <div class="animation-demo">
                <h3>加载动画</h3>
                <div class="loading">
                    <div class="loading-dot"></div>
                    <div class="loading-dot"></div>
                    <div class="loading-dot"></div>
                </div>
                <p>页面加载提示</p>
            </div>
        </div>
    </div>
</body>
</html>
```

**AI辅助学习**:
- 💡 提示词: "CSS动画性能优化技巧，如何避免卡顿？"
- 🔧 调试技巧: 使用浏览器开发者工具的"Animations"面板调试动画
- 📚 扩展阅读: 搜索"CSS动画最佳实践"

**每日挑战**: 创建自己的组合动画，比如一个会弹跳并变色的球

---

### Day 9: 登录注册页面
**难度**: ⭐⭐⭐⭐  
**知识点**: 表单设计、CSS定位、背景效果、用户交互
**项目描述**: 创建一个美观的登录/注册切换页面

**代码示例**:
```html
<!DOCTYPE html>
<html lang="zh-CN">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>登录注册页面</title>
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }
        
        body {
            font-family: 'Arial', sans-serif;
            background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
            min-height: 100vh;
            display: flex;
            justify-content: center;
            align-items: center;
        }
        
        .container {
            background: white;
            border-radius: 20px;
            box-shadow: 0 15px 35px rgba(0, 0, 0, 0.2);
            overflow: hidden;
            width: 800px;
            max-width: 100%;
            min-height: 500px;
            position: relative;
        }
        
        .form-container {
            position: absolute;
            top: 0;
            height: 100%;
            transition: all 0.6s ease-in-out;
        }
        
        .sign-in-container {
            left: 0;
            width: 50%;
            z-index: 2;
        }
        
        .sign-up-container {
            left: 0;
            width: 50%;
            opacity: 0;
            z-index: 1;
        }
        
        .container.right-panel-active .sign-in-container {
            transform: translateX(100%);
        }
        
        .container.right-panel-active .sign-up-container {
            transform: translateX(100%);
            opacity: 1;
            z-index: 5;
            animation: show 0.6s;
        }
        
        @keyframes show {
            0%, 49.99% {
                opacity: 0;
                z-index: 1;
            }
            50%, 100% {
                opacity: 1;
                z-index: 5;
            }
        }
        
        form {
            background: white;
            display: flex;
            flex-direction: column;
            padding: 0 50px;
            height: 100%;
            justify-content: center;
            align-items: center;
            text-align: center;
        }
        
        h1 {
            color: #333;
            margin-bottom: 20px;
        }
        
        .social-container {
            margin: 20px 0;
        }
        
        .social-container a {
            border: 1px solid #ddd;
            border-radius: 50%;
            display: inline-flex;
            justify-content: center;
            align-items: center;
            margin: 0 5px;
            height: 40px;
            width: 40px;
            text-decoration: none;
            color: #333;
            transition: all 0.3s ease;
        }
        
        .social-container a:hover {
            background: #667eea;
            color: white;
            border-color: #667eea;
        }
        
        .form-input {
            background: #f4f4f4;
            border: none;
            padding: 12px 15px;
            margin: 8px 0;
            width: 100%;
            border-radius: 8px;
            font-size: 14px;
            transition: all 0.3s ease;
        }
        
        .form-input:focus {
            outline: none;
            background: #e8e8e8;
            transform: scale(1.02);
        }
        
        .form-button {
            background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
            border: none;
            border-radius: 25px;
            color: white;
            cursor: pointer;
            font-size: 14px;
            font-weight: bold;
            padding: 12px 45px;
            margin-top: 20px;
            text-transform: uppercase;
            transition: transform 80ms ease-in;
        }
        
        .form-button:hover {
            transform: scale(1.05);
        }
        
        .form-button:active {
            transform: scale(0.95);
        }
        
        .overlay-container {
            position: absolute;
            top: 0;
            left: 50%;
            width: 50%;
            height: 100%;
            overflow: hidden;
            transition: transform 0.6s ease-in-out;
            z-index: 100;
        }
        
        .container.right-panel-active .overlay-container {
            transform: translateX(-100%);
        }
        
        .overlay {
            background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
            color: white;
            position: relative;
            left: -100%;
            height: 100%;
            width: 200%;
            transform: translateX(0);
            transition: transform 0.6s ease-in-out;
        }
        
        .container.right-panel-active .overlay {
            transform: translateX(50%);
        }
        
        .overlay-panel {
            position: absolute;
            display: flex;
            align-items: center;
            justify-content: center;
            flex-direction: column;
            padding: 0 40px;
            text-align: center;
            top: 0;
            height: 100%;
            width: 50%;
            transform: translateX(0);
            transition: transform 0.6s ease-in-out;
        }
        
        .overlay-left {
            transform: translateX(-20%);
        }
        
        .container.right-panel-active .overlay-left {
            transform: translateX(0);
        }
        
        .overlay-right {
            right: 0;
            transform: translateX(0);
        }
        
        .container.right-panel-active .overlay-right {
            transform: translateX(20%);
        }
        
        .overlay-button {
            background: transparent;
            border: 1px solid white;
            color: white;
            cursor: pointer;
            font-size: 14px;
            font-weight: bold;
            padding: 12px 45px;
            margin-top: 20px;
            text-transform: uppercase;
            border-radius: 25px;
            transition: all 0.3s ease;
        }
        
        .overlay-button:hover {
            background: white;
            color: #667eea;
        }
        
        p {
            font-size: 14px;
            font-weight: 300;
            line-height: 20px;
            letter-spacing: 0.5px;
            margin: 20px 0 30px;
        }
    </style>
</head>
<body>
    <div class="container" id="container">
        <div class="form-container sign-up-container">
            <form action="#">
                <h1>创建账户</h1>
                <div class="social-container">
                    <a href="#">f</a>
                    <a href="#">g</a>
                    <a href="#">in</a>
                </div>
                <span>或使用邮箱注册</span>
                <input type="text" class="form-input" placeholder="用户名" required>
                <input type="email" class="form-input" placeholder="邮箱" required>
                <input type="password" class="form-input" placeholder="密码" required>
                <button class="form-button">注册</button>
            </form>
        </div>
        
        <div class="form-container sign-in-container">
            <form action="#">
                <h1>登录</h1>
                <div class="social-container">
                    <a href="#">f</a>
                    <a href="#">g</a>
                    <a href="#">in</a>
                </div>
                <span>或使用邮箱登录</span>
                <input type="email" class="form-input" placeholder="邮箱" required>
                <input type="password" class="form-input" placeholder="密码" required>
                <a href="#" style="color: #333; text-decoration: none; margin: 15px 0;">忘记密码？</a>
                <button class="form-button">登录</button>
            </form>
        </div>
        
        <div class="overlay-container">
            <div class="overlay">
                <div class="overlay-panel overlay-left">
                    <h1>已有账户？</h1>
                    <p>立即登录，继续您的学习之旅</p>
                    <button class="overlay-button" id="signIn">登录</button>
                </div>
                
                <div class="overlay-panel overlay-right">
                    <h1>新用户？</h1>
                    <p>注册账户，开启网页开发学习之旅</p>
                    <button class="overlay-button" id="signUp">注册</button>
                </div>
            </div>
        </div>
    </div>
    
    <script>
        const signUpButton = document.getElementById('signUp');
        const signInButton = document.getElementById('signIn');
        const container = document.getElementById('container');
        
        signUpButton.addEventListener('click', () => {
            container.classList.add('right-panel-active');
        });
        
        signInButton.addEventListener('click', () => {
            container.classList.remove('right-panel-active');
        });
    </script>
</body>
</html>
```

**AI辅助学习**:
- 💡 提示词: "如何设计用户友好的表单界面？有哪些最佳实践？"
- 🔧 调试技巧: 测试表单验证功能，观察不同输入类型的浏览器默认行为
- 📚 扩展阅读: 搜索"现代表单设计原则"

**每日挑战**: 添加表单验证功能，显示错误提示信息

---

### Day 10: 响应式个人简历
**难度**: ⭐⭐⭐⭐  
**知识点**: 综合应用HTML/CSS、响应式设计、布局技巧
**项目描述**: 创建一个专业的个人简历网页

**代码示例**:
```html
<!DOCTYPE html>
<html lang="zh-CN">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>个人简历 - 你的名字</title>
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }
        
        body {
            font-family: 'Arial', sans-serif;
            background: #f8f9fa;
            color: #2d3748;
            line-height: 1.6;
        }
        
        .container {
            max-width: 1000px;
            margin: 0 auto;
            padding: 20px;
        }
        
        /* 头部区域 */
        .header {
            background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
            color: white;
            padding: 3rem 2rem;
            text-align: center;
            border-radius: 15px;
            margin-bottom: 2rem;
            box-shadow: 0 10px 30px rgba(0,0,0,0.1);
        }
        
        .profile-image {
            width: 150px;
            height: 150px;
            border-radius: 50%;
            border: 5px solid white;
            margin-bottom: 1rem;
            object-fit: cover;
        }
        
        .name {
            font-size: 2.5rem;
            margin-bottom: 0.5rem;
        }
        
        .title {
            font-size: 1.2rem;
            opacity: 0.9;
            margin-bottom: 1rem;
        }
        
        .contact-info {
            display: flex;
            justify-content: center;
            gap: 2rem;
            flex-wrap: wrap;
        }
        
        .contact-item {
            display: flex;
            align-items: center;
            gap: 0.5rem;
        }
        
        /* 主要内容区域 */
        .main-content {
            display: grid;
            grid-template-columns: 1fr 2fr;
            gap: 2rem;
        }
        
        .sidebar {
            background: white;
            padding: 2rem;
            border-radius: 15px;
            box-shadow: 0 5px 15px rgba(0,0,0,0.08);
            height: fit-content;
        }
        
        .content {
            background: white;
            padding: 2rem;
            border-radius: 15px;
            box-shadow: 0 5px 15px rgba(0,0,0,0.08);
        }
        
        .section {
            margin-bottom: 2rem;
        }
        
        .section-title {
            font-size: 1.5rem;
            color: #667eea;
            margin-bottom: 1rem;
            padding-bottom: 0.5rem;
            border-bottom: 2px solid #667eea;
        }
        
        /* 技能条 */
        .skill-item {
            margin-bottom: 1rem;
        }
        
        .skill-name {
            display: flex;
            justify-content: space-between;
            margin-bottom: 0.5rem;
        }
        
        .skill-bar {
            background: #e2e8f0;
            height: 8px;
            border-radius: 4px;
            overflow: hidden;
        }
        
        .skill-progress {
            background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
            height: 100%;
            border-radius: 4px;
            transition: width 2s ease;
        }
        
        /* 工作经历和项目 */
        .timeline-item {
            position: relative;
            padding-left: 2rem;
            margin-bottom: 2rem;
            border-left: 2px solid #667eea;
        }
        
        .timeline-item::before {
            content: '';
            position: absolute;
            left: -6px;
            top: 0;
            width: 10px;
            height: 10px;
            background: #667eea;
            border-radius: 50%;
        }
        
        .timeline-date {
            color: #667eea;
            font-weight: bold;
            margin-bottom: 0.5rem;
        }
        
        .timeline-title {
            font-size: 1.1rem;
            font-weight: bold;
            margin-bottom: 0.5rem;
        }
        
        .timeline-company {
            color: #718096;
            margin-bottom: 0.5rem;
        }
        
        .timeline-description {
            color: #4a5568;
        }
        
        /* 响应式设计 */
        @media (max-width: 768px) {
            .main-content {
                grid-template-columns: 1fr;
            }
            
            .contact-info {
                flex-direction: column;
                gap: 1rem;
            }
            
            .name {
                font-size: 2rem;
            }
            
            .header {
                padding: 2rem 1rem;
            }
        }
        
        /* 动画效果 */
        .fade-in {
            animation: fadeIn 1s ease-in;
        }
        
        @keyframes fadeIn {
            from { opacity: 0; transform: translateY(20px); }
            to { opacity: 1; transform: translateY(0); }
        }
    </style>
</head>
<body>
    <div class="container">
        <!-- 头部区域 -->
        <header class="header fade-in">
            <img src="https://picsum.photos/150/150?random=1" alt="个人照片" class="profile-image">
            <h1 class="name">张三</h1>
            <p class="title">前端开发工程师</p>
            <div class="contact-info">
                <div class="contact-item">
                    <span>📧</span>
                    <span>zhangsan@email.com</span>
                </div>
                <div class="contact-item">
                    <span>📱</span>
                    <span>138-0000-0000</span>
                </div>
                <div class="contact-item">
                    <span>🌐</span>
                    <span>github.com/zhangsan</span>
                </div>
                <div class="contact-item">
                    <span>📍</span>
                    <span>北京市</span>
                </div>
            </div>
        </header>
        
        <!-- 主要内容区域 -->
        <div class="main-content">
            <!-- 侧边栏 -->
            <aside class="sidebar fade-in">
                <section class="section">
                    <h2 class="section-title">关于我</h2>
                    <p>热爱技术的前端开发工程师，具有3年Web开发经验。专注于现代前端技术栈，擅长React、Vue.js等框架，对用户体验有深刻理解。</p>
                </section>
                
                <section class="section">
                    <h2 class="section-title">技能</h2>
                    <div class="skill-item">
                        <div class="skill-name">
                            <span>HTML5 & CSS3</span>
                            <span>90%</span>
                        </div>
                        <div class="skill-bar">
                            <div class="skill-progress" style="width: 90%"></div>
                        </div>
                    </div>
                    
                    <div class="skill-item">
                        <div class="skill-name">
                            <span>JavaScript</span>
                            <span>85%</span>
                        </div>
                        <div class="skill-bar">
                            <div class="skill-progress" style="width: 85%"></div>
                        </div>
                    </div>
                    
                    <div class="skill-item">
                        <div class="skill-name">
                            <span>React</span>
                            <span>80%</span>
                        </div>
                        <div class="skill-bar">
                            <div class="skill-progress" style="width: 80%"></div>
                        </div>
                    </div>
                    
                    <div class="skill-item">
                        <div class="skill-name">
                            <span>Vue.js</span>
                            <span>75%</span>
                        </div>
                        <div class="skill-bar">
                            <div class="skill-progress" style="width: 75%"></div>
                        </div>
                    </div>
                    
                    <div class="skill-item">
                        <div class="skill-name">
                            <span>Node.js</span>
                            <span>70%</span>
                        </div>
                        <div class="skill-bar">
                            <div class="skill-progress" style="width: 70%"></div>
                        </div>
                    </div>
                </section>
                
                <section class="section">
                    <h2 class="section-title">教育背景</h2>
                    <div class="timeline-item">
                        <div class="timeline-date">2016 - 2020</div>
                        <div class="timeline-title">计算机科学与技术</div>
                        <div class="timeline-company">北京大学</div>
                        <div class="timeline-description">本科学历，主修计算机科学与技术，GPA: 3.8/4.0</div>
                    </div>
                </section>
            </aside>
            
            <!-- 主要内容 -->
            <main class="content fade-in">
                <section class="section">
                    <h2 class="section-title">工作经历</h2>
                    
                    <div class="timeline-item">
                        <div class="timeline-date">2022 - 至今</div>
                        <div class="timeline-title">高级前端开发工程师</div>
                        <div class="timeline-company">ABC科技有限公司</div>
                        <div class="timeline-description">
                            负责公司核心产品的前端架构设计和开发工作。带领团队完成了多个重要项目的技术选型
                            和开发工作。优化了项目构建流程，提升了30%的开发效率。
                        </div>
                    </div>
                    
                    <div class="timeline-item">
                        <div class="timeline-date">2020 - 2022</div>
                        <div class="timeline-title">前端开发工程师</div>
                        <div class="timeline-company">XYZ互联网公司</div>
                        <div class="timeline-description">
                            参与了多个大型Web应用的开发工作，积累了丰富的项目经验。负责前端组件库的建设和维护，
                            提高了团队的开发效率和代码质量。
                        </div>
                    </div>
                </section>
                
                <section class="section">
                    <h2 class="section-title">项目经验</h2>
                    
                    <div class="timeline-item">
                        <div class="timeline-date">2023</div>
                        <div class="timeline-title">企业级中后台管理系统</div>
                        <div class="timeline-company">技术负责人</div>
                        <div class="timeline-description">
                            使用React + TypeScript + Ant Design技术栈，开发了企业级中后台管理系统。
                            实现了权限管理、数据可视化、多语言支持等核心功能，获得了客户的高度评价。
                        </div>
                    </div>
                    
                    <div class="timeline-item">
                        <div class="timeline-date">2022</div>
                        <div class="timeline-title">移动端电商平台</div>
                        <div class="timeline-company">核心开发成员</div>
                        <div class="timeline-description">
                            使用Vue 3 + Vant开发移动端电商应用，实现了商品展示、购物车、订单管理等核心功能。
                            通过性能优化，首屏加载时间减少了40%。
                        </div>
                    </div>
                </section>
                
                <section class="section">
                    <h2 class="section-title">获奖证书</h2>
                    <ul style="list-style: none; padding-left: 0;">
                        <li style="margin-bottom: 0.5rem;">🏆 2023年度优秀员工</li>
                        <li style="margin-bottom: 0.5rem;">🥇 全栈开发工程师认证</li>
                        <li style="margin-bottom: 0.5rem;">🎓 前端架构师资格认证</li>
                    </ul>
                </section>
            </main>
        </div>
    </div>
    
    <script>
        // 页面加载时的动画效果
        document.addEventListener('DOMContentLoaded', function() {
            const skillBars = document.querySelectorAll('.skill-progress');
            
            // 技能条动画
            setTimeout(() => {
                skillBars.forEach(bar => {
                    const width = bar.style.width;
                    bar.style.width = '0%';
                    setTimeout(() => {
                        bar.style.width = width;
                    }, 100);
                });
            }, 500);
        });
    </script>
</body>
</html>
```

**AI辅助学习**:
- 💡 提示词: "如何优化个人简历网站的用户体验和视觉效果？"
- 🔧 调试技巧: 在不同设备上测试响应式效果，确保在各种屏幕尺寸下都美观
- 📚 扩展阅读: 搜索"个人品牌建设与在线简历设计"

**每日挑战**: 添加暗色主题切换功能，或者添加滚动动画效果

---

## 🌳 中级 (Day 11-20) - JavaScript基础

### Day 11: 简单计算器
**难度**: ⭐⭐⭐  
**知识点**: JavaScript基础语法、DOM操作、事件处理
**项目描述**: 创建一个可以进行基本数学运算的计算器

**代码示例**:
```html
<!DOCTYPE html>
<html lang="zh-CN">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>简单计算器</title>
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }
        
        body {
            font-family: 'Arial', sans-serif;
            background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
            min-height: 100vh;
            display: flex;
            justify-content: center;
            align-items: center;
        }
        
        .calculator {
            background: rgba(255, 255, 255, 0.1);
            backdrop-filter: blur(10px);
            border-radius: 20px;
            padding: 20px;
            box-shadow: 0 8px 32px rgba(0, 0, 0, 0.3);
            border: 1px solid rgba(255, 255, 255, 0.2);
        }
        
        .display {
            background: rgba(0, 0, 0, 0.3);
            color: white;
            font-size: 2rem;
            padding: 20px;
            text-align: right;
            margin-bottom: 20px;
            border-radius: 10px;
            min-height: 80px;
            word-wrap: break-word;
            overflow-wrap: break-word;
        }
        
        .buttons {
            display: grid;
            grid-template-columns: repeat(4, 1fr);
            gap: 10px;
        }
        
        button {
            background: rgba(255, 255, 255, 0.1);
            color: white;
            border: none;
            padding: 25px;
            font-size: 1.2rem;
            border-radius: 10px;
            cursor: pointer;
            transition: all 0.2s ease;
            border: 1px solid rgba(255, 255, 255, 0.1);
        }
        
        button:hover {
            background: rgba(255, 255, 255, 0.2);
            transform: scale(1.05);
        }
        
        button:active {
            transform: scale(0.95);
        }
        
        .operator {
            background: rgba(255, 149, 0, 0.3);
        }
        
        .operator:hover {
            background: rgba(255, 149, 0, 0.5);
        }
        
        .equals {
            background: rgba(76, 175, 80, 0.3);
            grid-column: span 2;
        }
        
        .equals:hover {
            background: rgba(76, 175, 80, 0.5);
        }
        
        .clear {
            background: rgba(244, 67, 54, 0.3);
        }
        
        .clear:hover {
            background: rgba(244, 67, 54, 0.5);
        }
        
        .zero {
            grid-column: span 2;
        }
    </style>
</head>
<body>
    <div class="calculator">
        <div class="display" id="display">0</div>
        <div class="buttons">
            <button class="clear" onclick="clearDisplay()">C</button>
            <button onclick="appendToDisplay('/')" class="operator">÷</button>
            <button onclick="appendToDisplay('*')" class="operator">×</button>
            <button onclick="deleteLast()">←</button>
            
            <button onclick="appendToDisplay('7')">7</button>
            <button onclick="appendToDisplay('8')">8</button>
            <button onclick="appendToDisplay('9')">9</button>
            <button onclick="appendToDisplay('-')" class="operator">-</button>
            
            <button onclick="appendToDisplay('4')">4</button>
            <button onclick="appendToDisplay('5')">5</button>
            <button onclick="appendToDisplay('6')">6</button>
            <button onclick="appendToDisplay('+')" class="operator">+</button>
            
            <button onclick="appendToDisplay('1')">1</button>
            <button onclick="appendToDisplay('2')">2</button>
            <button onclick="appendToDisplay('3')">3</button>
            <button onclick="appendToDisplay('.')">.</button>
            
            <button onclick="appendToDisplay('0')" class="zero">0</button>
            <button onclick="calculate()" class="equals">=</button>
        </div>
    </div>
    
    <script>
        let display = document.getElementById('display');
        let currentInput = '0';
        let shouldResetDisplay = false;
        
        function updateDisplay() {
            display.textContent = currentInput;
        }
        
        function appendToDisplay(value) {
            if (shouldResetDisplay) {
                currentInput = '0';
                shouldResetDisplay = false;
            }
            
            if (currentInput === '0' && value !== '.') {
                currentInput = value;
            } else {
                currentInput += value;
            }
            updateDisplay();
        }
        
        function clearDisplay() {
            currentInput = '0';
            updateDisplay();
        }
        
        function deleteLast() {
            if (currentInput.length > 1) {
                currentInput = currentInput.slice(0, -1);
            } else {
                currentInput = '0';
            }
            updateDisplay();
        }
        
        function calculate() {
            try {
                // 安全计算表达式
                const result = Function('"use strict"; return (' + currentInput + ')')();
                currentInput = result.toString();
                shouldResetDisplay = true;
                updateDisplay();
            } catch (error) {
                currentInput = 'Error';
                shouldResetDisplay = true;
                updateDisplay();
            }
        }
        
        // 键盘支持
        document.addEventListener('keydown', function(event) {
            if (event.key >= '0' && event.key <= '9' || event.key === '.') {
                appendToDisplay(event.key);
            } else if (event.key === '+' || event.key === '-' || event.key === '*' || event.key === '/') {
                appendToDisplay(event.key);
            } else if (event.key === 'Enter' || event.key === '=') {
                calculate();
            } else if (event.key === 'Escape' || event.key === 'c' || event.key === 'C') {
                clearDisplay();
            } else if (event.key === 'Backspace') {
                deleteLast();
            }
        });
    </script>
</body>
</html>
```

**AI辅助学习**:
- 💡 提示词: "JavaScript中如何安全地计算用户输入的数学表达式？"
- 🔧 调试技巧: 使用console.log()跟踪变量值的变化
- 📚 扩展阅读: 搜索"JavaScript DOM操作基础"

**每日挑战**: 添加更多功能，如百分比计算、平方根、记忆功能等

---

### Day 12: 待办事项列表 (Todo List)
**难度**: ⭐⭐⭐  
**知识点**: JavaScript数组操作、本地存储、动态创建元素
**项目描述**: 创建一个功能完整的待办事项管理应用

**代码示例**:
```html
<!DOCTYPE html>
<html lang="zh-CN">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>待办事项列表</title>
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }
        
        body {
            font-family: 'Arial', sans-serif;
            background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
            min-height: 100vh;
            padding: 2rem;
        }
        
        .container {
            max-width: 600px;
            margin: 0 auto;
            background: white;
            border-radius: 20px;
            padding: 2rem;
            box-shadow: 0 10px 30px rgba(0,0,0,0.2);
        }
        
        h1 {
            text-align: center;
            color: #333;
            margin-bottom: 2rem;
        }
        
        .input-section {
            display: flex;
            gap: 10px;
            margin-bottom: 2rem;
        }
        
        #todoInput {
            flex: 1;
            padding: 15px;
            border: 2px solid #e1e5e9;
            border-radius: 10px;
            font-size: 16px;
            transition: border-color 0.3s ease;
        }
        
        #todoInput:focus {
            outline: none;
            border-color: #667eea;
        }
        
        .add-btn {
            background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
            color: white;
            border: none;
            padding: 15px 25px;
            border-radius: 10px;
            cursor: pointer;
            font-size: 16px;
            transition: transform 0.2s ease;
        }
        
        .add-btn:hover {
            transform: scale(1.05);
        }
        
        .stats {
            display: flex;
            justify-content: space-between;
            margin-bottom: 1rem;
            padding: 15px;
            background: #f8f9fa;
            border-radius: 10px;
        }
        
        .stat-item {
            text-align: center;
        }
        
        .stat-number {
            font-size: 1.5rem;
            font-weight: bold;
            color: #667eea;
        }
        
        .stat-label {
            font-size: 0.9rem;
            color: #666;
        }
        
        .filter-buttons {
            display: flex;
            gap: 10px;
            margin-bottom: 1rem;
        }
        
        .filter-btn {
            flex: 1;
            padding: 10px;
            border: 2px solid #e1e5e9;
            background: white;
            border-radius: 8px;
            cursor: pointer;
            transition: all 0.3s ease;
        }
        
        .filter-btn.active {
            background: #667eea;
            color: white;
            border-color: #667eea;
        }
        
        .todo-list {
            list-style: none;
        }
        
        .todo-item {
            display: flex;
            align-items: center;
            padding: 15px;
            background: #f8f9fa;
            border-radius: 10px;
            margin-bottom: 10px;
            transition: all 0.3s ease;
        }
        
        .todo-item:hover {
            background: #e9ecef;
        }
        
        .todo-item.completed {
            opacity: 0.6;
        }
        
        .todo-item.completed .todo-text {
            text-decoration: line-through;
        }
        
        .todo-checkbox {
            width: 20px;
            height: 20px;
            margin-right: 15px;
            cursor: pointer;
        }
        
        .todo-text {
            flex: 1;
            font-size: 16px;
        }
        
        .todo-text.editing {
            background: white;
            border: 2px solid #667eea;
            padding: 5px;
            border-radius: 5px;
        }
        
        .todo-actions {
            display: flex;
            gap: 5px;
        }
        
        .action-btn {
            background: none;
            border: none;
            padding: 5px 10px;
            cursor: pointer;
            border-radius: 5px;
            transition: background 0.2s ease;
            font-size: 14px;
        }
        
        .edit-btn {
            color: #28a745;
        }
        
        .edit-btn:hover {
            background: #d4edda;
        }
        
        .delete-btn {
            color: #dc3545;
        }
        
        .delete-btn:hover {
            background: #f8d7da;
        }
        
        .clear-completed {
            background: #dc3545;
            color: white;
            border: none;
            padding: 10px 20px;
            border-radius: 8px;
            cursor: pointer;
            margin-top: 1rem;
            width: 100%;
            font-size: 16px;
        }
        
        .clear-completed:hover {
            background: #c82333;
        }
        
        .empty-state {
            text-align: center;
            padding: 40px;
            color: #666;
        }
        
        .empty-state img {
            width: 100px;
            opacity: 0.5;
            margin-bottom: 15px;
        }
    </style>
</head>
<body>
    <div class="container">
        <h1>📋 我的待办事项</h1>
        
        <div class="input-section">
            <input type="text" id="todoInput" placeholder="添加新的待办事项..." autocomplete="off">
            <button class="add-btn" onclick="addTodo()">添加</button>
        </div>
        
        <div class="stats">
            <div class="stat-item">
                <div class="stat-number" id="totalTasks">0</div>
                <div class="stat-label">总计</div>
            </div>
            <div class="stat-item">
                <div class="stat-number" id="activeTasks">0</div>
                <div class="stat-label">未完成</div>
            </div>
            <div class="stat-item">
                <div class="stat-number" id="completedTasks">0</div>
                <div class="stat-label">已完成</div>
            </div>
        </div>
        
        <div class="filter-buttons">
            <button class="filter-btn active" onclick="filterTodos('all')">全部</button>
            <button class="filter-btn" onclick="filterTodos('active')">未完成</button>
            <button class="filter-btn" onclick="filterTodos('completed')">已完成</button>
        </div>
        
        <ul class="todo-list" id="todoList">
            <!-- 待办事项将在这里动态生成 -->
        </ul>
        
        <button class="clear-completed" onclick="clearCompleted()">清除已完成</button>
    </div>
    
    <script>
        // 待办事项数组
        let todos = JSON.parse(localStorage.getItem('todos')) || [];
        let currentFilter = 'all';
        let editingId = null;
        
        // 添加待办事项
        function addTodo() {
            const input = document.getElementById('todoInput');
            const text = input.value.trim();
            
            if (text === '') {
                alert('请输入待办事项内容');
                return;
            }
            
            const todo = {
                id: Date.now(),
                text: text,
                completed: false,
                createdAt: new Date().toISOString()
            };
            
            todos.unshift(todo);
            input.value = '';
            saveTodos();
            renderTodos();
        }
        
        // 切换完成状态
        function toggleTodo(id) {
            const todo = todos.find(t => t.id === id);
            if (todo) {
                todo.completed = !todo.completed;
                saveTodos();
                renderTodos();
            }
        }
        
        // 删除待办事项
        function deleteTodo(id) {
            todos = todos.filter(t => t.id !== id);
            saveTodos();
            renderTodos();
        }
        
        // 开始编辑
        function editTodo(id) {
            editingId = id;
            renderTodos();
            
            // 聚焦到编辑输入框
            setTimeout(() => {
                const input = document.querySelector(`[data-id="${id}"] .edit-input`);
                if (input) {
                    input.focus();
                    input.select();
                }
            }, 100);
        }
        
        // 保存编辑
        function saveEdit(id, newText) {
            const todo = todos.find(t => t.id === id);
            if (todo && newText.trim() !== '') {
                todo.text = newText.trim();
                saveTodos();
            }
            editingId = null;
            renderTodos();
        }
        
        // 取消编辑
        function cancelEdit() {
            editingId = null;
            renderTodos();
        }
        
        // 清除已完成的待办事项
        function clearCompleted() {
            todos = todos.filter(t => !t.completed);
            saveTodos();
            renderTodos();
        }
        
        // 过滤待办事项
        function filterTodos(filter) {
            currentFilter = filter;
            
            // 更新按钮状态
            document.querySelectorAll('.filter-btn').forEach(btn => {
                btn.classList.remove('active');
            });
            event.target.classList.add('active');
            
            renderTodos();
        }
        
        // 保存到本地存储
        function saveTodos() {
            localStorage.setItem('todos', JSON.stringify(todos));
            updateStats();
        }
        
        // 更新统计信息
        function updateStats() {
            const total = todos.length;
            const completed = todos.filter(t => t.completed).length;
            const active = total - completed;
            
            document.getElementById('totalTasks').textContent = total;
            document.getElementById('activeTasks').textContent = active;
            document.getElementById('completedTasks').textContent = completed;
        }
        
        // 渲染待办事项列表
        function renderTodos() {
            const todoList = document.getElementById('todoList');
            
            // 过滤待办事项
            let filteredTodos = todos;
            if (currentFilter === 'active') {
                filteredTodos = todos.filter(t => !t.completed);
            } else if (currentFilter === 'completed') {
                filteredTodos = todos.filter(t => t.completed);
            }
            
            if (filteredTodos.length === 0) {
                todoList.innerHTML = `
                    <div class="empty-state">
                        <img src="https://cdn-icons-png.flaticon.com/512/2278/2278992.png" alt="空状态">
                        <p>暂无待办事项</p>
                    </div>
                `;
                return;
            }
            
            todoList.innerHTML = filteredTodos.map(todo => `
                <li class="todo-item ${todo.completed ? 'completed' : ''}" data-id="${todo.id}">
                    <input type="checkbox" class="todo-checkbox" 
                           ${todo.completed ? 'checked' : ''} 
                           onchange="toggleTodo(${todo.id})">
                    
                    ${editingId === todo.id ? 
                        `<input type="text" class="edit-input" value="${todo.text}" 
                                onblur="saveEdit(${todo.id}, this.value)"
                                onkeypress="if(event.key==='Enter') saveEdit(${todo.id}, this.value); if(event.key==='Escape') cancelEdit()">` :
                        `<span class="todo-text" ondblclick="editTodo(${todo.id})">${todo.text}</span>`
                    }
                    
                    <div class="todo-actions">
                        <button class="action-btn edit-btn" onclick="editTodo(${todo.id})">编辑</button>
                        <button class="action-btn delete-btn" onclick="deleteTodo(${todo.id})">删除</button>
                    </div>
                </li>
            `).join('');
        }
        
        // 回车键添加待办事项
        document.getElementById('todoInput').addEventListener('keypress', function(event) {
            if (event.key === 'Enter') {
                addTodo();
            }
        });
        
        // 页面加载时渲染待办事项
        document.addEventListener('DOMContentLoaded', function() {
            renderTodos();
            updateStats();
        });
    </script>
</body>
</html>
```

**AI辅助学习**:
- 💡 提示词: "JavaScript本地存储localStorage的使用方法和最佳实践"
- 🔧 调试技巧: 使用浏览器开发者工具的"Application"面板查看本地存储数据
- 📚 扩展阅读: 搜索"JavaScript数组方法详解"

**每日挑战**: 添加待办事项的拖拽排序功能，或者添加截止日期和优先级功能

---



### Day 17: 倒计时器
**难度**: ⭐⭐⭐  
**知识点**: JavaScript Date对象、setInterval、时间计算、DOM更新
**项目描述**: 创建一个多功能的倒计时器，支持自定义时间和多种显示样式

**代码示例**:
```html
<!DOCTYPE html>
<html lang="zh-CN">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>多功能倒计时器</title>
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }
        
        body {
            font-family: 'Arial', sans-serif;
            background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
            min-height: 100vh;
            padding: 2rem;
        }
        
        .container {
            max-width: 800px;
            margin: 0 auto;
        }
        
        .header {
            text-align: center;
            color: white;
            margin-bottom: 2rem;
        }
        
        .header h1 {
            font-size: 2.5rem;
            margin-bottom: 0.5rem;
        }
        
        .timer-setup {
            background: white;
            border-radius: 20px;
            padding: 2rem;
            margin-bottom: 2rem;
            box-shadow: 0 10px 30px rgba(0,0,0,0.1);
        }
        
        .preset-times {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(120px, 1fr));
            gap: 15px;
            margin-bottom: 2rem;
        }
        
        .preset-btn {
            background: #f8f9fa;
            border: 2px solid #e1e5e9;
            padding: 15px;
            border-radius: 10px;
            cursor: pointer;
            transition: all 0.3s ease;
            text-align: center;
        }
        
        .preset-btn:hover {
            border-color: #667eea;
            background: #f0f4ff;
        }
        
        .preset-btn.active {
            background: #667eea;
            color: white;
            border-color: #667eea;
        }
        
        .preset-time {
            font-size: 1.2rem;
            font-weight: bold;
            margin-bottom: 5px;
        }
        
        .preset-label {
            font-size: 0.9rem;
            color: #666;
        }
        
        .preset-btn.active .preset-label {
            color: rgba(255,255,255,0.8);
        }
        
        .custom-time {
            display: grid;
            grid-template-columns: repeat(3, 1fr);
            gap: 15px;
            margin-bottom: 2rem;
        }
        
        .time-input-group {
            text-align: center;
        }
        
        .time-input-group label {
            display: block;
            margin-bottom: 5px;
            color: #666;
            font-size: 0.9rem;
        }
        
        .time-input {
            width: 100%;
            padding: 15px;
            border: 2px solid #e1e5e9;
            border-radius: 10px;
            font-size: 1.5rem;
            text-align: center;
            transition: border-color 0.3s ease;
        }
        
        .time-input:focus {
            outline: none;
            border-color: #667eea;
        }
        
        .timer-display {
            background: white;
            border-radius: 20px;
            padding: 3rem 2rem;
            text-align: center;
            box-shadow: 0 10px 30px rgba(0,0,0,0.1);
            margin-bottom: 2rem;
        }
        
        .timer-circle {
            width: 250px;
            height: 250px;
            border-radius: 50%;
            background: conic-gradient(#667eea 0deg, #e1e5e9 0deg);
            display: flex;
            align-items: center;
            justify-content: center;
            margin: 0 auto 2rem;
            position: relative;
            transition: background 0.1s ease;
        }
        
        .timer-inner {
            width: 200px;
            height: 200px;
            background: white;
            border-radius: 50%;
            display: flex;
            flex-direction: column;
            align-items: center;
            justify-content: center;
            box-shadow: inset 0 5px 15px rgba(0,0,0,0.1);
        }
        
        .time-display {
            font-size: 3rem;
            font-weight: bold;
            color: #333;
            font-family: 'Courier New', monospace;
            margin-bottom: 10px;
        }
        
        .time-label {
            font-size: 0.9rem;
            color: #666;
        }
        
        .timer-message {
            font-size: 1.2rem;
            color: #666;
            margin-bottom: 1rem;
            min-height: 1.5rem;
        }
        
        .timer-controls {
            display: flex;
            justify-content: center;
            gap: 15px;
            flex-wrap: wrap;
        }
        
        .control-btn {
            background: #667eea;
            color: white;
            border: none;
            padding: 15px 30px;
            border-radius: 10px;
            cursor: pointer;
            font-size: 16px;
            transition: all 0.3s ease;
            min-width: 120px;
        }
        
        .control-btn:hover {
            background: #5a6fd8;
            transform: scale(1.05);
        }
        
        .control-btn:disabled {
            opacity: 0.6;
            cursor: not-allowed;
            transform: none;
        }
        
        .control-btn.secondary {
            background: #6c757d;
        }
        
        .control-btn.secondary:hover {
            background: #5a6268;
        }
        
        .control-btn.danger {
            background: #dc3545;
        }
        
        .control-btn.danger:hover {
            background: #c82333;
        }
        
        .timer-modes {
            background: white;
            border-radius: 20px;
            padding: 2rem;
            box-shadow: 0 10px 30px rgba(0,0,0,0.1);
        }
        
        .mode-tabs {
            display: flex;
            margin-bottom: 2rem;
            background: #f8f9fa;
            border-radius: 10px;
            padding: 5px;
        }
        
        .mode-tab {
            flex: 1;
            padding: 15px;
            text-align: center;
            border-radius: 8px;
            cursor: pointer;
            transition: all 0.3s ease;
            font-weight: 500;
        }
        
        .mode-tab.active {
            background: #667eea;
            color: white;
        }
        
        .mode-content {
            display: none;
        }
        
        .mode-content.active {
            display: block;
        }
        
        .alarm-settings {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(200px, 1fr));
            gap: 15px;
        }
        
        .alarm-option {
            display: flex;
            align-items: center;
            gap: 10px;
        }
        
        .alarm-option input[type="checkbox"] {
            width: 20px;
            height: 20px;
        }
        
        .sound-select {
            width: 100%;
            padding: 10px;
            border: 2px solid #e1e5e9;
            border-radius: 8px;
            font-size: 16px;
        }
        
        .volume-control {
            display: flex;
            align-items: center;
            gap: 15px;
        }
        
        .volume-slider {
            flex: 1;
            height: 6px;
            border-radius: 3px;
            background: #e1e5e9;
            outline: none;
            cursor: pointer;
        }
        
        /* 响应式设计 */
        @media (max-width: 768px) {
            .custom-time {
                grid-template-columns: 1fr;
            }
            
            .timer-circle {
                width: 200px;
                height: 200px;
            }
            
            .timer-inner {
                width: 160px;
                height: 160px;
            }
            
            .time-display {
                font-size: 2rem;
            }
            
            .timer-controls {
                flex-direction: column;
                align-items: center;
            }
            
            .control-btn {
                width: 200px;
            }
        }
    </style>
</head>
<body>
    <div class="container">
        <div class="header">
            <h1>⏰ 多功能倒计时器</h1>
            <p>专注计时，提高效率</p>
        </div>
        
        <div class="timer-setup">
            <h3 style="margin-bottom: 1rem; color: #333;">选择预设时间</h3>
            <div class="preset-times">
                <div class="preset-btn" onclick="selectPreset(5, '5分钟', this)">
                    <div class="preset-time">5</div>
                    <div class="preset-label">分钟</div>
                </div>
                <div class="preset-btn active" onclick="selectPreset(25, '番茄钟', this)">
                    <div class="preset-time">25</div>
                    <div class="preset-label">番茄钟</div>
                </div>
                <div class="preset-btn" onclick="selectPreset(30, '30分钟', this)">
                    <div class="preset-time">30</div>
                    <div class="preset-label">分钟</div>
                </div>
                <div class="preset-btn" onclick="selectPreset(60, '1小时', this)">
                    <div class="preset-time">60</div>
                    <div class="preset-label">小时</div>
                </div>
            </div>
            
            <h3 style="margin-bottom: 1rem; color: #333;">或自定义时间</h3>
            <div class="custom-time">
                <div class="time-input-group">
                    <label for="hours">小时</label>
                    <input type="number" id="hours" class="time-input" min="0" max="23" value="0" onchange="updateCustomTime()">
                </div>
                <div class="time-input-group">
                    <label for="minutes">分钟</label>
                    <input type="number" id="minutes" class="time-input" min="0" max="59" value="25" onchange="updateCustomTime()">
                </div>
                <div class="time-input-group">
                    <label for="seconds">秒</label>
                    <input type="number" id="seconds" class="time-input" min="0" max="59" value="0" onchange="updateCustomTime()">
                </div>
            </div>
        </div>
        
        <div class="timer-display">
            <div class="timer-circle" id="timerCircle">
                <div class="timer-inner">
                    <div class="time-display" id="timeDisplay">25:00</div>
                    <div class="time-label" id="timeLabel">番茄钟</div>
                </div>
            </div>
            
            <div class="timer-message" id="timerMessage">准备开始专注时间</div>
            
            <div class="timer-controls">
                <button class="control-btn" id="startBtn" onclick="startTimer()">开始</button>
                <button class="control-btn secondary" id="pauseBtn" onclick="pauseTimer()" disabled>暂停</button>
                <button class="control-btn secondary" id="resetBtn" onclick="resetTimer()">重置</button>
                <button class="control-btn danger" id="stopBtn" onclick="stopTimer()" disabled>停止</button>
            </div>
        </div>
        
        <div class="timer-modes">
            <div class="mode-tabs">
                <div class="mode-tab active" onclick="switchMode('alarm', this)">闹钟设置</div>
                <div class="mode-tab" onclick="switchMode('presets', this)">预设管理</div>
            </div>
            
            <div class="mode-content active" id="alarm-mode">
                <h4 style="margin-bottom: 1rem; color: #333;">提醒设置</h4>
                <div class="alarm-settings">
                    <div class="alarm-option">
                        <input type="checkbox" id="soundEnabled" checked>
                        <label for="soundEnabled">声音提醒</label>
                    </div>
                    <div class="alarm-option">
                        <label for="alarmSound">提醒音：</label>
                        <select class="sound-select" id="alarmSound">
                            <option value="bell">铃声</option>
                            <option value="beep">哔哔声</option>
                            <option value="chime">钟声</option>
                            <option value="alarm">闹钟声</option>
                        </select>
                    </div>
                    <div class="alarm-option">
                        <label for="volume">音量：</label>
                        <div class="volume-control">
                            <span>🔈</span>
                            <input type="range" class="volume-slider" id="volume" min="0" max="100" value="70">
                            <span>🔊</span>
                        </div>
                    </div>
                    <div class="alarm-option">
                        <input type="checkbox" id="vibrationEnabled">
                        <label for="vibrationEnabled">震动提醒（移动设备）</label>
                    </div>
                </div>
            </div>
            
            <div class="mode-content" id="presets-mode">
                <h4 style="margin-bottom: 1rem; color: #333;">预设时间管理</h4>
                <p style="color: #666;">这里可以添加自定义的预设时间，方便快速选择。</p>
            </div>
        </div>
    </div>
    
    <audio id="alarmAudio" preload="auto">
        <source src="data:audio/wav;base64,UklGRnoGAABXQVZFZm10IBAAAAABAAEAQB8AAEAfAAABAAgAZGF0YQoGAACBhYqFbF1fdJivrJBhNjVgodDbq2EcBj+a2/LDciUFLIHO8tiJNwgZaLvt559NEAxQp+PwtmMcBjiR1/LMeSwFJHfH8N2QQAoUXrTp66hVFApGn+DyvmwhBSuBzvLZiTYIG2m98OScTgwOUarm7blmFgU7k9n1unEiBC13yO/eizEIHWq+8+OWT" type="audio/wav">
    </audio>
    
    <script>
        let totalSeconds = 25 * 60; // 默认25分钟
        let remainingSeconds = totalSeconds;
        let timerInterval = null;
        let isRunning = false;
        let isPaused = false;
        
        // 更新显示
        function updateDisplay() {
            const hours = Math.floor(remainingSeconds / 3600);
            const minutes = Math.floor((remainingSeconds % 3600) / 60);
            const seconds = remainingSeconds % 60;
            
            let timeString = '';
            if (hours > 0) {
                timeString = `${hours}:${minutes.toString().padStart(2, '0')}:${seconds.toString().padStart(2, '0')}`;
            } else {
                timeString = `${minutes}:${seconds.toString().padStart(2, '0')}`;
            }
            
            document.getElementById('timeDisplay').textContent = timeString;
            
            // 更新圆形进度
            const progress = ((totalSeconds - remainingSeconds) / totalSeconds) * 360;
            document.getElementById('timerCircle').style.background = 
                `conic-gradient(#667eea ${progress}deg, #e1e5e9 ${progress}deg)`;
        }
        
        // 选择预设时间
        function selectPreset(minutes, label, element) {
            // 更新按钮状态
            document.querySelectorAll('.preset-btn').forEach(btn => btn.classList.remove('active'));
            element.classList.add('active');
            
            // 设置时间
            totalSeconds = minutes * 60;
            remainingSeconds = totalSeconds;
            
            // 更新输入框
            document.getElementById('hours').value = 0;
            document.getElementById('minutes').value = minutes;
            document.getElementById('seconds').value = 0;
            
            // 更新显示
            document.getElementById('timeLabel').textContent = label;
            updateDisplay();
            
            // 重置状态
            resetTimer();
        }
        
        // 更新自定义时间
        function updateCustomTime() {
            const hours = parseInt(document.getElementById('hours').value) || 0;
            const minutes = parseInt(document.getElementById('minutes').value) || 0;
            const seconds = parseInt(document.getElementById('seconds').value) || 0;
            
            totalSeconds = hours * 3600 + minutes * 60 + seconds;
            remainingSeconds = totalSeconds;
            
            // 取消预设按钮的选中状态
            document.querySelectorAll('.preset-btn').forEach(btn => btn.classList.remove('active'));
            
            // 更新显示
            document.getElementById('timeLabel').textContent = '自定义时间';
            updateDisplay();
            
            // 重置状态
            resetTimer();
        }
        
        // 开始计时
        function startTimer() {
            if (remainingSeconds <= 0) return;
            
            isRunning = true;
            isPaused = false;
            
            // 更新按钮状态
            document.getElementById('startBtn').disabled = true;
            document.getElementById('pauseBtn').disabled = false;
            document.getElementById('stopBtn').disabled = false;
            
            // 更新消息
            document.getElementById('timerMessage').textContent = '专注进行中...';
            
            // 开始倒计时
            timerInterval = setInterval(() => {
                remainingSeconds--;
                updateDisplay();
                
                if (remainingSeconds <= 0) {
                    timerComplete();
                }
            }, 1000);
        }
        
        // 暂停计时
        function pauseTimer() {
            if (!isRunning) return;
            
            isRunning = false;
            isPaused = true;
            
            clearInterval(timerInterval);
            
            // 更新按钮状态
            document.getElementById('startBtn').disabled = false;
            document.getElementById('pauseBtn').disabled = true;
            
            // 更新消息
            document.getElementById('timerMessage').textContent = '计时已暂停';
        }
        
        // 重置计时器
        function resetTimer() {
            isRunning = false;
            isPaused = false;
            
            clearInterval(timerInterval);
            remainingSeconds = totalSeconds;
            
            // 更新按钮状态
            document.getElementById('startBtn').disabled = false;
            document.getElementById('pauseBtn').disabled = true;
            document.getElementById('stopBtn').disabled = true;
            
            // 更新消息
            document.getElementById('timerMessage').textContent = '准备开始专注时间';
            
            updateDisplay();
        }
        
        // 停止计时器
        function stopTimer() {
            resetTimer();
        }
        
        // 计时完成
        function timerComplete() {
            isRunning = false;
            clearInterval(timerInterval);
            
            // 更新按钮状态
            document.getElementById('startBtn').disabled = false;
            document.getElementById('pauseBtn').disabled = true;
            document.getElementById('stopBtn').disabled = true;
            
            // 更新消息
            document.getElementById('timerMessage').textContent = '🎉 时间到！休息一下~';
            
            // 播放提醒音
            if (document.getElementById('soundEnabled').checked) {
                playAlarm();
            }
            
            // 震动提醒（如果支持）
            if (document.getElementById('vibrationEnabled').checked && navigator.vibrate) {
                navigator.vibrate([200, 100, 200, 100, 200]);
            }
            
            // 重置计时器
            setTimeout(() => {
                resetTimer();
            }, 3000);
        }
        
        // 播放提醒音
        function playAlarm() {
            const audio = document.getElementById('alarmAudio');
            const volume = document.getElementById('volume').value / 100;
            audio.volume = volume;
            audio.play().catch(e => {
                console.log('无法播放提醒音:', e);
            });
        }
        
        // 切换模式
        function switchMode(mode, element) {
            // 更新标签状态
            document.querySelectorAll('.mode-tab').forEach(tab => tab.classList.remove('active'));
            element.classList.add('active');
            
            // 更新内容显示
            document.querySelectorAll('.mode-content').forEach(content => content.classList.remove('active'));
            document.getElementById(mode + '-mode').classList.add('active');
        }
        
        // 初始化
        document.addEventListener('DOMContentLoaded', function() {
            updateDisplay();
        });
        
        // 防止页面刷新时丢失计时状态
        window.addEventListener('beforeunload', function() {
            if (isRunning) {
                return '计时器正在运行，确定要离开吗？';
            }
        });
    </script>
</body>
</html>
```

**AI辅助学习**:
- 💡 提示词: "JavaScript中Date对象的各种方法和时间计算技巧"
- 🔧 调试技巧: 使用console.log()输出剩余时间，检查定时器是否正常工作
- 📚 扩展阅读: 搜索"JavaScript定时器最佳实践"

**每日挑战**: 添加番茄钟工作法模式（25分钟工作+5分钟休息），或添加多个计时器同时运行

---

### Day 18: 简单笔记应用
**难度**: ⭐⭐⭐  
**知识点**: 本地存储、CRUD操作、搜索过滤、数据管理
**项目描述**: 创建一个功能完整的笔记应用，支持增删改查和搜索

**代码示例**:
```html
<!DOCTYPE html>
<html lang="zh-CN">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>简易笔记应用</title>
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }
        
        body {
            font-family: 'Arial', sans-serif;
            background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
            min-height: 100vh;
            padding: 2rem;
        }
        
        .container {
            max-width: 1200px;
            margin: 0 auto;
        }
        
        .header {
            text-align: center;
            color: white;
            margin-bottom: 2rem;
        }
        
        .header h1 {
            font-size: 2.5rem;
            margin-bottom: 0.5rem;
        }
        
        .main-content {
            display: grid;
            grid-template-columns: 1fr 2fr;
            gap: 2rem;
            height: calc(100vh - 200px);
        }
        
        .sidebar {
            background: white;
            border-radius: 20px;
            padding: 2rem;
            box-shadow: 0 10px 30px rgba(0,0,0,0.1);
            display: flex;
            flex-direction: column;
        }
        
        .content-area {
            background: white;
            border-radius: 20px;
            padding: 2rem;
            box-shadow: 0 10px 30px rgba(0,0,0,0.1);
            display: flex;
            flex-direction: column;
        }
        
        .search-section {
            margin-bottom: 2rem;
        }
        
        .search-input {
            width: 100%;
            padding: 15px;
            border: 2px solid #e1e5e9;
            border-radius: 10px;
            font-size: 16px;
            transition: border-color 0.3s ease;
            margin-bottom: 1rem;
        }
        
        .search-input:focus {
            outline: none;
            border-color: #667eea;
        }
        
        .filter-section {
            display: flex;
            gap: 10px;
            margin-bottom: 2rem;
        }
        
        .filter-btn {
            flex: 1;
            padding: 10px;
            border: 2px solid #e1e5e9;
            background: white;
            border-radius: 8px;
            cursor: pointer;
            transition: all 0.3s ease;
            font-size: 14px;
        }
        
        .filter-btn.active {
            background: #667eea;
            color: white;
            border-color: #667eea;
        }
        
        .new-note-btn {
            background: #667eea;
            color: white;
            border: none;
            padding: 15px;
            border-radius: 10px;
            cursor: pointer;
            font-size: 16px;
            transition: all 0.3s ease;
            margin-bottom: 2rem;
        }
        
        .new-note-btn:hover {
            background: #5a6fd8;
            transform: scale(1.02);
        }
        
        .notes-list {
            flex: 1;
            overflow-y: auto;
        }
        
        .note-item {
            padding: 15px;
            border: 2px solid #e1e5e9;
            border-radius: 10px;
            margin-bottom: 10px;
            cursor: pointer;
            transition: all 0.3s ease;
            position: relative;
        }
        
        .note-item:hover {
            border-color: #667eea;
            background: #f8f9fa;
        }
        
        .note-item.active {
            border-color: #667eea;
            background: #f0f4ff;
        }
        
        .note-item.selected {
            border-color: #28a745;
            background: #d4edda;
        }
        
        .note-title {
            font-weight: bold;
            color: #333;
            margin-bottom: 5px;
            font-size: 1.1rem;
        }
        
        .note-preview {
            color: #666;
            font-size: 0.9rem;
            line-height: 1.4;
            overflow: hidden;
            text-overflow: ellipsis;
            display: -webkit-box;
            -webkit-line-clamp: 2;
            -webkit-box-orient: vertical;
        }
        
        .note-meta {
            display: flex;
            justify-content: space-between;
            align-items: center;
            margin-top: 10px;
            font-size: 0.8rem;
            color: #999;
        }
        
        .note-date {
            flex: 1;
        }
        
        .note-actions {
            display: flex;
            gap: 5px;
        }
        
        .action-btn {
            background: none;
            border: none;
            cursor: pointer;
            padding: 5px;
            border-radius: 3px;
            transition: background 0.2s ease;
            font-size: 12px;
        }
        
        .action-btn:hover {
            background: rgba(0,0,0,0.1);
        }
        
        .delete-btn {
            color: #dc3545;
        }
        
        .delete-btn:hover {
            background: rgba(220, 53, 69, 0.1);
        }
        
        .note-editor {
            flex: 1;
            display: flex;
            flex-direction: column;
        }
        
        .editor-header {
            display: flex;
            justify-content: space-between;
            align-items: center;
            margin-bottom: 1rem;
            padding-bottom: 1rem;
            border-bottom: 2px solid #e1e5e9;
        }
        
        .note-title-input {
            flex: 1;
            font-size: 1.5rem;
            font-weight: bold;
            border: none;
            outline: none;
            color: #333;
            margin-right: 1rem;
        }
        
        .save-status {
            font-size: 0.9rem;
            color: #666;
        }
        
        .save-status.saving {
            color: #ffc107;
        }
        
        .save-status.saved {
            color: #28a745;
        }
        
        .note-content-input {
            flex: 1;
            border: none;
            outline: none;
            font-size: 16px;
            line-height: 1.6;
            color: #333;
            resize: none;
            font-family: inherit;
        }
        
        .note-content-input::placeholder {
            color: #999;
        }
        
        .empty-state {
            text-align: center;
            padding: 60px 20px;
            color: #666;
        }
        
        .empty-state-icon {
            font-size: 4rem;
            margin-bottom: 1rem;
            opacity: 0.5;
        }
        
        .stats-section {
            background: #f8f9fa;
            padding: 1rem;
            border-radius: 10px;
            margin-bottom: 2rem;
        }
        
        .stats-grid {
            display: grid;
            grid-template-columns: repeat(3, 1fr);
            gap: 1rem;
            text-align: center;
        }
        
        .stat-item {
            padding: 10px;
        }
        
        .stat-number {
            font-size: 1.5rem;
            font-weight: bold;
            color: #667eea;
        }
        
        .stat-label {
            font-size: 0.9rem;
            color: #666;
        }
        
        /* 响应式设计 */
        @media (max-width: 768px) {
            .main-content {
                grid-template-columns: 1fr;
                height: auto;
            }
            
            .sidebar,
            .content-area {
                height: 60vh;
            }
            
            .filter-section {
                flex-direction: column;
            }
            
            .stats-grid {
                grid-template-columns: 1fr;
            }
        }
    </style>
</head>
<body>
    <div class="container">
        <div class="header">
            <h1>📝 简易笔记应用</h1>
            <p>记录你的想法和灵感</p>
        </div>
        
        <div class="main-content">
            <!-- 侧边栏 -->
            <div class="sidebar">
                <div class="search-section">
                    <input type="text" class="search-input" id="searchInput" 
                           placeholder="搜索笔记..." oninput="searchNotes()">
                    
                    <div class="filter-section">
                        <button class="filter-btn active" onclick="filterNotes('all', this)">全部</button>
                        <button class="filter-btn" onclick="filterNotes('today', this)">今天</button>
                        <button class="filter-btn" onclick="filterNotes('week', this)">本周</button>
                    </div>
                </div>
                
                <div class="stats-section">
                    <div class="stats-grid">
                        <div class="stat-item">
                            <div class="stat-number" id="totalNotes">0</div>
                            <div class="stat-label">总笔记</div>
                        </div>
                        <div class="stat-item">
                            <div class="stat-number" id="todayNotes">0</div>
                            <div class="stat-label">今日新增</div>
                        </div>
                        <div class="stat-item">
                            <div class="stat-number" id="thisWeekNotes">0</div>
                            <div class="stat-label">本周新增</div>
                        </div>
                    </div>
                </div>
                
                <button class="new-note-btn" onclick="createNewNote()">✏️ 新建笔记</button>
                
                <div class="notes-list" id="notesList">
                    <!-- 笔记列表将在这里生成 -->
                </div>
            </div>
            
            <!-- 内容区域 -->
            <div class="content-area">
                <div class="note-editor" id="noteEditor">
                    <div class="empty-state" id="emptyState">
                        <div class="empty-state-icon">📝</div>
                        <h3>开始记录你的第一个笔记</h3>
                        <p>点击左侧"新建笔记"按钮开始创作</p>
                    </div>
                </div>
            </div>
        </div>
    </div>
    
    <script>
        // 笔记数据
        let notes = JSON.parse(localStorage.getItem('notes')) || [];
        let currentNoteId = null;
        let searchTerm = '';
        let currentFilter = 'all';
        let saveTimeout = null;
        
        // 初始化
        document.addEventListener('DOMContentLoaded', function() {
            renderNotesList();
            updateStats();
            
            // 如果有笔记，显示第一个
            if (notes.length > 0) {
                selectNote(notes[0].id);
            }
        });
        
        // 创建新笔记
        function createNewNote() {
            const newNote = {
                id: Date.now(),
                title: '新建笔记',
                content: '',
                createdAt: new Date().toISOString(),
                updatedAt: new Date().toISOString()
            };
            
            notes.unshift(newNote);
            saveNotes();
            renderNotesList();
            updateStats();
            selectNote(newNote.id);
            
            // 聚焦到标题输入框
            setTimeout(() => {
                document.querySelector('.note-title-input').focus();
                document.querySelector('.note-title-input').select();
            }, 100);
        }
        
        // 选择笔记
        function selectNote(noteId) {
            currentNoteId = noteId;
            
            // 更新列表中的选中状态
            document.querySelectorAll('.note-item').forEach(item => {
                item.classList.remove('active');
            });
            document.querySelector(`[data-id="${noteId}"]`).classList.add('active');
            
            // 显示笔记编辑器
            const note = notes.find(n => n.id === noteId);
            if (note) {
                displayNoteEditor(note);
            }
        }
        
        // 显示笔记编辑器
        function displayNoteEditor(note) {
            const editor = document.getElementById('noteEditor');
            editor.innerHTML = `
                <div class="editor-header">
                    <input type="text" class="note-title-input" id="noteTitle" 
                           value="${escapeHtml(note.title)}" 
                           oninput="updateNoteTitle()" placeholder="笔记标题">
                    <span class="save-status" id="saveStatus">已保存</span>
                </div>
                <textarea class="note-content-input" id="noteContent" 
                          placeholder="开始记录你的想法..."
                          oninput="updateNoteContent()">${escapeHtml(note.content)}</textarea>
            `;
        }
        
        // 更新笔记标题
        function updateNoteTitle() {
            const title = document.getElementById('noteTitle').value.trim();
            const note = notes.find(n => n.id === currentNoteId);
            if (note) {
                note.title = title || '无标题';
                note.updatedAt = new Date().toISOString();
                scheduleSave();
            }
        }
        
        // 更新笔记内容
        function updateNoteContent() {
            const content = document.getElementById('noteContent').value;
            const note = notes.find(n => n.id === currentNoteId);
            if (note) {
                note.content = content;
                note.updatedAt = new Date().toISOString();
                scheduleSave();
            }
        }
        
        // 计划保存（防抖）
        function scheduleSave() {
            const saveStatus = document.getElementById('saveStatus');
            saveStatus.textContent = '保存中...';
            saveStatus.className = 'save-status saving';
            
            if (saveTimeout) {
                clearTimeout(saveTimeout);
            }
            
            saveTimeout = setTimeout(() => {
                saveNotes();
                renderNotesList();
                saveStatus.textContent = '已保存';
                saveStatus.className = 'save-status saved';
                
                setTimeout(() => {
                    saveStatus.textContent = '已保存';
                    saveStatus.className = 'save-status';
                }, 2000);
            }, 500);
        }
        
        // 删除笔记
        function deleteNote(noteId, event) {
            event.stopPropagation();
            
            if (confirm('确定要删除这个笔记吗？')) {
                notes = notes.filter(n => n.id !== noteId);
                saveNotes();
                renderNotesList();
                updateStats();
                
                if (currentNoteId === noteId) {
                    currentNoteId = null;
                    if (notes.length > 0) {
                        selectNote(notes[0].id);
                    } else {
                        showEmptyState();
                    }
                }
            }
        }
        
        // 显示空状态
        function showEmptyState() {
            const editor = document.getElementById('noteEditor');
            editor.innerHTML = `
                <div class="empty-state">
                    <div class="empty-state-icon">📝</div>
                    <h3>选择一个笔记开始编辑</h3>
                    <p>或者创建一个新的笔记</p>
                </div>
            `;
        }
        
        // 搜索笔记
        function searchNotes() {
            searchTerm = document.getElementById('searchInput').value.toLowerCase();
            renderNotesList();
        }
        
        // 过滤笔记
        function filterNotes(filter, element) {
            currentFilter = filter;
            
            // 更新按钮状态
            document.querySelectorAll('.filter-btn').forEach(btn => btn.classList.remove('active'));
            element.classList.add('active');
            
            renderNotesList();
        }
        
        // 渲染笔记列表
        function renderNotesList() {
            let filteredNotes = notes;
            
            // 应用搜索过滤
            if (searchTerm) {
                filteredNotes = filteredNotes.filter(note => 
                    note.title.toLowerCase().includes(searchTerm) ||
                    note.content.toLowerCase().includes(searchTerm)
                );
            }
            
            // 应用时间过滤
            const now = new Date();
            if (currentFilter === 'today') {
                filteredNotes = filteredNotes.filter(note => {
                    const noteDate = new Date(note.createdAt);
                    return noteDate.toDateString() === now.toDateString();
                });
            } else if (currentFilter === 'week') {
                const weekAgo = new Date(now.getTime() - 7 * 24 * 60 * 60 * 1000);
                filteredNotes = filteredNotes.filter(note => {
                    const noteDate = new Date(note.createdAt);
                    return noteDate >= weekAgo;
                });
            }
            
            const notesList = document.getElementById('notesList');
            
            if (filteredNotes.length === 0) {
                notesList.innerHTML = `
                    <div class="empty-state">
                        <div class="empty-state-icon" style="font-size: 2rem;">🔍</div>
                        <h4>没有找到笔记</h4>
                        <p>尝试调整搜索条件或创建新笔记</p>
                    </div>
                `;
                return;
            }
            
            notesList.innerHTML = filteredNotes.map(note => `
                <div class="note-item ${note.id === currentNoteId ? 'active' : ''}" 
                     data-id="${note.id}" onclick="selectNote(${note.id})">
                    <div class="note-title">${escapeHtml(note.title)}</div>
                    <div class="note-preview">${escapeHtml(note.content.substring(0, 100))}${note.content.length > 100 ? '...' : ''}</div>
                    <div class="note-meta">
                        <div class="note-date">${formatDate(note.updatedAt)}</div>
                        <div class="note-actions">
                            <button class="action-btn delete-btn" onclick="deleteNote(${note.id}, event)">删除</button>
                        </div>
                    </div>
                </div>
            `).join('');
        }
        
        // 更新统计信息
        function updateStats() {
            const now = new Date();
            const today = now.toDateString();
            const weekAgo = new Date(now.getTime() - 7 * 24 * 60 * 60 * 1000);
            
            const totalNotes = notes.length;
            const todayNotes = notes.filter(note => {
                const noteDate = new Date(note.createdAt);
                return noteDate.toDateString() === today;
            }).length;
            
            const thisWeekNotes = notes.filter(note => {
                const noteDate = new Date(note.createdAt);
                return noteDate >= weekAgo;
            }).length;
            
            document.getElementById('totalNotes').textContent = totalNotes;
            document.getElementById('todayNotes').textContent = todayNotes;
            document.getElementById('thisWeekNotes').textContent = thisWeekNotes;
        }
        
        // 保存笔记到本地存储
        function saveNotes() {
            localStorage.setItem('notes', JSON.stringify(notes));
        }
        
        // 转义HTML
        function escapeHtml(text) {
            const div = document.createElement('div');
            div.textContent = text;
            return div.innerHTML;
        }
        
        // 格式化日期
        function formatDate(dateString) {
            const date = new Date(dateString);
            const now = new Date();
            const diff = now - date;
            
            if (diff < 60000) { // 1分钟内
                return '刚刚';
            } else if (diff < 3600000) { // 1小时内
                return `${Math.floor(diff / 60000)}分钟前`;
            } else if (diff < 86400000) { // 1天内
                return `${Math.floor(diff / 3600000)}小时前`;
            } else if (diff < 2592000000) { // 30天内
                return `${Math.floor(diff / 86400000)}天前`;
            } else {
                return date.toLocaleDateString('zh-CN');
            }
        }
        
        // 键盘快捷键
        document.addEventListener('keydown', function(event) {
            if (event.ctrlKey || event.metaKey) {
                switch(event.key) {
                    case 'n':
                        event.preventDefault();
                        createNewNote();
                        break;
                    case 's':
                        event.preventDefault();
                        if (saveTimeout) {
                            clearTimeout(saveTimeout);
                            scheduleSave();
                        }
                        break;
                }
            }
        });
    </script>
</body>
</html>
```

**AI辅助学习**:
- 💡 提示词: "JavaScript本地存储的性能优化，如何避免阻塞主线程？"
- 🔧 调试技巧: 使用浏览器开发者工具的"Application"面板查看和管理本地存储数据
- 📚 扩展阅读: 搜索"JavaScript防抖和节流技术"

**每日挑战**: 添加笔记分类和标签功能，或添加导出/导入笔记功能

---

### Day 19: 表单验证器
**难度**: ⭐⭐⭐⭐  
**知识点**: 正则表达式、表单验证、错误处理、用户反馈
**项目描述**: 创建一个强大的表单验证库，支持各种验证规则和自定义提示

**代码示例**:
```html
<!DOCTYPE html>
<html lang="zh-CN">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>表单验证器示例</title>
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }
        
        body {
            font-family: 'Arial', sans-serif;
            background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
            min-height: 100vh;
            padding: 2rem;
        }
        
        .container {
            max-width: 800px;
            margin: 0 auto;
        }
        
        .header {
            text-align: center;
            color: white;
            margin-bottom: 2rem;
        }
        
        .header h1 {
            font-size: 2.5rem;
            margin-bottom: 0.5rem;
        }
        
        .form-container {
            background: white;
            border-radius: 20px;
            padding: 2rem;
            box-shadow: 0 10px 30px rgba(0,0,0,0.1);
        }
        
        .form-section {
            margin-bottom: 2rem;
        }
        
        .form-section h3 {
            color: #333;
            margin-bottom: 1rem;
            padding-bottom: 0.5rem;
            border-bottom: 2px solid #e1e5e9;
        }
        
        .form-group {
            margin-bottom: 1.5rem;
            position: relative;
        }
        
        .form-label {
            display: block;
            margin-bottom: 0.5rem;
            color: #333;
            font-weight: 500;
        }
        
        .form-input {
            width: 100%;
            padding: 12px 15px;
            border: 2px solid #e1e5e9;
            border-radius: 8px;
            font-size: 16px;
            transition: all 0.3s ease;
            background: white;
        }
        
        .form-input:focus {
            outline: none;
            border-color: #667eea;
            box-shadow: 0 0 0 3px rgba(102, 126, 234, 0.1);
        }
        
        .form-input.valid {
            border-color: #28a745;
            background: #f8fff9;
        }
        
        .form-input.invalid {
            border-color: #dc3545;
            background: #fff8f8;
        }
        
        .form-input.disabled {
            background: #f8f9fa;
            cursor: not-allowed;
            opacity: 0.6;
        }
        
        .input-icon {
            position: absolute;
            right: 15px;
            top: 50%;
            transform: translateY(-50%);
            font-size: 1.2rem;
            opacity: 0;
            transition: opacity 0.3s ease;
        }
        
        .input-icon.show {
            opacity: 1;
        }
        
        .input-icon.valid {
            color: #28a745;
        }
        
        .input-icon.invalid {
            color: #dc3545;
        }
        
        .error-message {
            color: #dc3545;
            font-size: 0.875rem;
            margin-top: 5px;
            opacity: 0;
            transform: translateY(-10px);
            transition: all 0.3s ease;
        }
        
        .error-message.show {
            opacity: 1;
            transform: translateY(0);
        }
        
        .hint-message {
            color: #6c757d;
            font-size: 0.875rem;
            margin-top: 5px;
        }
        
        .form-row {
            display: grid;
            grid-template-columns: 1fr 1fr;
            gap: 1rem;
        }
        
        .checkbox-group {
            display: flex;
            align-items: center;
            gap: 10px;
        }
        
        .checkbox-group input[type="checkbox"] {
            width: 18px;
            height: 18px;
        }
        
        .submit-section {
            text-align: center;
            padding-top: 2rem;
            border-top: 2px solid #e1e5e9;
        }
        
        .submit-btn {
            background: #667eea;
            color: white;
            border: none;
            padding: 15px 40px;
            border-radius: 10px;
            cursor: pointer;
            font-size: 18px;
            font-weight: bold;
            transition: all 0.3s ease;
            min-width: 200px;
        }
        
        .submit-btn:hover:not(:disabled) {
            background: #5a6fd8;
            transform: scale(1.05);
        }
        
        .submit-btn:disabled {
            opacity: 0.6;
            cursor: not-allowed;
        }
        
        .validation-summary {
            background: #f8d7da;
            border: 1px solid #f5c6cb;
            color: #721c24;
            padding: 15px;
            border-radius: 8px;
            margin-bottom: 1rem;
            display: none;
        }
        
        .validation-summary.show {
            display: block;
        }
        
        .validation-summary h4 {
            margin-bottom: 10px;
        }
        
        .validation-list {
            list-style: none;
            padding: 0;
        }
        
        .validation-list li {
            margin-bottom: 5px;
        }
        
        /* 密码强度指示器 */
        .password-strength {
            margin-top: 10px;
        }
        
        .strength-bar {
            height: 6px;
            background: #e1e5e9;
            border-radius: 3px;
            overflow: hidden;
        }
        
        .strength-fill {
            height: 100%;
            width: 0%;
            transition: all 0.3s ease;
            border-radius: 3px;
        }
        
        .strength-fill.weak {
            background: #dc3545;
            width: 33%;
        }
        
        .strength-fill.medium {
            background: #ffc107;
            width: 66%;
        }
        
        .strength-fill.strong {
            background: #28a745;
            width: 100%;
        }
        
        .strength-text {
            font-size: 0.875rem;
            margin-top: 5px;
        }
        
        .strength-text.weak {
            color: #dc3545;
        }
        
        .strength-text.medium {
            color: #856404;
        }
        
        .strength-text.strong {
            color: #28a745;
        }
        
        /* 响应式设计 */
        @media (max-width: 768px) {
            .form-row {
                grid-template-columns: 1fr;
            }
            
            .container {
                padding: 1rem;
            }
            
            .form-container {
                padding: 1.5rem;
            }
        }
    </style>
</head>
<body>
    <div class="container">
        <div class="header">
            <h1>🔍 表单验证器</h1>
            <p>强大而灵活的表单验证解决方案</p>
        </div>
        
        <div class="form-container">
            <form id="demoForm" onsubmit="handleSubmit(event)">
                <div class="validation-summary" id="validationSummary">
                    <h4>请修正以下错误：</h4>
                    <ul class="validation-list" id="validationList"></ul>
                </div>
                
                <div class="form-section">
                    <h3>基本信息</h3>
                    
                    <div class="form-row">
                        <div class="form-group">
                            <label class="form-label" for="firstName">姓名 *</label>
                            <input type="text" class="form-input" id="firstName" 
                                   data-rules="required|min:2|max:20" 
                                   data-message-required="请输入姓名"
                                   data-message-min="姓名至少需要2个字符"
                                   data-message-max="姓名不能超过20个字符"
                                   placeholder="请输入姓名">
                            <div class="input-icon" id="firstNameIcon"></div>
                            <div class="error-message" id="firstNameError"></div>
                        </div>
                        
                        <div class="form-group">
                            <label class="form-label" for="lastName">姓氏 *</label>
                            <input type="text" class="form-input" id="lastName" 
                                   data-rules="required|min:2|max:20"
                                   data-message-required="请输入姓氏"
                                   data-message-min="姓氏至少需要2个字符"
                                   data-message-max="姓氏不能超过20个字符"
                                   placeholder="请输入姓氏">
                            <div class="input-icon" id="lastNameIcon"></div>
                            <div class="error-message" id="lastNameError"></div>
                        </div>
                    </div>
                    
                    <div class="form-group">
                        <label class="form-label" for="email">邮箱地址 *</label>
                        <input type="email" class="form-input" id="email" 
                               data-rules="required|email"
                               data-message-required="请输入邮箱地址"
                               data-message-email="请输入有效的邮箱地址"
                               placeholder="example@email.com">
                        <div class="input-icon" id="emailIcon"></div>
                        <div class="error-message" id="emailError"></div>
                    </div>
                    
                    <div class="form-group">
                        <label class="form-label" for="phone">手机号码 *</label>
                        <input type="tel" class="form-input" id="phone" 
                               data-rules="required|phone"
                               data-message-required="请输入手机号码"
                               data-message-phone="请输入有效的手机号码"
                               placeholder="请输入手机号码">
                        <div class="input-icon" id="phoneIcon"></div>
                        <div class="error-message" id="phoneError"></div>
                        <div class="hint-message">请输入11位手机号码</div>
                    </div>
                </div>
                
                <div class="form-section">
                    <h3>账户信息</h3>
                    
                    <div class="form-group">
                        <label class="form-label" for="username">用户名 *</label>
                        <input type="text" class="form-input" id="username" 
                               data-rules="required|min:4|max:16|alnum"
                               data-message-required="请输入用户名"
                               data-message-min="用户名至少需要4个字符"
                               data-message-max="用户名不能超过16个字符"
                               data-message-alnum="用户名只能包含字母和数字"
                               placeholder="4-16位字母或数字">
                        <div class="input-icon" id="usernameIcon"></div>
                        <div class="error-message" id="usernameError"></div>
                    </div>
                    
                    <div class="form-group">
                        <label class="form-label" for="password">密码 *</label>
                        <input type="password" class="form-input" id="password" 
                               data-rules="required|min:6|max:20|strong"
                               data-message-required="请输入密码"
                               data-message-min="密码至少需要6个字符"
                               data-message-max="密码不能超过20个字符"
                               data-message-strong="密码必须包含大小写字母、数字和特殊字符"
                               placeholder="请输入密码" oninput="checkPasswordStrength(this.value)">
                        <div class="input-icon" id="passwordIcon"></div>
                        <div class="error-message" id="passwordError"></div>
                        
                        <div class="password-strength">
                            <div class="strength-bar">
                                <div class="strength-fill" id="strengthFill"></div>
                            </div>
                            <div class="strength-text" id="strengthText">密码强度</div>
                        </div>
                    </div>
                    
                    <div class="form-group">
                        <label class="form-label" for="confirmPassword">确认密码 *</label>
                        <input type="password" class="form-input" id="confirmPassword" 
                               data-rules="required|match:password"
                               data-message-required="请确认密码"
                               data-message-match="两次输入的密码不一致"
                               placeholder="请再次输入密码">
                        <div class="input-icon" id="confirmPasswordIcon"></div>
                        <div class="error-message" id="confirmPasswordError"></div>
                    </div>
                </div>
                
                <div class="form-section">
                    <h3>其他信息</h3>
                    
                    <div class="form-group">
                        <label class="form-label" for="age">年龄</label>
                        <input type="number" class="form-input" id="age" 
                               data-rules="min:18|max:100"
                               data-message-min="年龄必须大于等于18岁"
                               data-message-max="年龄不能超过100岁"
                               placeholder="请输入年龄">
                        <div class="input-icon" id="ageIcon"></div>
                        <div class="error-message" id="ageError"></div>
                    </div>
                    
                    <div class="form-group">
                        <label class="form-label" for="website">个人网站</label>
                        <input type="url" class="form-input" id="website" 
                               data-rules="url"
                               data-message-url="请输入有效的网址"
                               placeholder="https://example.com">
                        <div class="input-icon" id="websiteIcon"></div>
                        <div class="error-message" id="websiteError"></div>
                    </div>
                    
                    <div class="form-group">
                        <label class="form-label" for="bio">个人简介</label>
                        <textarea class="form-input" id="bio" rows="4" 
                                  data-rules="max:200"
                                  data-message-max="个人简介不能超过200个字符"
                                  placeholder="请简单介绍一下自己"></textarea>
                        <div class="input-icon" id="bioIcon"></div>
                        <div class="error-message" id="bioError"></div>
                    </div>
                    
                    <div class="form-group">
                        <div class="checkbox-group">
                            <input type="checkbox" id="agreeTerms" 
                                   data-rules="required"
                                   data-message-required="请同意服务条款">
                            <label for="agreeTerms">我已阅读并同意服务条款和隐私政策 *</label>
                        </div>
                        <div class="error-message" id="agreeTermsError"></div>
                    </div>
                </div>
                
                <div class="submit-section">
                    <button type="submit" class="submit-btn" id="submitBtn">提交注册</button>
                </div>
            </form>
        </div>
    </div>
    
    <script>
        // 验证规则
        const validators = {
            required: (value) => value.trim() !== '',
            email: (value) => /^[^\s@]+@[^\s@]+\.[^\s@]+$/.test(value),
            phone: (value) => /^1[3-9]\d{9}$/.test(value),
            min: (value, param) => value.length >= parseInt(param),
            max: (value, param) => value.length <= parseInt(param),
            alnum: (value) => /^[a-zA-Z0-9]+$/.test(value),
            strong: (value) => /^(?=.*[a-z])(?=.*[A-Z])(?=.*\d)(?=.*[@$!%*?&])[A-Za-z\d@$!%*?&]{6,20}$/.test(value),
            match: (value, param) => value === document.getElementById(param).value,
            url: (value) => {
                try {
                    new URL(value);
                    return true;
                } catch {
                    return value === '';
                }
            }
        };
        
        // 密码强度检查
        function checkPasswordStrength(password) {
            const strengthFill = document.getElementById('strengthFill');
            const strengthText = document.getElementById('strengthText');
            
            let strength = 0;
            let strengthClass = '';
            let strengthLabel = '';
            
            if (password.length >= 6) strength++;
            if (password.length >= 8) strength++;
            if (/[a-z]/.test(password) && /[A-Z]/.test(password)) strength++;
            if (/\d/.test(password)) strength++;
            if (/[@$!%*?&]/.test(password)) strength++;
            
            if (strength < 2) {
                strengthClass = 'weak';
                strengthLabel = '弱';
            } else if (strength < 4) {
                strengthClass = 'medium';
                strengthLabel = '中';
            } else {
                strengthClass = 'strong';
                strengthLabel = '强';
            }
            
            strengthFill.className = `strength-fill ${strengthClass}`;
            strengthText.className = `strength-text ${strengthClass}`;
            strengthText.textContent = `密码强度: ${strengthLabel}`;
        }
        
        // 验证单个字段
        function validateField(field) {
            const rules = field.dataset.rules;
            const value = field.value.trim();
            const fieldId = field.id;
            const errorElement = document.getElementById(fieldId + 'Error');
            const iconElement = document.getElementById(fieldId + 'Icon');
            
            if (!rules) return true;
            
            const ruleList = rules.split('|');
            
            for (const rule of ruleList) {
                const [ruleName, param] = rule.split(':');
                
                if (validators[ruleName]) {
                    const isValid = validators[ruleName](value, param);
                    
                    if (!isValid) {
                        const message = field.dataset[`message${ruleName.charAt(0).toUpperCase() + ruleName.slice(1)}`];
                        showFieldError(field, errorElement, iconElement, message || getDefaultMessage(ruleName, param));
                        return false;
                    }
                }
            }
            
            showFieldSuccess(field, errorElement, iconElement);
            return true;
        }
        
        // 显示字段错误
        function showFieldError(field, errorElement, iconElement, message) {
            field.classList.remove('valid');
            field.classList.add('invalid');
            
            errorElement.textContent = message;
            errorElement.classList.add('show');
            
            iconElement.innerHTML = '✗';
            iconElement.className = 'input-icon invalid show';
        }
        
        // 显示字段成功
        function showFieldSuccess(field, errorElement, iconElement) {
            field.classList.remove('invalid');
            field.classList.add('valid');
            
            errorElement.classList.remove('show');
            
            iconElement.innerHTML = '✓';
            iconElement.className = 'input-icon valid show';
        }
        
        // 获取默认错误消息
        function getDefaultMessage(ruleName, param) {
            const messages = {
                required: '此字段为必填项',
                email: '请输入有效的邮箱地址',
                phone: '请输入有效的手机号码',
                min: `最少需要${param}个字符`,
                max: `最多允许${param}个字符`,
                alnum: '只能包含字母和数字',
                strong: '密码强度不够',
                match: '两次输入不一致',
                url: '请输入有效的网址'
            };
            return messages[ruleName] || '输入无效';
        }
        
        // 验证整个表单
        function validateForm() {
            const form = document.getElementById('demoForm');
            const fields = form.querySelectorAll('[data-rules]');
            const summary = document.getElementById('validationSummary');
            const list = document.getElementById('validationList');
            
            let isValid = true;
            const errors = [];
            
            fields.forEach(field => {
                const fieldIsValid = validateField(field);
                if (!fieldIsValid) {
                    isValid = false;
                    const label = document.querySelector(`label[for="${field.id}"]`);
                    errors.push(`${label.textContent.replace(' *', '')}: ${document.getElementById(field.id + 'Error').textContent}`);
                }
            });
            
            if (!isValid) {
                list.innerHTML = errors.map(error => `<li>${error}</li>`).join('');
                summary.classList.add('show');
            } else {
                summary.classList.remove('show');
            }
            
            return isValid;
        }
        
        // 处理表单提交
        function handleSubmit(event) {
            event.preventDefault();
            
            if (validateForm()) {
                const submitBtn = document.getElementById('submitBtn');
                submitBtn.textContent = '提交中...';
                submitBtn.disabled = true;
                
                // 模拟提交
                setTimeout(() => {
                    alert('表单验证通过！提交成功！');
                    submitBtn.textContent = '提交注册';
                    submitBtn.disabled = false;
                }, 2000);
            }
        }
        
        // 添加事件监听器
        document.addEventListener('DOMContentLoaded', function() {
            const form = document.getElementById('demoForm');
            const fields = form.querySelectorAll('[data-rules]');
            
            // 实时验证
            fields.forEach(field => {
                field.addEventListener('blur', () => validateField(field));
                field.addEventListener('input', () => {
                    if (field.classList.contains('invalid')) {
                        validateField(field);
                    }
                });
            });
            
            // 表单提交
            form.addEventListener('submit', handleSubmit);
        });
    </script>
</body>
</html>
```

**AI辅助学习**:
- 💡 提示词: "JavaScript正则表达式的性能优化和常见陷阱"
- 🔧 调试技巧: 使用console.log()输出验证结果，检查正则表达式是否按预期工作
- 📚 扩展阅读: 搜索"JavaScript正则表达式完全指南"

**每日挑战**: 添加异步验证（如检查用户名是否已存在），或添加自定义验证规则功能

---

### Day 20: 拖拽拼图游戏
**难度**: ⭐⭐⭐⭐  
**知识点**: 拖拽API、事件处理、游戏逻辑、CSS动画
**项目描述**: 创建一个可交互的拖拽拼图游戏，支持难度选择和计时功能

**代码示例**:
```html
<!DOCTYPE html>
<html lang="zh-CN">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>拖拽拼图游戏</title>
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }
        
        body {
            font-family: 'Arial', sans-serif;
            background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
            min-height: 100vh;
            padding: 2rem;
        }
        
        .container {
            max-width: 1200px;
            margin: 0 auto;
        }
        
        .header {
            text-align: center;
            color: white;
            margin-bottom: 2rem;
        }
        
        .header h1 {
            font-size: 2.5rem;
            margin-bottom: 0.5rem;
        }
        
        .game-controls {
            background: white;
            border-radius: 20px;
            padding: 2rem;
            margin-bottom: 2rem;
            box-shadow: 0 10px 30px rgba(0,0,0,0.1);
        }
        
        .controls-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(200px, 1fr));
            gap: 2rem;
            align-items: end;
        }
        
        .control-group {
            display: flex;
            flex-direction: column;
        }
        
        .control-label {
            font-weight: bold;
            color: #333;
            margin-bottom: 0.5rem;
        }
        
        .control-select {
            padding: 12px;
            border: 2px solid #e1e5e9;
            border-radius: 8px;
            font-size: 16px;
            background: white;
            cursor: pointer;
            transition: border-color 0.3s ease;
        }
        
        .control-select:focus {
            outline: none;
            border-color: #667eea;
        }
        
        .control-btn {
            background: #667eea;
            color: white;
            border: none;
            padding: 12px 24px;
            border-radius: 8px;
            cursor: pointer;
            font-size: 16px;
            transition: all 0.3s ease;
        }
        
        .control-btn:hover {
            background: #5a6fd8;
            transform: scale(1.05);
        }
        
        .control-btn:disabled {
            opacity: 0.6;
            cursor: not-allowed;
            transform: none;
        }
        
        .game-stats {
            display: grid;
            grid-template-columns: repeat(4, 1fr);
            gap: 1rem;
            margin-top: 2rem;
            padding-top: 2rem;
            border-top: 2px solid #e1e5e9;
        }
        
        .stat-item {
            text-align: center;
        }
        
        .stat-value {
            font-size: 1.5rem;
            font-weight: bold;
            color: #667eea;
            margin-bottom: 0.25rem;
        }
        
        .stat-label {
            font-size: 0.9rem;
            color: #666;
        }
        
        .game-area {
            display: grid;
            grid-template-columns: 1fr 1fr;
            gap: 2rem;
            height: 600px;
        }
        
        .puzzle-container {
            background: white;
            border-radius: 20px;
            padding: 2rem;
            box-shadow: 0 10px 30px rgba(0,0,0,0.1);
            display: flex;
            flex-direction: column;
        }
        
        .puzzle-title {
            font-size: 1.2rem;
            font-weight: bold;
            color: #333;
            margin-bottom: 1rem;
            text-align: center;
        }
        
        .puzzle-board {
            flex: 1;
            position: relative;
            border: 3px solid #e1e5e9;
            border-radius: 10px;
            overflow: hidden;
            background: #f8f9fa;
        }
        
        .puzzle-piece {
            position: absolute;
            background-size: cover;
            cursor: grab;
            transition: all 0.3s ease;
            border: 2px solid transparent;
            box-shadow: 0 2px 8px rgba(0,0,0,0.2);
        }
        
        .puzzle-piece:hover {
            transform: scale(1.05);
            z-index: 10;
            box-shadow: 0 5px 20px rgba(0,0,0,0.3);
        }
        
        .puzzle-piece.dragging {
            cursor: grabbing;
            transform: scale(1.1);
            z-index: 100;
            box-shadow: 0 10px 30px rgba(0,0,0,0.4);
        }
        
        .puzzle-piece.correct {
            border-color: #28a745;
            box-shadow: 0 0 15px rgba(40, 167, 69, 0.5);
        }
        
        .puzzle-piece.incorrect {
            border-color: #dc3545;
            animation: shake 0.5s ease-in-out;
        }
        
        @keyframes shake {
            0%, 100% { transform: translateX(0); }
            25% { transform: translateX(-10px); }
            75% { transform: translateX(10px); }
        }
        
        .preview-container {
            background: white;
            border-radius: 20px;
            padding: 2rem;
            box-shadow: 0 10px 30px rgba(0,0,0,0.1);
            display: flex;
            flex-direction: column;
            align-items: center;
        }
        
        .preview-image {
            max-width: 100%;
            max-height: 400px;
            border-radius: 10px;
            box-shadow: 0 5px 15px rgba(0,0,0,0.2);
        }
        
        .preview-info {
            margin-top: 1rem;
            text-align: center;
            color: #666;
        }
        
        .success-modal {
            position: fixed;
            top: 0;
            left: 0;
            width: 100%;
            height: 100%;
            background: rgba(0, 0, 0, 0.8);
            display: flex;
            justify-content: center;
            align-items: center;
            z-index: 1000;
            opacity: 0;
            visibility: hidden;
            transition: all 0.3s ease;
        }
        
        .success-modal.show {
            opacity: 1;
            visibility: visible;
        }
        
        .success-content {
            background: white;
            padding: 3rem 2rem;
            border-radius: 20px;
            text-align: center;
            max-width: 400px;
            transform: scale(0.7);
            transition: transform 0.3s ease;
        }
        
        .success-modal.show .success-content {
            transform: scale(1);
        }
        
        .success-icon {
            font-size: 4rem;
            color: #28a745;
            margin-bottom: 1rem;
        }
        
        .success-title {
            font-size: 1.5rem;
            color: #333;
            margin-bottom: 1rem;
        }
        
        .success-stats {
            background: #f8f9fa;
            padding: 1rem;
            border-radius: 10px;
            margin: 1rem 0;
        }
        
        .success-btn {
            background: #28a745;
            color: white;
            border: none;
            padding: 12px 24px;
            border-radius: 8px;
            cursor: pointer;
            font-size: 16px;
            margin-top: 1rem;
            transition: background 0.3s ease;
        }
        
        .success-btn:hover {
            background: #218838;
        }
        
        /* 响应式设计 */
        @media (max-width: 768px) {
            .game-area {
                grid-template-columns: 1fr;
                height: auto;
            }
            
            .game-stats {
                grid-template-columns: repeat(2, 1fr);
            }
            
            .controls-grid {
                grid-template-columns: 1fr;
            }
            
            .puzzle-container,
            .preview-container {
                height: 400px;
            }
        }
    </style>
</head>
<body>
    <div class="container">
        <div class="header">
            <h1>🧩 拖拽拼图游戏</h1>
            <p>挑战你的观察力和耐心</p>
        </div>
        
        <div class="game-controls">
            <div class="controls-grid">
                <div class="control-group">
                    <label class="control-label">选择图片</label>
                    <select class="control-select" id="imageSelect" onchange="changeImage()">
                        <option value="1">风景图 1</option>
                        <option value="2">风景图 2</option>
                        <option value="3">风景图 3</option>
                        <option value="4">风景图 4</option>
                        <option value="5">风景图 5</option>
                    </select>
                </div>
                
                <div class="control-group">
                    <label class="control-label">难度级别</label>
                    <select class="control-select" id="difficultySelect" onchange="changeDifficulty()">
                        <option value="3">简单 (3×3)</option>
                        <option value="4" selected>中等 (4×4)</option>
                        <option value="5">困难 (5×5)</option>
                        <option value="6">专家 (6×6)</option>
                    </select>
                </div>
                
                <div class="control-group">
                    <button class="control-btn" onclick="startNewGame()">新游戏</button>
                </div>
                
                <div class="control-group">
                    <button class="control-btn" onclick="showHint()">显示提示</button>
                </div>
            </div>
            
            <div class="game-stats">
                <div class="stat-item">
                    <div class="stat-value" id="moveCount">0</div>
                    <div class="stat-label">移动次数</div>
                </div>
                <div class="stat-item">
                    <div class="stat-value" id="timeElapsed">00:00</div>
                    <div class="stat-label">用时</div>
                </div>
                <div class="stat-item">
                    <div class="stat-value" id="difficultyText">中等</div>
                    <div class="stat-label">难度</div>
                </div>
                <div class="stat-item">
                    <div class="stat-value" id="completionRate">0%</div>
                    <div class="stat-label">完成度</div>
                </div>
            </div>
        </div>
        
        <div class="game-area">
            <div class="puzzle-container">
                <div class="puzzle-title">拼图区域</div>
                <div class="puzzle-board" id="puzzleBoard">
                    <!-- 拼图块将在这里生成 -->
                </div>
            </div>
            
            <div class="preview-container">
                <div class="puzzle-title">参考图片</div>
                <img src="https://picsum.photos/400/400?random=1" alt="参考图片" 
                     class="preview-image" id="previewImage">
                <div class="preview-info">
                    <p>将右侧的拼图块拖拽到左侧正确位置</p>
                </div>
            </div>
        </div>
    </div>
    
    <!-- 成功模态框 -->
    <div class="success-modal" id="successModal">
        <div class="success-content">
            <div class="success-icon">🎉</div>
            <h3 class="success-title">恭喜完成！</h3>
            <p>你成功完成了拼图挑战！</p>
            
            <div class="success-stats">
                <p>移动次数: <strong id="finalMoves">0</strong></p>
                <p>用时: <strong id="finalTime">00:00</strong></p>
                <p>难度: <strong id="finalDifficulty">中等</strong></p>
            </div>
            
            <button class="success-btn" onclick="startNewGame()">再玩一次</button>
            <button class="success-btn" onclick="closeSuccessModal()" style="background: #6c757d;">关闭</button>
        </div>
    </div>
    
    <script>
        // 游戏状态
        let currentImageId = 1;
        let gridSize = 4;
        let pieces = [];
        let correctPositions = [];
        let moveCount = 0;
        let startTime = null;
        let timerInterval = null;
        let isGameComplete = false;
        
        // 初始化游戏
        function initGame() {
            updateDifficultyText();
            loadImage();
            createPuzzle();
            resetStats();
        }
        
        // 加载图片
        function loadImage() {
            const previewImage = document.getElementById('previewImage');
            previewImage.src = `https://picsum.photos/400/400?random=${currentImageId}`;
        }
        
        // 创建拼图
        function createPuzzle() {
            const board = document.getElementById('puzzleBoard');
            board.innerHTML = '';
            pieces = [];
            correctPositions = [];
            
            const pieceSize = 400 / gridSize;
            
            // 创建拼图块
            for (let row = 0; row < gridSize; row++) {
                for (let col = 0; col < gridSize; col++) {
                    const piece = document.createElement('div');
                    piece.className = 'puzzle-piece';
                    piece.style.width = pieceSize + 'px';
                    piece.style.height = pieceSize + 'px';
                    piece.style.backgroundImage = `url(https://picsum.photos/400/400?random=${currentImageId})`;
                    piece.style.backgroundPosition = `-${col * pieceSize}px -${row * pieceSize}px`;
                    
                    const correctRow = Math.floor(Math.random() * gridSize);
                    const correctCol = Math.floor(Math.random() * gridSize);
                    
                    piece.style.left = correctCol * pieceSize + 'px';
                    piece.style.top = correctRow * pieceSize + 'px';
                    
                    piece.dataset.correctRow = row;
                    piece.dataset.correctCol = col;
                    piece.dataset.currentRow = correctRow;
                    piece.dataset.currentCol = correctCol;
                    
                    // 添加拖拽事件
                    piece.draggable = true;
                    piece.addEventListener('dragstart', handleDragStart);
                    piece.addEventListener('dragend', handleDragEnd);
                    
                    // 添加点击事件（移动设备）
                    piece.addEventListener('click', handlePieceClick);
                    
                    board.appendChild(piece);
                    pieces.push(piece);
                    correctPositions.push({ row, col });
                }
            }
            
            // 添加放置区域事件
            board.addEventListener('dragover', handleDragOver);
            board.addEventListener('drop', handleDrop);
            
            updateCompletionRate();
        }
        
        // 拖拽开始
        function handleDragStart(event) {
            if (isGameComplete) return;
            
            event.target.classList.add('dragging');
            event.dataTransfer.setData('text/plain', event.target.dataset.currentRow + ',' + event.target.dataset.currentCol);
        }
        
        // 拖拽结束
        function handleDragEnd(event) {
            event.target.classList.remove('dragging');
        }
        
        // 拖拽经过
        function handleDragOver(event) {
            event.preventDefault();
        }
        
        // 放置
        function handleDrop(event) {
            event.preventDefault();
            if (isGameComplete) return;
            
            const data = event.dataTransfer.getData('text/plain').split(',');
            const draggedRow = parseInt(data[0]);
            const draggedCol = parseInt(data[1]);
            
            const rect = event.currentTarget.getBoundingClientRect();
            const x = event.clientX - rect.left;
            const y = event.clientY - rect.top;
            
            const pieceSize = 400 / gridSize;
            const targetRow = Math.floor(y / pieceSize);
            const targetCol = Math.floor(x / pieceSize);
            
            swapPieces(draggedRow, draggedCol, targetRow, targetCol);
        }
        
        // 处理拼图块点击（移动设备）
        let selectedPiece = null;
        
        function handlePieceClick(event) {
            if (isGameComplete) return;
            
            if (selectedPiece === null) {
                // 选择第一个拼图块
                selectedPiece = event.target;
                selectedPiece.classList.add('selected');
            } else if (selectedPiece === event.target) {
                // 取消选择
                selectedPiece.classList.remove('selected');
                selectedPiece = null;
            } else {
                // 交换两个拼图块
                const firstRow = parseInt(selectedPiece.dataset.currentRow);
                const firstCol = parseInt(selectedPiece.dataset.currentCol);
                const secondRow = parseInt(event.target.dataset.currentRow);
                const secondCol = parseInt(event.target.dataset.currentCol);
                
                swapPieces(firstRow, firstCol, secondRow, secondCol);
                
                selectedPiece.classList.remove('selected');
                selectedPiece = null;
            }
        }
        
        // 交换拼图块
        function swapPieces(row1, col1, row2, col2) {
            if (row1 === row2 && col1 === col2) return;
            
            const piece1 = pieces.find(p => 
                parseInt(p.dataset.currentRow) === row1 && 
                parseInt(p.dataset.currentCol) === col1
            );
            const piece2 = pieces.find(p => 
                parseInt(p.dataset.currentRow) === row2 && 
                parseInt(p.dataset.currentCol) === col2
            );
            
            if (!piece1 || !piece2) return;
            
            // 交换位置数据
            piece1.dataset.currentRow = row2;
            piece1.dataset.currentCol = col2;
            piece2.dataset.currentRow = row1;
            piece2.dataset.currentCol = col1;
            
            // 更新位置
            const pieceSize = 400 / gridSize;
            piece1.style.left = col2 * pieceSize + 'px';
            piece1.style.top = row2 * pieceSize + 'px';
            piece2.style.left = col1 * pieceSize + 'px';
            piece2.style.top = row1 * pieceSize + 'px';
            
            // 检查是否正确
            checkPiecePosition(piece1);
            checkPiecePosition(piece2);
            
            moveCount++;
            updateStats();
            updateCompletionRate();
            
            // 检查游戏是否完成
            checkGameComplete();
        }
        
        // 检查拼图块位置
        function checkPiecePosition(piece) {
            const currentRow = parseInt(piece.dataset.currentRow);
            const currentCol = parseInt(piece.dataset.currentCol);
            const correctRow = parseInt(piece.dataset.correctRow);
            const correctCol = parseInt(piece.dataset.correctCol);
            
            if (currentRow === correctRow && currentCol === correctCol) {
                piece.classList.add('correct');
                piece.classList.remove('incorrect');
            } else {
                piece.classList.remove('correct');
                piece.classList.add('incorrect');
                
                // 移除错误标记
                setTimeout(() => {
                    piece.classList.remove('incorrect');
                }, 500);
            }
        }
        
        // 检查游戏是否完成
        function checkGameComplete() {
            const correctCount = pieces.filter(piece => {
                const currentRow = parseInt(piece.dataset.currentRow);
                const currentCol = parseInt(piece.dataset.currentCol);
                const correctRow = parseInt(piece.dataset.correctRow);
                const correctCol = parseInt(piece.dataset.correctCol);
                return currentRow === correctRow && currentCol === correctCol;
            }).length;
            
            if (correctCount === pieces.length) {
                gameComplete();
            }
        }
        
        // 游戏完成
        function gameComplete() {
            isGameComplete = true;
            stopTimer();
            
            // 显示成功模态框
            document.getElementById('finalMoves').textContent = moveCount;
            document.getElementById('finalTime').textContent = document.getElementById('timeElapsed').textContent;
            document.getElementById('finalDifficulty').textContent = document.getElementById('difficultyText').textContent;
            
            const modal = document.getElementById('successModal');
            modal.classList.add('show');
        }
        
        // 更新完成度
        function updateCompletionRate() {
            if (pieces.length === 0) return;
            
            const correctCount = pieces.filter(piece => {
                const currentRow = parseInt(piece.dataset.currentRow);
                const currentCol = parseInt(piece.dataset.currentCol);
                const correctRow = parseInt(piece.dataset.correctRow);
                const correctCol = parseInt(piece.dataset.correctCol);
                return currentRow === correctRow && currentCol === correctCol;
            }).length;
            
            const rate = Math.round((correctCount / pieces.length) * 100);
            document.getElementById('completionRate').textContent = rate + '%';
        }
        
        // 更改图片
        function changeImage() {
            const select = document.getElementById('imageSelect');
            currentImageId = select.value;
            loadImage();
            createPuzzle();
            resetStats();
        }
        
        // 更改难度
        function changeDifficulty() {
            const select = document.getElementById('difficultySelect');
            gridSize = parseInt(select.value);
            updateDifficultyText();
            createPuzzle();
            resetStats();
        }
        
        // 更新难度文本
        function updateDifficultyText() {
            const difficultyMap = {
                3: '简单',
                4: '中等',
                5: '困难',
                6: '专家'
            };
            document.getElementById('difficultyText').textContent = difficultyMap[gridSize];
        }
        
        // 开始新游戏
        function startNewGame() {
            createPuzzle();
            resetStats();
            closeSuccessModal();
        }
        
        // 显示提示
        function showHint() {
            // 随机显示一个正确位置的拼图块
            const incorrectPieces = pieces.filter(piece => {
                const currentRow = parseInt(piece.dataset.currentRow);
                const currentCol = parseInt(piece.dataset.currentCol);
                const correctRow = parseInt(piece.dataset.correctRow);
                const correctCol = parseInt(piece.dataset.correctCol);
                return currentRow !== correctRow || currentCol !== correctCol;
            });
            
            if (incorrectPieces.length > 0) {
                const randomPiece = incorrectPieces[Math.floor(Math.random() * incorrectPieces.length)];
                const correctRow = parseInt(randomPiece.dataset.correctRow);
                const correctCol = parseInt(randomPiece.dataset.correctCol);
                
                // 移动拼图块到正确位置
                const currentRow = parseInt(randomPiece.dataset.currentRow);
                const currentCol = parseInt(randomPiece.dataset.currentCol);
                
                const targetPiece = pieces.find(p => 
                    parseInt(p.dataset.currentRow) === correctRow && 
                    parseInt(p.dataset.currentCol) === correctCol
                );
                
                if (targetPiece) {
                    swapPieces(currentRow, currentCol, correctRow, correctCol);
                }
            }
        }
        
        // 重置统计信息
        function resetStats() {
            moveCount = 0;
            isGameComplete = false;
            selectedPiece = null;
            startTime = Date.now();
            
            document.getElementById('moveCount').textContent = '0';
            document.getElementById('completionRate').textContent = '0%';
            
            startTimer();
        }
        
        // 开始计时
        function startTimer() {
            if (timerInterval) clearInterval(timerInterval);
            
            timerInterval = setInterval(() => {
                const elapsed = Math.floor((Date.now() - startTime) / 1000);
                const minutes = Math.floor(elapsed / 60);
                const seconds = elapsed % 60;
                document.getElementById('timeElapsed').textContent = 
                    `${minutes.toString().padStart(2, '0')}:${seconds.toString().padStart(2, '0')}`;
            }, 1000);
        }
        
        // 停止计时
        function stopTimer() {
            if (timerInterval) {
                clearInterval(timerInterval);
                timerInterval = null;
            }
        }
        
        // 更新统计信息
        function updateStats() {
            document.getElementById('moveCount').textContent = moveCount;
        }
        
        // 关闭成功模态框
        function closeSuccessModal() {
            document.getElementById('successModal').classList.remove('show');
        }
        
        // 页面加载完成后初始化
        document.addEventListener('DOMContentLoaded', initGame);
    </script>
</body>
</html>
```

**AI辅助学习**:
- 💡 提示词: "HTML5拖拽API的详细使用方法和兼容性处理"
- 🔧 调试技巧: 使用console.log()跟踪拖拽事件，检查dataTransfer数据
- 📚 扩展阅读: 搜索"HTML5拖拽API完全指南"

**每日挑战**: 添加计时排行榜，或添加更多游戏模式（如旋转拼图、数字拼图等）

---

## 🌲 高级 (Day 21-25) - 现代前端技术

### Day 21: Vue.js 待办事项应用
**难度**: ⭐⭐⭐⭐  
**知识点**: Vue.js基础、组件化、响应式数据、事件处理
**项目描述**: 使用Vue.js重构待办事项应用，体验现代前端框架的魅力

**代码示例**:
```html
<!DOCTYPE html>
<html lang="zh-CN">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Vue.js 待办事项应用</title>
    <script src="https://cdn.jsdelivr.net/npm/vue@2.6.14/dist/vue.js"></script>
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }
        
        body {
            font-family: 'Arial', sans-serif;
            background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
            min-height: 100vh;
            padding: 2rem;
        }
        
        .container {
            max-width: 600px;
            margin: 0 auto;
        }
        
        .header {
            text-align: center;
            color: white;
            margin-bottom: 2rem;
        }
        
        .header h1 {
            font-size: 2.5rem;
            margin-bottom: 0.5rem;
        }
        
        .todo-app {
            background: white;
            border-radius: 20px;
            padding: 2rem;
            box-shadow: 0 10px 30px rgba(0,0,0,0.1);
        }
        
        .input-section {
            display: flex;
            gap: 10px;
            margin-bottom: 2rem;
        }
        
        .todo-input {
            flex: 1;
            padding: 15px;
            border: 2px solid #e1e5e9;
            border-radius: 10px;
            font-size: 16px;
            transition: border-color 0.3s ease;
        }
        
        .todo-input:focus {
            outline: none;
            border-color: #667eea;
        }
        
        .add-btn {
            background: #667eea;
            color: white;
            border: none;
            padding: 15px 25px;
            border-radius: 10px;
            cursor: pointer;
            font-size: 16px;
            transition: all 0.3s ease;
        }
        
        .add-btn:hover {
            background: #5a6fd8;
            transform: scale(1.05);
        }
        
        .stats {
            display: grid;
            grid-template-columns: repeat(3, 1fr);
            gap: 1rem;
            margin-bottom: 2rem;
            padding: 15px;
            background: #f8f9fa;
            border-radius: 10px;
        }
        
        .stat-item {
            text-align: center;
        }
        
        .stat-number {
            font-size: 1.5rem;
            font-weight: bold;
            color: #667eea;
        }
        
        .stat-label {
            font-size: 0.9rem;
            color: #666;
        }
        
        .filter-buttons {
            display: flex;
            gap: 10px;
            margin-bottom: 1rem;
        }
        
        .filter-btn {
            flex: 1;
            padding: 10px;
            border: 2px solid #e1e5e9;
            background: white;
            border-radius: 8px;
            cursor: pointer;
            transition: all 0.3s ease;
        }
        
        .filter-btn.active {
            background: #667eea;
            color: white;
            border-color: #667eea;
        }
        
        .todo-list {
            list-style: none;
        }
        
        .todo-item {
            display: flex;
            align-items: center;
            padding: 15px;
            background: #f8f9fa;
            border-radius: 10px;
            margin-bottom: 10px;
            transition: all 0.3s ease;
        }
        
        .todo-item:hover {
            background: #e9ecef;
        }
        
        .todo-item.completed {
            opacity: 0.6;
        }
        
        .todo-item.completed .todo-text {
            text-decoration: line-through;
        }
        
        .todo-checkbox {
            width: 20px;
            height: 20px;
            margin-right: 15px;
            cursor: pointer;
        }
        
        .todo-text {
            flex: 1;
            font-size: 16px;
        }
        
        .todo-priority {
            padding: 2px 8px;
            border-radius: 12px;
            font-size: 0.75rem;
            margin-right: 10px;
        }
        
        .priority-high {
            background: #f8d7da;
            color: #721c24;
        }
        
        .priority-medium {
            background: #fff3cd;
            color: #856404;
        }
        
        .priority-low {
            background: #d4edda;
            color: #155724;
        }
        
        .todo-actions {
            display: flex;
            gap: 5px;
        }
        
        .action-btn {
            background: none;
            border: none;
            padding: 5px 10px;
            cursor: pointer;
            border-radius: 5px;
            transition: background 0.2s ease;
            font-size: 14px;
        }
        
        .edit-btn {
            color: #28a745;
        }
        
        .edit-btn:hover {
            background: #d4edda;
        }
        
        .delete-btn {
            color: #dc3545;
        }
        
        .delete-btn:hover {
            background: #f8d7da;
        }
        
        .empty-state {
            text-align: center;
            padding: 40px;
            color: #666;
        }
        
        .empty-state-icon {
            font-size: 3rem;
            opacity: 0.5;
            margin-bottom: 15px;
        }
        
        .clear-completed {
            background: #dc3545;
            color: white;
            border: none;
            padding: 10px 20px;
            border-radius: 8px;
            cursor: pointer;
            margin-top: 1rem;
            width: 100%;
            font-size: 16px;
        }
        
        .clear-completed:hover {
            background: #c82333;
        }
        
        /* 编辑模式样式 */
        .todo-item.editing {
            background: #fff3cd;
        }
        
        .edit-input {
            flex: 1;
            padding: 8px;
            border: 2px solid #667eea;
            border-radius: 5px;
            font-size: 16px;
            margin-right: 10px;
        }
        
        .edit-input:focus {
            outline: none;
        }
        
        .priority-select {
            padding: 5px;
            border: 2px solid #e1e5e9;
            border-radius: 5px;
            margin-right: 10px;
        }
        
        /* 响应式设计 */
        @media (max-width: 768px) {
            .stats {
                grid-template-columns: 1fr;
            }
            
            .filter-buttons {
                flex-direction: column;
            }
            
            .todo-actions {
                flex-direction: column;
            }
        }
    </style>
</head>
<body>
    <div class="container">
        <div class="header">
            <h1>✅ Vue.js 待办事项</h1>
            <p>使用Vue.js构建的现代化待办应用</p>
        </div>
        
        <div class="todo-app" id="todoApp">
            <!-- 输入区域 -->
            <div class="input-section">
                <input type="text" class="todo-input" 
                       v-model="newTodoText" 
                       @keyup.enter="addTodo"
                       placeholder="添加新的待办事项...">
                <select v-model="newTodoPriority" class="todo-input" style="width: 120px;">
                    <option value="low">低优先级</option>
                    <option value="medium" selected>中优先级</option>
                    <option value="high">高优先级</option>
                </select>
                <button class="add-btn" @click="addTodo">添加</button>
            </div>
            
            <!-- 统计信息 -->
            <div class="stats">
                <div class="stat-item">
                    <div class="stat-number">{{ totalTodos }}</div>
                    <div class="stat-label">总计</div>
                </div>
                <div class="stat-item">
                    <div class="stat-number">{{ activeTodos }}</div>
                    <div class="stat-label">未完成</div>
                </div>
                <div class="stat-item">
                    <div class="stat-number">{{ completedTodos }}</div>
                    <div class="stat-label">已完成</div>
                </div>
            </div>
            
            <!-- 过滤器 -->
            <div class="filter-buttons">
                <button class="filter-btn" 
                        :class="{ active: filter === 'all' }"
                        @click="filter = 'all'">全部</button>
                <button class="filter-btn" 
                        :class="{ active: filter === 'active' }"
                        @click="filter = 'active'">未完成</button>
                <button class="filter-btn" 
                        :class="{ active: filter === 'completed' }"
                        @click="filter = 'completed'">已完成</button>
                <button class="filter-btn" 
                        :class="{ active: filter === 'high' }"
                        @click="filter = 'high'">高优先级</button>
            </div>
            
            <!-- 待办事项列表 -->
            <ul class="todo-list">
                <li v-for="todo in filteredTodos" 
                    :key="todo.id" 
                    class="todo-item" 
                    :class="{ completed: todo.completed, editing: todo.editing }">
                    
                    <input type="checkbox" 
                           class="todo-checkbox" 
                           v-model="todo.completed"
                           @change="saveTodos">
                    
                    <span class="todo-priority" 
                          :class="'priority-' + todo.priority"
                          v-if="!todo.editing">
                        {{ getPriorityText(todo.priority) }}
                    </span>
                    
                    <template v-if="!todo.editing">
                        <span class="todo-text">{{ todo.text }}</span>
                        
                        <div class="todo-actions">
                            <button class="action-btn edit-btn" @click="editTodo(todo)">编辑</button>
                            <button class="action-btn delete-btn" @click="deleteTodo(todo)">删除</button>
                        </div>
                    </template>
                    
                    <template v-else>
                        <input type="text" 
                               class="edit-input" 
                               v-model="todo.editText"
                               @keyup.enter="saveEdit(todo)"
                               @keyup.esc="cancelEdit(todo)">
                        <select class="priority-select" v-model="todo.editPriority">
                            <option value="low">低</option>
                            <option value="medium">中</option>
                            <option value="high">高</option>
                        </select>
                        <div class="todo-actions">
                            <button class="action-btn edit-btn" @click="saveEdit(todo)">保存</button>
                            <button class="action-btn delete-btn" @click="cancelEdit(todo)">取消</button>
                        </div>
                    </template>
                </li>
            </ul>
            
            <!-- 空状态 -->
            <div v-if="filteredTodos.length === 0" class="empty-state">
                <div class="empty-state-icon">📝</div>
                <h4>暂无待办事项</h4>
                <p>添加一个新的待办事项开始吧！</p>
            </div>
            
            <!-- 清除已完成 -->
            <button class="clear-completed" 
                    v-if="completedTodos > 0"
                    @click="clearCompleted">
                清除已完成 ({{ completedTodos }})
            </button>
        </div>
    </div>
    
    <script>
        // Vue 应用
        new Vue({
            el: '#todoApp',
            data: {
                newTodoText: '',
                newTodoPriority: 'medium',
                todos: [],
                filter: 'all',
                nextId: 1
            },
            
            computed: {
                // 计算属性：总待办事项数
                totalTodos() {
                    return this.todos.length;
                },
                
                // 计算属性：未完成待办事项数
                activeTodos() {
                    return this.todos.filter(todo => !todo.completed).length;
                },
                
                // 计算属性：已完成待办事项数
                completedTodos() {
                    return this.todos.filter(todo => todo.completed).length;
                },
                
                // 计算属性：过滤后的待办事项
                filteredTodos() {
                    let filtered = this.todos;
                    
                    switch(this.filter) {
                        case 'active':
                            filtered = this.todos.filter(todo => !todo.completed);
                            break;
                        case 'completed':
                            filtered = this.todos.filter(todo => todo.completed);
                            break;
                        case 'high':
                            filtered = this.todos.filter(todo => todo.priority === 'high');
                            break;
                    }
                    
                    // 按优先级排序
                    return filtered.sort((a, b) => {
                        const priorityOrder = { high: 3, medium: 2, low: 1 };
                        return priorityOrder[b.priority] - priorityOrder[a.priority];
                    });
                }
            },
            
            methods: {
                // 添加待办事项
                addTodo() {
                    if (this.newTodoText.trim() === '') return;
                    
                    const newTodo = {
                        id: this.nextId++,
                        text: this.newTodoText.trim(),
                        completed: false,
                        priority: this.newTodoPriority,
                        createdAt: new Date().toISOString(),
                        editing: false,
                        editText: '',
                        editPriority: 'medium'
                    };
                    
                    this.todos.unshift(newTodo);
                    this.newTodoText = '';
                    this.saveTodos();
                },
                
                // 删除待办事项
                deleteTodo(todo) {
                    const index = this.todos.findIndex(t => t.id === todo.id);
                    if (index > -1) {
                        this.todos.splice(index, 1);
                        this.saveTodos();
                    }
                },
                
                // 编辑待办事项
                editTodo(todo) {
                    todo.editing = true;
                    todo.editText = todo.text;
                    todo.editPriority = todo.priority;
                    
                    // 聚焦到输入框
                    this.$nextTick(() => {
                        const input = document.querySelector('.edit-input');
                        if (input) {
                            input.focus();
                            input.select();
                        }
                    });
                },
                
                // 保存编辑
                saveEdit(todo) {
                    if (todo.editText.trim() === '') return;
                    
                    todo.text = todo.editText.trim();
                    todo.priority = todo.editPriority;
                    todo.editing = false;
                    todo.editText = '';
                    
                    this.saveTodos();
                },
                
                // 取消编辑
                cancelEdit(todo) {
                    todo.editing = false;
                    todo.editText = '';
                },
                
                // 清除已完成的待办事项
                clearCompleted() {
                    this.todos = this.todos.filter(todo => !todo.completed);
                    this.saveTodos();
                },
                
                // 获取优先级文本
                getPriorityText(priority) {
                    const priorityMap = {
                        high: '高',
                        medium: '中',
                        low: '低'
                    };
                    return priorityMap[priority] || '中';
                },
                
                // 保存到本地存储
                saveTodos() {
                    localStorage.setItem('vueTodos', JSON.stringify({
                        todos: this.todos,
                        nextId: this.nextId
                    }));
                },
                
                // 从本地存储加载
                loadTodos() {
                    const saved = localStorage.getItem('vueTodos');
                    if (saved) {
                        const data = JSON.parse(saved);
                        this.todos = data.todos || [];
                        this.nextId = data.nextId || 1;
                    }
                }
            },
            
            // 生命周期钩子
            created() {
                this.loadTodos();
            },
            
            // 监听器
            watch: {
                // 监听待办事项变化，自动保存
                todos: {
                    handler() {
                        this.saveTodos();
                    },
                    deep: true
                }
            }
        });
    </script>
</body>
</html>
```

**AI辅助学习**:
- 💡 提示词: "Vue.js中computed和methods的区别，何时使用computed？"
- 🔧 调试技巧: 使用Vue开发者工具查看组件状态和数据流
- 📚 扩展阅读: 搜索"Vue.js官方文档教程"

**每日挑战**: 添加待办事项的分类管理，或集成Vuex进行状态管理

---

# 30天网页开发学习计划 - 第二部分 (Day 22-30)

## 🌲 高级 (Day 21-25) - 现代前端技术 (续)

### Day 22: React 天气应用
**难度**: ⭐⭐⭐⭐⭐  
**知识点**: React基础、组件化、Hooks、状态管理、副作用处理
**项目描述**: 使用React重新构建天气查询应用，学习组件化思维

**代码示例**:
```html
<!DOCTYPE html>
<html lang="zh-CN">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>React 天气应用</title>
    <script src="https://unpkg.com/react@18/umd/react.development.js"></script>
    <script src="https://unpkg.com/react-dom@18/umd/react-dom.development.js"></script>
    <script src="https://unpkg.com/@babel/standalone/babel.min.js"></script>
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }
        
        body {
            font-family: 'Arial', sans-serif;
            background: linear-gradient(135deg, #74b9ff 0%, #0984e3 100%);
            min-height: 100vh;
            padding: 2rem;
        }
        
        .container {
            max-width: 800px;
            margin: 0 auto;
        }
        
        .header {
            text-align: center;
            color: white;
            margin-bottom: 2rem;
        }
        
        .header h1 {
            font-size: 2.5rem;
            margin-bottom: 0.5rem;
        }
        
        .weather-app {
            background: white;
            border-radius: 20px;
            padding: 2rem;
            box-shadow: 0 10px 30px rgba(0,0,0,0.1);
        }
        
        .search-section {
            display: flex;
            gap: 15px;
            margin-bottom: 2rem;
        }
        
        .search-input {
            flex: 1;
            padding: 15px;
            border: 2px solid #e1e5e9;
            border-radius: 10px;
            font-size: 16px;
            transition: border-color 0.3s ease;
        }
        
        .search-input:focus {
            outline: none;
            border-color: #74b9ff;
        }
        
        .search-btn {
            background: #74b9ff;
            color: white;
            border: none;
            padding: 15px 30px;
            border-radius: 10px;
            cursor: pointer;
            font-size: 16px;
            transition: all 0.3s ease;
        }
        
        .search-btn:hover {
            background: #0984e3;
            transform: scale(1.05);
        }
        
        .location-btn {
            background: #00b894;
            color: white;
            border: none;
            padding: 15px 30px;
            border-radius: 10px;
            cursor: pointer;
            font-size: 16px;
            transition: all 0.3s ease;
        }
        
        .location-btn:hover {
            background: #00a085;
        }
        
        .weather-card {
            text-align: center;
            padding: 2rem;
            background: linear-gradient(135deg, #74b9ff 0%, #0984e3 100%);
            border-radius: 20px;
            color: white;
            margin-bottom: 2rem;
        }
        
        .city-name {
            font-size: 2rem;
            margin-bottom: 1rem;
        }
        
        .weather-icon {
            font-size: 4rem;
            margin: 1rem 0;
        }
        
        .temperature {
            font-size: 3rem;
            font-weight: bold;
            margin-bottom: 0.5rem;
        }
        
        .weather-description {
            font-size: 1.2rem;
            margin-bottom: 1rem;
        }
        
        .weather-details {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(150px, 1fr));
            gap: 1rem;
            margin-top: 2rem;
        }
        
        .detail-card {
            background: rgba(255, 255, 255, 0.1);
            padding: 1rem;
            border-radius: 10px;
            backdrop-filter: blur(10px);
        }
        
        .detail-icon {
            font-size: 1.5rem;
            margin-bottom: 0.5rem;
        }
        
        .detail-label {
            font-size: 0.9rem;
            opacity: 0.8;
            margin-bottom: 0.5rem;
        }
        
        .detail-value {
            font-size: 1.2rem;
            font-weight: bold;
        }
        
        .loading {
            text-align: center;
            padding: 40px;
        }
        
        .spinner {
            border: 4px solid #f3f3f3;
            border-top: 4px solid #74b9ff;
            border-radius: 50%;
            width: 40px;
            height: 40px;
            animation: spin 1s linear infinite;
            margin: 0 auto 1rem;
        }
        
        @keyframes spin {
            0% { transform: rotate(0deg); }
            100% { transform: rotate(360deg); }
        }
        
        .error-message {
            background: #f8d7da;
            color: #721c24;
            padding: 15px;
            border-radius: 10px;
            margin-top: 1rem;
            border: 1px solid #f5c6cb;
        }
        
        .empty-state {
            text-align: center;
            padding: 60px 20px;
            color: #666;
        }
        
        .empty-state-icon {
            font-size: 4rem;
            margin-bottom: 1rem;
            opacity: 0.5;
        }
        
        .recent-searches {
            margin-top: 1rem;
        }
        
        .recent-searches h4 {
            color: #666;
            margin-bottom: 0.5rem;
        }
        
        .recent-list {
            display: flex;
            gap: 10px;
            flex-wrap: wrap;
        }
        
        .recent-item {
            background: #f8f9fa;
            padding: 5px 15px;
            border-radius: 20px;
            font-size: 14px;
            color: #666;
            cursor: pointer;
            transition: all 0.2s ease;
        }
        
        .recent-item:hover {
            background: #74b9ff;
            color: white;
        }
    </style>
</head>
<body>
    <div class="container">
        <div class="header">
            <h1>🌤️ React 天气应用</h1>
            <p>使用React构建的现代天气查询应用</p>
        </div>
        
        <div class="weather-app">
            <div id="root"></div>
        </div>
    </div>
    
    <script type="text/babel">
        const { useState, useEffect, useCallback } = React;
        
        // 天气图标映射
        const weatherIcons = {
            'clear sky': '☀️',
            'few clouds': '🌤️',
            'scattered clouds': '⛅',
            'broken clouds': '☁️',
            'shower rain': '🌦️',
            'rain': '🌧️',
            'thunderstorm': '⛈️',
            'snow': '🌨️',
            'mist': '🌫️'
        };
        
        // 搜索组件
        function SearchSection({ onSearch, onLocationSearch, searchTerm, setSearchTerm }) {
            const handleSubmit = (e) => {
                e.preventDefault();
                if (searchTerm.trim()) {
                    onSearch(searchTerm.trim());
                }
            };
            
            return (
                <form className="search-section" onSubmit={handleSubmit}>
                    <input 
                        type="text" 
                        className="search-input" 
                        placeholder="输入城市名称（如：北京、上海、广州）"
                        value={searchTerm}
                        onChange={(e) => setSearchTerm(e.target.value)}
                    />
                    <button type="submit" className="search-btn">搜索</button>
                    <button type="button" className="location-btn" onClick={onLocationSearch}>
                        📍 定位
                    </button>
                </form>
            );
        }
        
        // 天气卡片组件
        function WeatherCard({ weather }) {
            if (!weather) return null;
            
            const icon = weatherIcons[weather.description.toLowerCase()] || '🌡️';
            
            return (
                <div className="weather-card">
                    <h2 className="city-name">{weather.name}</h2>
                    <div className="weather-icon">{icon}</div>
                    <div className="temperature">{Math.round(weather.main.temp)}°C</div>
                    <div className="weather-description">{weather.description}</div>
                    
                    <div className="weather-details">
                        <div className="detail-card">
                            <div className="detail-icon">💧</div>
                            <div className="detail-label">湿度</div>
                            <div className="detail-value">{weather.main.humidity}%</div>
                        </div>
                        
                        <div className="detail-card">
                            <div className="detail-icon">💨</div>
                            <div className="detail-label">风速</div>
                            <div className="detail-value">{weather.wind.speed} m/s</div>
                        </div>
                        
                        <div className="detail-card">
                            <div className="detail-icon">👁️</div>
                            <div className="detail-label">能见度</div>
                            <div className="detail-value">{(weather.visibility / 1000).toFixed(1)} km</div>
                        </div>
                        
                        <div className="detail-card">
                            <div className="detail-icon">🌡️</div>
                            <div className="detail-label">体感温度</div>
                            <div className="detail-value">{Math.round(weather.main.feels_like)}°C</div>
                        </div>
                        
                        <div className="detail-card">
                            <div className="detail-icon">🔵</div>
                            <div className="detail-label">气压</div>
                            <div className="detail-value">{weather.main.pressure} hPa</div>
                        </div>
                        
                        <div className="detail-card">
                            <div className="detail-icon">🌅</div>
                            <div className="detail-label">紫外线</div>
                            <div className="detail-value">中等</div>
                        </div>
                    </div>
                </div>
            );
        }
        
        // 最近搜索组件
        function RecentSearches({ searches, onSearch }) {
            if (searches.length === 0) return null;
            
            return (
                <div className="recent-searches">
                    <h4>最近搜索：</h4>
                    <div className="recent-list">
                        {searches.map((city, index) => (
                            <span 
                                key={index} 
                                className="recent-item"
                                onClick={() => onSearch(city)}
                            >
                                {city}
                            </span>
                        ))}
                    </div>
                </div>
            );
        }
        
        // 主应用组件
        function WeatherApp() {
            const [weather, setWeather] = useState(null);
            const [loading, setLoading] = useState(false);
            const [error, setError] = useState(null);
            const [searchTerm, setSearchTerm] = useState('');
            const [recentSearches, setRecentSearches] = useState([]);
            
            // 从本地存储加载最近搜索
            useEffect(() => {
                const saved = localStorage.getItem('reactWeatherSearches');
                if (saved) {
                    setRecentSearches(JSON.parse(saved));
                }
            }, []);
            
            // 保存到本地存储
            const saveRecentSearch = useCallback((city) => {
                setRecentSearches(prev => {
                    const updated = [city, ...prev.filter(c => c !== city)].slice(0, 10);
                    localStorage.setItem('reactWeatherSearches', JSON.stringify(updated));
                    return updated;
                });
            }, []);
            
            // 模拟获取天气数据
            const fetchWeather = useCallback(async (city) => {
                setLoading(true);
                setError(null);
                
                try {
                    // 模拟API延迟
                    await new Promise(resolve => setTimeout(resolve, 1000));
                    
                    // 模拟天气数据
                    const mockWeather = {
                        name: city,
                        main: {
                            temp: 15 + Math.random() * 20,
                            feels_like: 17 + Math.random() * 15,
                            humidity: 40 + Math.random() * 40,
                            pressure: 1000 + Math.random() * 30
                        },
                        weather: [{
                            description: 'clear sky',
                            icon: '01d'
                        }],
                        wind: {
                            speed: 2 + Math.random() * 8
                        },
                        visibility: 8000 + Math.random() * 4000
                    };
                    
                    setWeather(mockWeather);
                    saveRecentSearch(city);
                } catch (err) {
                    setError('获取天气信息失败，请检查城市名称或网络连接');
                } finally {
                    setLoading(false);
                }
            }, [saveRecentSearch]);
            
            // 搜索天气
            const handleSearch = useCallback((city) => {
                setSearchTerm(city);
                fetchWeather(city);
            }, [fetchWeather]);
            
            // 获取当前位置
            const handleLocationSearch = useCallback(() => {
                if (!navigator.geolocation) {
                    setError('您的浏览器不支持地理定位功能');
                    return;
                }
                
                setLoading(true);
                navigator.geolocation.getCurrentPosition(
                    () => {
                        fetchWeather('当前位置');
                    },
                    () => {
                        setError('无法获取您的位置信息，请手动输入城市名称');
                        setLoading(false);
                    }
                );
            }, [fetchWeather]);
            
            // 初始加载
            useEffect(() => {
                fetchWeather('Beijing');
            }, [fetchWeather]);
            
            return (
                <div>
                    <SearchSection 
                        onSearch={handleSearch}
                        onLocationSearch={handleLocationSearch}
                        searchTerm={searchTerm}
                        setSearchTerm={setSearchTerm}
                    />
                    
                    {error && <div className="error-message">{error}</div>}
                    
                    {loading && (
                        <div className="loading">
                            <div className="spinner"></div>
                            <p>正在获取天气信息...</p>
                        </div>
                    )}
                    
                    {weather && !loading && <WeatherCard weather={weather} />}
                    
                    <RecentSearches 
                        searches={recentSearches} 
                        onSearch={handleSearch} 
                    />
                </div>
            );
        }
        
        // 渲染应用
        ReactDOM.render(<WeatherApp />, document.getElementById('root'));
    </script>
</body>
</html>
```

**AI辅助学习**:
- 💡 提示词: "React Hooks的使用规则和最佳实践，useEffect的依赖数组如何正确设置？"
- 🔧 调试技巧: 使用React开发者工具查看组件树和状态变化
- 📚 扩展阅读: 搜索"React官方文档Hooks指南"

**每日挑战**: 添加自定义Hook（如useLocalStorage），或添加错误边界处理

---

### Day 23: 响应式图片网格
**难度**: ⭐⭐⭐⭐  
**知识点**: CSS Grid、Flexbox、响应式设计、图片懒加载
**项目描述**: 创建一个响应式的图片网格布局，支持多种布局和懒加载

**代码示例**:
```html
<!DOCTYPE html>
<html lang="zh-CN">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>响应式图片网格</title>
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }
        
        body {
            font-family: 'Arial', sans-serif;
            background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
            min-height: 100vh;
            padding: 2rem;
        }
        
        .container {
            max-width: 1400px;
            margin: 0 auto;
        }
        
        .header {
            text-align: center;
            color: white;
            margin-bottom: 2rem;
        }
        
        .header h1 {
            font-size: 2.5rem;
            margin-bottom: 0.5rem;
        }
        
        .controls {
            background: white;
            border-radius: 20px;
            padding: 2rem;
            margin-bottom: 2rem;
            box-shadow: 0 10px 30px rgba(0,0,0,0.1);
        }
        
        .controls-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(200px, 1fr));
            gap: 2rem;
            align-items: end;
        }
        
        .control-group {
            display: flex;
            flex-direction: column;
        }
        
        .control-label {
            font-weight: bold;
            color: #333;
            margin-bottom: 0.5rem;
        }
        
        .control-select, .control-input {
            padding: 12px;
            border: 2px solid #e1e5e9;
            border-radius: 8px;
            font-size: 16px;
            background: white;
            cursor: pointer;
            transition: border-color 0.3s ease;
        }
        
        .control-select:focus, .control-input:focus {
            outline: none;
            border-color: #667eea;
        }
        
        .control-btn {
            background: #667eea;
            color: white;
            border: none;
            padding: 12px 24px;
            border-radius: 8px;
            cursor: pointer;
            font-size: 16px;
            transition: all 0.3s ease;
        }
        
        .control-btn:hover {
            background: #5a6fd8;
            transform: scale(1.05);
        }
        
        .gallery-container {
            background: white;
            border-radius: 20px;
            padding: 2rem;
            box-shadow: 0 10px 30px rgba(0,0,0,0.1);
        }
        
        .gallery-header {
            display: flex;
            justify-content: space-between;
            align-items: center;
            margin-bottom: 2rem;
            padding-bottom: 1rem;
            border-bottom: 2px solid #e1e5e9;
        }
        
        .gallery-title {
            font-size: 1.5rem;
            font-weight: bold;
            color: #333;
        }
        
        .gallery-stats {
            display: flex;
            gap: 2rem;
            color: #666;
        }
        
        .gallery-grid {
            display: grid;
            gap: 20px;
            transition: all 0.3s ease;
        }
        
        /* 不同的网格布局 */
        .gallery-grid.masonry {
            grid-template-columns: repeat(auto-fill, minmax(300px, 1fr));
            grid-auto-rows: 10px;
        }
        
        .gallery-grid.flexible {
            display: flex;
            flex-wrap: wrap;
            gap: 20px;
        }
        
        .gallery-grid.uniform {
            grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
        }
        
        .gallery-grid.columns-2 {
            grid-template-columns: repeat(2, 1fr);
        }
        
        .gallery-grid.columns-3 {
            grid-template-columns: repeat(3, 1fr);
        }
        
        .gallery-grid.columns-4 {
            grid-template-columns: repeat(4, 1fr);
        }
        
        .image-item {
            position: relative;
            overflow: hidden;
            border-radius: 10px;
            cursor: pointer;
            transition: all 0.3s ease;
            background: #f8f9fa;
        }
        
        .gallery-grid.masonry .image-item {
            grid-row-end: span var(--span, 30);
        }
        
        .gallery-grid.flexible .image-item {
            flex: 1 1 300px;
            max-width: calc(33.333% - 14px);
        }
        
        .image-item:hover {
            transform: translateY(-5px);
            box-shadow: 0 10px 30px rgba(0,0,0,0.2);
        }
        
        .image-item img {
            width: 100%;
            height: 100%;
            object-fit: cover;
            transition: transform 0.3s ease;
        }
        
        .image-item:hover img {
            transform: scale(1.05);
        }
        
        .image-overlay {
            position: absolute;
            bottom: 0;
            left: 0;
            right: 0;
            background: linear-gradient(transparent, rgba(0,0,0,0.8));
            color: white;
            padding: 20px;
            transform: translateY(100%);
            transition: transform 0.3s ease;
        }
        
        .image-item:hover .image-overlay {
            transform: translateY(0);
        }
        
        .image-title {
            font-size: 1.1rem;
            font-weight: bold;
            margin-bottom: 0.5rem;
        }
        
        .image-description {
            font-size: 0.9rem;
            opacity: 0.9;
        }
        
        .image-meta {
            display: flex;
            justify-content: space-between;
            align-items: center;
            margin-top: 0.5rem;
            font-size: 0.8rem;
            opacity: 0.8;
        }
        
        /* 加载动画 */
        .loading-spinner {
            text-align: center;
            padding: 40px;
        }
        
        .spinner {
            border: 4px solid #f3f3f3;
            border-top: 4px solid #667eea;
            border-radius: 50%;
            width: 40px;
            height: 40px;
            animation: spin 1s linear infinite;
            margin: 0 auto;
        }
        
        @keyframes spin {
            0% { transform: rotate(0deg); }
            100% { transform: rotate(360deg); }
        }
        
        /* 图片懒加载 */
        .image-item img {
            opacity: 0;
            transition: opacity 0.3s ease;
        }
        
        .image-item img.loaded {
            opacity: 1;
        }
        
        .image-item.loading::before {
            content: '';
            position: absolute;
            top: 0;
            left: 0;
            right: 0;
            bottom: 0;
            background: linear-gradient(90deg, #f0f0f0 25%, #e0e0e0 50%, #f0f0f0 75%);
            background-size: 200% 100%;
            animation: loading 1.5s infinite;
        }
        
        @keyframes loading {
            0% { background-position: 200% 0; }
            100% { background-position: -200% 0; }
        }
        
        /* 响应式设计 */
        @media (max-width: 768px) {
            .controls-grid {
                grid-template-columns: 1fr;
            }
            
            .gallery-grid.columns-2,
            .gallery-grid.columns-3,
            .gallery-grid.columns-4 {
                grid-template-columns: 1fr;
            }
            
            .gallery-grid.flexible .image-item {
                max-width: 100%;
            }
            
            .gallery-header {
                flex-direction: column;
                gap: 1rem;
            }
            
            .gallery-stats {
                justify-content: center;
            }
        }
        
        @media (max-width: 480px) {
            body {
                padding: 1rem;
            }
            
            .controls,
            .gallery-container {
                padding: 1rem;
            }
        }
    </style>
</head>
<body>
    <div class="container">
        <div class="header">
            <h1>🖼️ 响应式图片网格</h1>
            <p>灵活的图片展示解决方案</p>
        </div>
        
        <div class="controls">
            <div class="controls-grid">
                <div class="control-group">
                    <label class="control-label">布局模式</label>
                    <select class="control-select" id="layoutMode">
                        <option value="masonry">瀑布流布局</option>
                        <option value="flexible">弹性布局</option>
                        <option value="uniform" selected>统一网格</option>
                        <option value="columns-2">2列布局</option>
                        <option value="columns-3">3列布局</option>
                        <option value="columns-4">4列布局</option>
                    </select>
                </div>
                
                <div class="control-group">
                    <label class="control-label">图片数量</label>
                    <input type="number" class="control-input" id="imageCount" min="10" max="100" value="30">
                </div>
                
                <div class="control-group">
                    <label class="control-label">图片分类</label>
                    <select class="control-select" id="imageCategory">
                        <option value="nature">自然风景</option>
                        <option value="city">城市建筑</option>
                        <option value="people">人物肖像</option>
                        <option value="tech">科技产品</option>
                        <option value="animals">动物世界</option>
                    </select>
                </div>
                
                <div class="control-group">
                    <button class="control-btn" onclick="reloadGallery()">重新加载</button>
                </div>
            </div>
        </div>
        
        <div class="gallery-container">
            <div class="gallery-header">
                <h3 class="gallery-title">图片画廊</h3>
                <div class="gallery-stats">
                    <span>总计: <strong id="totalImages">0</strong></span>
                    <span>已加载: <strong id="loadedImages">0</strong></span>
                </div>
            </div>
            
            <div class="gallery-grid uniform" id="galleryGrid">
                <!-- 图片将在这里动态生成 -->
            </div>
            
            <div class="loading-spinner" id="loadingSpinner" style="display: none;">
                <div class="spinner"></div>
                <p>正在加载更多图片...</p>
            </div>
        </div>
    </div>
    
    <script>
        // 图片数据生成器
        class ImageGenerator {
            constructor() {
                this.categories = {
                    nature: ['mountain', 'forest', 'beach', 'sunset', 'waterfall', 'lake', 'garden', 'sky'],
                    city: ['skyline', 'street', 'building', 'bridge', 'tower', 'plaza', 'avenue', 'downtown'],
                    people: ['portrait', 'group', 'family', 'worker', 'student', 'artist', 'athlete', 'chef'],
                    tech: ['computer', 'phone', 'robot', 'drone', 'circuit', 'network', 'code', 'data'],
                    animals: ['cat', 'dog', 'bird', 'lion', 'elephant', 'dolphin', 'butterfly', 'horse']
                };
            }
            
            generateImage(category, index) {
                const keywords = this.categories[category] || this.categories.nature;
                const keyword = keywords[index % keywords.length];
                const width = 300 + Math.floor(Math.random() * 200);
                const height = 200 + Math.floor(Math.random() * 300);
                
                return {
                    id: Date.now() + index,
                    url: `https://picsum.photos/${width}/${height}?random=${index}&blur=0`,
                    title: `${keyword.charAt(0).toUpperCase() + keyword.slice(1)} Image ${index + 1}`,
                    description: `Beautiful ${keyword} photography with high quality and stunning colors.`,
                    width,
                    height,
                    aspectRatio: width / height
                };
            }
            
            generateImages(category, count) {
                const images = [];
                for (let i = 0; i < count; i++) {
                    images.push(this.generateImage(category, i));
                }
                return images;
            }
        }
        
        // 画廊管理器
        class GalleryManager {
            constructor() {
                this.generator = new ImageGenerator();
                this.images = [];
                this.loadedCount = 0;
                this.observer = null;
                this.init();
            }
            
            init() {
                this.setupIntersectionObserver();
                this.reloadGallery();
            }
            
            setupIntersectionObserver() {
                const options = {
                    root: null,
                    rootMargin: '50px',
                    threshold: 0.1
                };
                
                this.observer = new IntersectionObserver((entries) => {
                    entries.forEach(entry => {
                        if (entry.isIntersecting) {
                            const img = entry.target;
                            this.loadImage(img);
                            this.observer.unobserve(img);
                        }
                    });
                }, options);
            }
            
            loadImage(imgElement) {
                const src = imgElement.dataset.src;
                if (!src) return;
                
                imgElement.src = src;
                imgElement.classList.add('loaded');
                imgElement.parentElement.classList.remove('loading');
                
                imgElement.onload = () => {
                    this.loadedCount++;
                    this.updateStats();
                };
            }
            
            reloadGallery() {
                const layoutMode = document.getElementById('layoutMode').value;
                const imageCount = parseInt(document.getElementById('imageCount').value);
                const category = document.getElementById('imageCategory').value;
                
                this.images = this.generator.generateImages(category, imageCount);
                this.loadedCount = 0;
                this.renderGallery(layoutMode);
                this.updateStats();
            }
            
            renderGallery(layoutMode) {
                const grid = document.getElementById('galleryGrid');
                grid.className = `gallery-grid ${layoutMode}`;
                grid.innerHTML = '';
                
                this.images.forEach((image, index) => {
                    const imageElement = this.createImageElement(image, index);
                    grid.appendChild(imageElement);
                });
                
                // 重新观察图片
                this.observeImages();
            }
            
            createImageElement(image, index) {
                const item = document.createElement('div');
                item.className = 'image-item loading';
                
                // 计算不同布局的高度
                let itemHeight = 'auto';
                if (document.getElementById('layoutMode').value === 'masonry') {
                    const baseHeight = Math.max(200, Math.min(400, image.height / 2));
                    itemHeight = `${baseHeight}px`;
                    item.style.setProperty('--span', Math.floor(baseHeight / 10));
                }
                
                item.innerHTML = `
                    <img data-src="${image.url}" alt="${image.title}" style="height: ${itemHeight}">
                    <div class="image-overlay">
                        <h4 class="image-title">${image.title}</h4>
                        <p class="image-description">${image.description}</p>
                        <div class="image-meta">
                            <span>${image.width}×${image.height}</span>
                            <span>图片 ${index + 1}</span>
                        </div>
                    </div>
                `;
                
                return item;
            }
            
            observeImages() {
                const images = document.querySelectorAll('.image-item img');
                images.forEach(img => {
                    this.observer.observe(img);
                });
            }
            
            updateStats() {
                document.getElementById('totalImages').textContent = this.images.length;
                document.getElementById('loadedImages').textContent = this.loadedCount;
            }
        }
        
        // 初始化画廊
        let galleryManager;
        
        function reloadGallery() {
            galleryManager.reloadGallery();
        }
        
        // 布局模式切换
        document.getElementById('layoutMode').addEventListener('change', function() {
            const grid = document.getElementById('galleryGrid');
            grid.className = `gallery-grid ${this.value}`;
            
            // 重新渲染以适应新布局
            galleryManager.renderGallery(this.value);
        });
        
        // 页面加载完成后初始化
        document.addEventListener('DOMContentLoaded', function() {
            galleryManager = new GalleryManager();
        });
        
        // 滚动加载更多
        window.addEventListener('scroll', function() {
            if ((window.innerHeight + window.scrollY) >= document.body.offsetHeight - 1000) {
                // 可以在这里实现加载更多功能
            }
        });
    </script>
</body>
</html>
```

**AI辅助学习**:
- 💡 提示词: "Intersection Observer API的使用方法和性能优势"
- 🔧 调试技巧: 使用浏览器开发者工具观察图片加载和网络请求
- 📚 扩展阅读: 搜索"图片懒加载最佳实践"

**每日挑战**: 添加图片灯箱效果，或实现无限滚动加载

---

### Day 24: CSS动画与过渡效果库
**难度**: ⭐⭐⭐⭐  
**知识点**: CSS动画、关键帧、过渡效果、JavaScript控制
**项目描述**: 创建一个CSS动画效果展示库，包含各种实用动画效果

**代码示例**:
```html
<!DOCTYPE html>
<html lang="zh-CN">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>CSS动画效果库</title>
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }
        
        body {
            font-family: 'Arial', sans-serif;
            background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
            min-height: 100vh;
            padding: 2rem;
        }
        
        .container {
            max-width: 1400px;
            margin: 0 auto;
        }
        
        .header {
            text-align: center;
            color: white;
            margin-bottom: 2rem;
        }
        
        .header h1 {
            font-size: 2.5rem;
            margin-bottom: 0.5rem;
        }
        
        .controls {
            background: white;
            border-radius: 20px;
            padding: 2rem;
            margin-bottom: 2rem;
            box-shadow: 0 10px 30px rgba(0,0,0,0.1);
        }
        
        .control-section {
            margin-bottom: 2rem;
        }
        
        .control-section h3 {
            color: #333;
            margin-bottom: 1rem;
        }
        
        .control-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(200px, 1fr));
            gap: 1rem;
        }
        
        .control-item {
            display: flex;
            flex-direction: column;
            gap: 0.5rem;
        }
        
        .control-label {
            font-weight: 500;
            color: #333;
        }
        
        .control-input {
            padding: 8px;
            border: 2px solid #e1e5e9;
            border-radius: 5px;
            font-size: 14px;
        }
        
        .control-input:focus {
            outline: none;
            border-color: #667eea;
        }
        
        .control-btn {
            background: #667eea;
            color: white;
            border: none;
            padding: 8px 16px;
            border-radius: 5px;
            cursor: pointer;
            font-size: 14px;
            transition: all 0.3s ease;
        }
        
        .control-btn:hover {
            background: #5a6fd8;
        }
        
        .animation-showcase {
            background: white;
            border-radius: 20px;
            padding: 2rem;
            box-shadow: 0 10px 30px rgba(0,0,0,0.1);
        }
        
        .showcase-header {
            display: flex;
            justify-content: space-between;
            align-items: center;
            margin-bottom: 2rem;
            padding-bottom: 1rem;
            border-bottom: 2px solid #e1e5e9;
        }
        
        .showcase-title {
            font-size: 1.5rem;
            font-weight: bold;
            color: #333;
        }
        
        .showcase-controls {
            display: flex;
            gap: 10px;
        }
        
        .demo-btn {
            background: #28a745;
            color: white;
            border: none;
            padding: 10px 20px;
            border-radius: 8px;
            cursor: pointer;
            font-size: 16px;
            transition: all 0.3s ease;
        }
        
        .demo-btn:hover {
            background: #218838;
            transform: scale(1.05);
        }
        
        .demo-btn.stop {
            background: #dc3545;
        }
        
        .demo-btn.stop:hover {
            background: #c82333;
        }
        
        .animation-stage {
            min-height: 400px;
            background: #f8f9fa;
            border-radius: 15px;
            display: flex;
            align-items: center;
            justify-content: center;
            position: relative;
            overflow: hidden;
        }
        
        .demo-element {
            width: 100px;
            height: 100px;
            background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
            border-radius: 10px;
            display: flex;
            align-items: center;
            justify-content: center;
            color: white;
            font-size: 2rem;
            font-weight: bold;
            cursor: pointer;
            transition: all 0.3s ease;
        }
        
        .animation-list {
            display: grid;
            grid-template-columns: repeat(auto-fill, minmax(300px, 1fr));
            gap: 1rem;
            margin-top: 2rem;
        }
        
        .animation-item {
            background: #f8f9fa;
            border: 2px solid #e1e5e9;
            border-radius: 10px;
            padding: 1.5rem;
            cursor: pointer;
            transition: all 0.3s ease;
        }
        
        .animation-item:hover {
            border-color: #667eea;
            background: #f0f4ff;
        }
        
        .animation-item.active {
            border-color: #667eea;
            background: #667eea;
            color: white;
        }
        
        .animation-name {
            font-size: 1.1rem;
            font-weight: bold;
            margin-bottom: 0.5rem;
        }
        
        .animation-description {
            font-size: 0.9rem;
            opacity: 0.8;
        }
        
        /* 基础动画类 */
        .animate-bounce {
            animation: bounce 1s infinite;
        }
        
        @keyframes bounce {
            0%, 20%, 53%, 80%, 100% { transform: translateY(0); }
            40%, 43% { transform: translateY(-30px); }
            70% { transform: translateY(-15px); }
            90% { transform: translateY(-4px); }
        }
        
        .animate-pulse {
            animation: pulse 2s infinite;
        }
        
        @keyframes pulse {
            0% { transform: scale(1); }
            50% { transform: scale(1.1); }
            100% { transform: scale(1); }
        }
        
        .animate-rotate {
            animation: rotate 2s linear infinite;
        }
        
        @keyframes rotate {
            from { transform: rotate(0deg); }
            to { transform: rotate(360deg); }
        }
        
        .animate-shake {
            animation: shake 0.5s ease-in-out;
        }
        
        @keyframes shake {
            0%, 100% { transform: translateX(0); }
            10%, 30%, 50%, 70%, 90% { transform: translateX(-10px); }
            20%, 40%, 60%, 80% { transform: translateX(10px); }
        }
        
        .animate-fade-in {
            animation: fadeIn 1s ease-in;
        }
        
        @keyframes fadeIn {
            from { opacity: 0; transform: translateY(20px); }
            to { opacity: 1; transform: translateY(0); }
        }
        
        .animate-slide-in {
            animation: slideIn 1s ease-out;
        }
        
        @keyframes slideIn {
            from { transform: translateX(-100%); }
            to { transform: translateX(0); }
        }
        
        .animate-flip {
            animation: flip 1s ease-in-out;
        }
        
        @keyframes flip {
            0% { transform: perspective(400px) rotateY(0); }
            50% { transform: perspective(400px) rotateY(180deg); }
            100% { transform: perspective(400px) rotateY(360deg); }
        }
        
        .animate-wobble {
            animation: wobble 1s ease-in-out;
        }
        
        @keyframes wobble {
            0% { transform: translateX(0%); }
            15% { transform: translateX(-25%) rotate(-5deg); }
            30% { transform: translateX(20%) rotate(3deg); }
            45% { transform: translateX(-15%) rotate(-3deg); }
            60% { transform: translateX(10%) rotate(2deg); }
            75% { transform: translateX(-5%) rotate(-1deg); }
            100% { transform: translateX(0%); }
        }
        
        .animate-jello {
            animation: jello 1s ease-in-out;
        }
        
        @keyframes jello {
            0%, 100% { transform: scale3d(1, 1, 1); }
            30% { transform: scale3d(1.25, 0.75, 1); }
            40% { transform: scale3d(0.75, 1.25, 1); }
            50% { transform: scale3d(1.15, 0.85, 1); }
            65% { transform: scale3d(0.95, 1.05, 1); }
            75% { transform: scale3d(1.05, 0.95, 1); }
        }
        
        .animate-heartbeat {
            animation: heartbeat 1.5s ease-in-out infinite;
        }
        
        @keyframes heartbeat {
            0% { transform: scale(1); }
            14% { transform: scale(1.3); }
            28% { transform: scale(1); }
            42% { transform: scale(1.3); }
            70% { transform: scale(1); }
        }
        
        .animate-rubber-band {
            animation: rubberBand 1s ease-in-out;
        }
        
        @keyframes rubberBand {
            0% { transform: scale(1); }
            30% { transform: scaleX(1.25) scaleY(0.75); }
            40% { transform: scaleX(0.75) scaleY(1.25); }
            50% { transform: scaleX(1.15) scaleY(0.85); }
            65% { transform: scaleX(0.95) scaleY(1.05); }
            75% { transform: scaleX(1.05) scaleY(0.95); }
            100% { transform: scale(1); }
        }
        
        .animate-swing {
            animation: swing 1s ease-in-out;
        }
        
        @keyframes swing {
            20% { transform: rotate3d(0, 0, 1, 15deg); }
            40% { transform: rotate3d(0, 0, 1, -10deg); }
            60% { transform: rotate3d(0, 0, 1, 5deg); }
            80% { transform: rotate3d(0, 0, 1, -5deg); }
            100% { transform: rotate3d(0, 0, 1, 0deg); }
        }
        
        .animate-tada {
            animation: tada 1s ease-in-out;
        }
        
        @keyframes tada {
            0% { transform: scale(1); }
            10%, 20% { transform: scale(0.9) rotate(-3deg); }
            30%, 50%, 70%, 90% { transform: scale(1.1) rotate(3deg); }
            40%, 60%, 80% { transform: scale(1.1) rotate(-3deg); }
            100% { transform: scale(1) rotate(0); }
        }
        
        /* 自定义动画 */
        .animate-morphing {
            animation: morphing 2s ease-in-out infinite;
        }
        
        @keyframes morphing {
            0% { border-radius: 10px; transform: scale(1) rotate(0deg); }
            25% { border-radius: 50%; transform: scale(1.2) rotate(90deg); }
            50% { border-radius: 0; transform: scale(0.8) rotate(180deg); }
            75% { border-radius: 50%; transform: scale(1.2) rotate(270deg); }
            100% { border-radius: 10px; transform: scale(1) rotate(360deg); }
        }
        
        .animate-glow {
            animation: glow 2s ease-in-out infinite alternate;
        }
        
        @keyframes glow {
            from { box-shadow: 0 0 10px rgba(102, 126, 234, 0.5); }
            to { box-shadow: 0 0 30px rgba(102, 126, 234, 1), 0 0 40px rgba(102, 126, 234, 0.8); }
        }
        
        .animate-float {
            animation: float 3s ease-in-out infinite;
        }
        
        @keyframes float {
            0%, 100% { transform: translateY(0px); }
            50% { transform: translateY(-20px); }
        }
        
        /* 响应式设计 */
        @media (max-width: 768px) {
            .animation-list {
                grid-template-columns: 1fr;
            }
            
            .showcase-header {
                flex-direction: column;
                gap: 1rem;
            }
            
            .showcase-controls {
                width: 100%;
                justify-content: center;
            }
        }
    </style>
</head>
<body>
    <div class="container">
        <div class="header">
            <h1>✨ CSS动画效果库</h1>
            <p>丰富多样的CSS动画效果展示</p>
        </div>
        
        <div class="controls">
            <div class="control-section">
                <h3>动画控制</h3>
                <div class="control-grid">
                    <div class="control-item">
                        <label class="control-label">动画时长 (秒)</label>
                        <input type="range" class="control-input" id="duration" min="0.5" max="5" step="0.1" value="1">
                        <span id="durationValue">1.0s</span>
                    </div>
                    
                    <div class="control-item">
                        <label class="control-label">延迟时间 (秒)</label>
                        <input type="range" class="control-input" id="delay" min="0" max="3" step="0.1" value="0">
                        <span id="delayValue">0.0s</span>
                    </div>
                    
                    <div class="control-item">
                        <label class="control-label">重复次数</label>
                        <input type="number" class="control-input" id="iterations" min="1" max="10" value="1">
                        <label><input type="checkbox" id="infinite"> 无限循环</label>
                    </div>
                    
                    <div class="control-item">
                        <label class="control-label">缓动函数</label>
                        <select class="control-input" id="easing">
                            <option value="ease">Ease</option>
                            <option value="linear">Linear</option>
                            <option value="ease-in">Ease In</option>
                            <option value="ease-out">Ease Out</option>
                            <option value="ease-in-out">Ease In Out</option>
                            <option value="cubic-bezier(0.68,-0.55,0.265,1.55)">Bounce</option>
                        </select>
                    </div>
                </div>
            </div>
        </div>
        
        <div class="animation-showcase">
            <div class="showcase-header">
                <h3 class="showcase-title">动画演示</h3>
                <div class="showcase-controls">
                    <button class="demo-btn" id="playBtn" onclick="playAnimation()">播放动画</button>
                    <button class="demo-btn stop" id="stopBtn" onclick="stopAnimation()">停止</button>
                </div>
            </div>
            
            <div class="animation-stage">
                <div class="demo-element" id="demoElement">
                    Aa
                </div>
            </div>
            
            <div class="animation-list" id="animationList">
                <!-- 动画列表将在这里生成 -->
            </div>
        </div>
    </div>
    
    <script>
        // 动画库定义
        const animations = [
            { name: 'bounce', description: '弹跳效果', class: 'animate-bounce' },
            { name: 'pulse', description: '脉冲效果', class: 'animate-pulse' },
            { name: 'rotate', description: '旋转效果', class: 'animate-rotate' },
            { name: 'shake', description: '摇晃效果', class: 'animate-shake' },
            { name: 'fade-in', description: '淡入效果', class: 'animate-fade-in' },
            { name: 'slide-in', description: '滑入效果', class: 'animate-slide-in' },
            { name: 'flip', description: '翻转效果', class: 'animate-flip' },
            { name: 'wobble', description: '摇摆效果', class: 'animate-wobble' },
            { name: 'jello', description: '果冻效果', class: 'animate-jello' },
            { name: 'heartbeat', description: '心跳效果', class: 'animate-heartbeat' },
            { name: 'rubber-band', description: '橡皮筋效果', class: 'animate-rubber-band' },
            { name: 'swing', description: '摆动效果', class: 'animate-swing' },
            { name: 'tada', description: '欢呼效果', class: 'animate-tada' },
            { name: 'morphing', description: '变形效果', class: 'animate-morphing' },
            { name: 'glow', description: '发光效果', class: 'animate-glow' },
            { name: 'float', description: '浮动效果', class: 'animate-float' }
        ];
        
        let currentAnimation = null;
        let animationTimeout = null;
        
        // 初始化
        document.addEventListener('DOMContentLoaded', function() {
            renderAnimationList();
            setupControlListeners();
        });
        
        // 渲染动画列表
        function renderAnimationList() {
            const container = document.getElementById('animationList');
            container.innerHTML = animations.map(anim => `
                <div class="animation-item" onclick="selectAnimation('${anim.name}', '${anim.class}')">
                    <div class="animation-name">${anim.name}</div>
                    <div class="animation-description">${anim.description}</div>
                </div>
            `).join('');
        }
        
        // 选择动画
        function selectAnimation(name, className) {
            // 移除之前的选中状态
            document.querySelectorAll('.animation-item').forEach(item => {
                item.classList.remove('active');
            });
            
            // 添加选中状态
            event.target.closest('.animation-item').classList.add('active');
            
            currentAnimation = { name, className };
            updateDemoElement();
        }
        
        // 更新演示元素
        function updateDemoElement() {
            const element = document.getElementById('demoElement');
            const duration = document.getElementById('duration').value;
            const delay = document.getElementById('delay').value;
            const easing = document.getElementById('easing').value;
            const infinite = document.getElementById('infinite').checked;
            const iterations = document.getElementById('iterations').value;
            
            // 移除所有动画类
            animations.forEach(anim => {
                element.classList.remove(anim.class);
            });
            
            if (currentAnimation) {
                // 应用动画
                element.classList.add(currentAnimation.class);
                
                // 设置动画属性
                const iterationCount = infinite ? 'infinite' : iterations;
                element.style.animationDuration = duration + 's';
                element.style.animationDelay = delay + 's';
                element.style.animationTimingFunction = easing;
                element.style.animationIterationCount = iterationCount;
            }
        }
        
        // 播放动画
        function playAnimation() {
            if (!currentAnimation) {
                alert('请先选择一个动画效果');
                return;
            }
            
            updateDemoElement();
            
            // 重新开始动画
            const element = document.getElementById('demoElement');
            element.style.animation = 'none';
            element.offsetHeight; // 触发重排
            updateDemoElement();
        }
        
        // 停止动画
        function stopAnimation() {
            const element = document.getElementById('demoElement');
            animations.forEach(anim => {
                element.classList.remove(anim.class);
            });
            element.style.animation = '';
        }
        
        // 设置控制器监听器
        function setupControlListeners() {
            const duration = document.getElementById('duration');
            const delay = document.getElementById('delay');
            const iterations = document.getElementById('iterations');
            const infinite = document.getElementById('infinite');
            const easing = document.getElementById('easing');
            
            duration.addEventListener('input', function() {
                document.getElementById('durationValue').textContent = this.value + 's';
                updateDemoElement();
            });
            
            delay.addEventListener('input', function() {
                document.getElementById('delayValue').textContent = this.value + 's';
                updateDemoElement();
            });
            
            iterations.addEventListener('input', updateDemoElement);
            infinite.addEventListener('change', updateDemoElement);
            easing.addEventListener('change', updateDemoElement);
            
            // 点击演示元素触发动画
            document.getElementById('demoElement').addEventListener('click', playAnimation);
        }
        
        // 默认选择第一个动画
        setTimeout(() => {
            const firstAnimation = animations[0];
            selectAnimation(firstAnimation.name, firstAnimation.class);
        }, 100);
    </script>
</body>
</html>
```

**AI辅助学习**:
- 💡 提示词: "CSS动画性能优化技巧，如何避免重排和重绘？"
- 🔧 调试技巧: 使用浏览器开发者工具的"Performance"面板分析动画性能
- 📚 扩展阅读: 搜索"CSS动画性能优化指南"

**每日挑战**: 添加动画导出功能（CSS代码），或创建动画组合效果

---

### Day 25: 数据可视化仪表盘
**难度**: ⭐⭐⭐⭐⭐  
**知识点**: ECharts.js、数据可视化、响应式图表、交互设计
**项目描述**: 创建一个完整的数据可视化仪表盘，展示多种图表类型

**代码示例**:
```html
<!DOCTYPE html>
<html lang="zh-CN">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>数据可视化仪表盘</title>
    <script src="https://cdn.jsdelivr.net/npm/echarts@5.4.3/dist/echarts.min.js"></script>
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }
        
        body {
            font-family: 'Arial', sans-serif;
            background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
            min-height: 100vh;
            padding: 2rem;
        }
        
        .container {
            max-width: 1400px;
            margin: 0 auto;
        }
        
        .header {
            text-align: center;
            color: white;
            margin-bottom: 2rem;
        }
        
        .header h1 {
            font-size: 2.5rem;
            margin-bottom: 0.5rem;
        }
        
        .dashboard {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(400px, 1fr));
            gap: 2rem;
        }
        
        .chart-card {
            background: white;
            border-radius: 20px;
            padding: 2rem;
            box-shadow: 0 10px 30px rgba(0,0,0,0.1);
            transition: transform 0.3s ease;
        }
        
        .chart-card:hover {
            transform: translateY(-5px);
        }
        
        .chart-header {
            display: flex;
            justify-content: space-between;
            align-items: center;
            margin-bottom: 1rem;
            padding-bottom: 1rem;
            border-bottom: 2px solid #e1e5e9;
        }
        
        .chart-title {
            font-size: 1.2rem;
            font-weight: bold;
            color: #333;
        }
        
        .chart-subtitle {
            font-size: 0.9rem;
            color: #666;
        }
        
        .chart-actions {
            display: flex;
            gap: 10px;
        }
        
        .action-btn {
            background: none;
            border: none;
            padding: 5px 10px;
            cursor: pointer;
            border-radius: 5px;
            transition: background 0.2s ease;
            font-size: 14px;
        }
        
        .action-btn:hover {
            background: #f8f9fa;
        }
        
        .chart-container {
            width: 100%;
            height: 300px;
        }
        
        .stats-grid {
            display: grid;
            grid-template-columns: repeat(4, 1fr);
            gap: 1rem;
            margin-bottom: 2rem;
        }
        
        .stat-card {
            background: white;
            border-radius: 15px;
            padding: 1.5rem;
            text-align: center;
            box-shadow: 0 5px 15px rgba(0,0,0,0.1);
        }
        
        .stat-value {
            font-size: 2rem;
            font-weight: bold;
            color: #667eea;
            margin-bottom: 0.5rem;
        }
        
        .stat-label {
            font-size: 0.9rem;
            color: #666;
        }
        
        .stat-change {
            font-size: 0.8rem;
            margin-top: 0.5rem;
        }
        
        .stat-change.positive {
            color: #28a745;
        }
        
        .stat-change.negative {
            color: #dc3545;
        }
        
        .full-width {
            grid-column: 1 / -1;
        }
        
        .large-chart {
            height: 400px;
        }
        
        /* 响应式设计 */
        @media (max-width: 768px) {
            .dashboard {
                grid-template-columns: 1fr;
            }
            
            .stats-grid {
                grid-template-columns: repeat(2, 1fr);
            }
            
            .chart-card {
                padding: 1rem;
            }
            
            .chart-container {
                height: 250px;
            }
            
            .large-chart {
                height: 300px;
            }
        }
        
        @media (max-width: 480px) {
            body {
                padding: 1rem;
            }
            
            .stats-grid {
                grid-template-columns: 1fr;
            }
        }
    </style>
</head>
<body>
    <div class="container">
        <div class="header">
            <h1>📊 数据可视化仪表盘</h1>
            <p>实时监控业务数据</p>
        </div>
        
        <!-- 统计卡片 -->
        <div class="stats-grid">
            <div class="stat-card">
                <div class="stat-value" id="totalRevenue">¥0</div>
                <div class="stat-label">总收入</div>
                <div class="stat-change positive" id="revenueChange">+12.5%</div>
            </div>
            
            <div class="stat-card">
                <div class="stat-value" id="totalUsers">0</div>
                <div class="stat-label">总用户数</div>
                <div class="stat-change positive" id="userChange">+8.3%</div>
            </div>
            
            <div class="stat-card">
                <div class="stat-value" id="totalOrders">0</div>
                <div class="stat-label">总订单数</div>
                <div class="stat-change negative" id="orderChange">-2.1%</div>
            </div>
            
            <div class="stat-card">
                <div class="stat-value" id="conversionRate">0%</div>
                <div class="stat-label">转化率</div>
                <div class="stat-change positive" id="conversionChange">+1.2%</div>
            </div>
        </div>
        
        <!-- 仪表盘网格 -->
        <div class="dashboard">
            <!-- 销售趋势图 -->
            <div class="chart-card full-width">
                <div class="chart-header">
                    <div>
                        <h3 class="chart-title">销售趋势</h3>
                        <p class="chart-subtitle">过去30天的销售数据</p>
                    </div>
                    <div class="chart-actions">
                        <button class="action-btn" onclick="refreshChart('salesTrend')">刷新</button>
                        <button class="action-btn" onclick="exportChart('salesTrend')">导出</button>
                    </div>
                </div>
                <div class="chart-container large-chart" id="salesTrend"></div>
            </div>
            
            <!-- 用户分布饼图 -->
            <div class="chart-card">
                <div class="chart-header">
                    <div>
                        <h3 class="chart-title">用户分布</h3>
                        <p class="chart-subtitle">按地区分布</p>
                    </div>
                    <div class="chart-actions">
                        <button class="action-btn" onclick="refreshChart('userDistribution')">刷新</button>
                    </div>
                </div>
                <div class="chart-container" id="userDistribution"></div>
            </div>
            
            <!-- 产品销量柱状图 -->
            <div class="chart-card">
                <div class="chart-header">
                    <div>
                        <h3 class="chart-title">产品销量</h3>
                        <p class="chart-subtitle">TOP 5 产品</p>
                    </div>
                    <div class="chart-actions">
                        <button class="action-btn" onclick="refreshChart('productSales')">刷新</button>
                    </div>
                </div>
                <div class="chart-container" id="productSales"></div>
            </div>
            
            <!-- 实时数据折线图 -->
            <div class="chart-card">
                <div class="chart-header">
                    <div>
                        <h3 class="chart-title">实时数据</h3>
                        <p class="chart-subtitle">最近24小时</p>
                    </div>
                    <div class="chart-actions">
                        <button class="action-btn" onclick="toggleRealtime('realtimeData')">开始</button>
                    </div>
                </div>
                <div class="chart-container" id="realtimeData"></div>
            </div>
            
            <!-- 用户行为漏斗图 -->
            <div class="chart-card">
                <div class="chart-header">
                    <div>
                        <h3 class="chart-title">转化漏斗</h3>
                        <p class="chart-subtitle">用户行为分析</p>
                    </div>
                    <div class="chart-actions">
                        <button class="action-btn" onclick="refreshChart('conversionFunnel')">刷新</button>
                    </div>
                </div>
                <div class="chart-container" id="conversionFunnel"></div>
            </div>
            
            <!-- 热力图 -->
            <div class="chart-card">
                <div class="chart-header">
                    <div>
                        <h3 class="chart-title">活跃度热力图</h3>
                        <p class="chart-subtitle">按时间段</p>
                    </div>
                    <div class="chart-actions">
                        <button class="action-btn" onclick="refreshChart('activityHeatmap')">刷新</button>
                    </div>
                </div>
                <div class="chart-container" id="activityHeatmap"></div>
            </div>
        </div>
    </div>
    
    <script>
        // 图表配置
        const chartColors = {
            primary: '#667eea',
            secondary: '#764ba2',
            success: '#28a745',
            warning: '#ffc107',
            danger: '#dc3545',
            info: '#17a2b8'
        };
        
        // 生成随机数据
        function generateRandomData(length, min, max) {
            return Array.from({length}, () => Math.floor(Math.random() * (max - min + 1)) + min);
        }
        
        // 生成日期数组
        function generateDateRange(days) {
            const dates = [];
            const today = new Date();
            for (let i = days - 1; i >= 0; i--) {
                const date = new Date(today);
                date.setDate(date.getDate() - i);
                dates.push(date.toISOString().split('T')[0]);
            }
            return dates;
        }
        
        // 初始化销售趋势图
        function initSalesTrend() {
            const chart = echarts.init(document.getElementById('salesTrend'));
            const dates = generateDateRange(30);
            const salesData = generateRandomData(30, 5000, 15000);
            const ordersData = generateRandomData(30, 100, 500);
            
            const option = {
                tooltip: {
                    trigger: 'axis',
                    axisPointer: {
                        type: 'cross'
                    }
                },
                legend: {
                    data: ['销售额', '订单数']
                },
                xAxis: {
                    type: 'category',
                    data: dates,
                    axisLabel: {
                        formatter: function(value) {
                            return value.split('-').slice(1).join('/');
                        }
                    }
                },
                yAxis: [
                    {
                        type: 'value',
                        name: '销售额 (¥)',
                        position: 'left',
                        axisLabel: {
                            formatter: '¥{value}'
                        }
                    },
                    {
                        type: 'value',
                        name: '订单数',
                        position: 'right'
                    }
                ],
                series: [
                    {
                        name: '销售额',
                        type: 'line',
                        yAxisIndex: 0,
                        data: salesData,
                        smooth: true,
                        itemStyle: {
                            color: chartColors.primary
                        },
                        areaStyle: {
                            color: {
                                type: 'linear',
                                x: 0, y: 0, x2: 0, y2: 1,
                                colorStops: [
                                    { offset: 0, color: 'rgba(102, 126, 234, 0.3)' },
                                    { offset: 1, color: 'rgba(102, 126, 234, 0.1)' }
                                ]
                            }
                        }
                    },
                    {
                        name: '订单数',
                        type: 'bar',
                        yAxisIndex: 1,
                        data: ordersData,
                        itemStyle: {
                            color: chartColors.secondary
                        }
                    }
                ]
            };
            
            chart.setOption(option);
            return chart;
        }
        
        // 初始化用户分布饼图
        function initUserDistribution() {
            const chart = echarts.init(document.getElementById('userDistribution'));
            
            const option = {
                tooltip: {
                    trigger: 'item',
                    formatter: '{a} <br/>{b}: {c} ({d}%)'
                },
                legend: {
                    orient: 'vertical',
                    left: 'left'
                },
                series: [
                    {
                        name: '用户分布',
                        type: 'pie',
                        radius: ['40%', '70%'],
                        center: ['60%', '50%'],
                        data: [
                            { value: 1048, name: '北京', itemStyle: { color: chartColors.primary } },
                            { value: 735, name: '上海', itemStyle: { color: chartColors.secondary } },
                            { value: 580, name: '广州', itemStyle: { color: chartColors.success } },
                            { value: 484, name: '深圳', itemStyle: { color: chartColors.warning } },
                            { value: 300, name: '其他', itemStyle: { color: chartColors.info } }
                        ],
                        emphasis: {
                            itemStyle: {
                                shadowBlur: 10,
                                shadowOffsetX: 0,
                                shadowColor: 'rgba(0, 0, 0, 0.5)'
                            }
                        }
                    }
                ]
            };
            
            chart.setOption(option);
            return chart;
        }
        
        // 初始化产品销量柱状图
        function initProductSales() {
            const chart = echarts.init(document.getElementById('productSales'));
            
            const option = {
                tooltip: {
                    trigger: 'axis',
                    axisPointer: {
                        type: 'shadow'
                    }
                },
                xAxis: {
                    type: 'category',
                    data: ['产品A', '产品B', '产品C', '产品D', '产品E']
                },
                yAxis: {
                    type: 'value'
                },
                series: [
                    {
                        name: '销量',
                        type: 'bar',
                        data: [320, 302, 301, 334, 390],
                        itemStyle: {
                            color: {
                                type: 'linear',
                                x: 0, y: 0, x2: 0, y2: 1,
                                colorStops: [
                                    { offset: 0, color: chartColors.success },
                                    { offset: 1, color: chartColors.info }
                                ]
                            }
                        }
                    }
                ]
            };
            
            chart.setOption(option);
            return chart;
        }
        
        // 初始化实时数据折线图
        function initRealtimeData() {
            const chart = echarts.init(document.getElementById('realtimeData'));
            const data = [];
            const now = new Date();
            
            // 初始化24小时数据
            for (let i = 0; i < 24; i++) {
                const time = new Date(now.getTime() - (23 - i) * 3600000);
                data.push([
                    time.toISOString().substr(11, 5),
                    Math.floor(Math.random() * 100) + 50
                ]);
            }
            
            const option = {
                tooltip: {
                    trigger: 'axis'
                },
                xAxis: {
                    type: 'category',
                    boundaryGap: false
                },
                yAxis: {
                    type: 'value'
                },
                series: [
                    {
                        name: '实时数据',
                        type: 'line',
                        data: data,
                        smooth: true,
                        itemStyle: {
                            color: chartColors.warning
                        },
                        areaStyle: {
                            color: {
                                type: 'linear',
                                x: 0, y: 0, x2: 0, y2: 1,
                                colorStops: [
                                    { offset: 0, color: 'rgba(255, 193, 7, 0.3)' },
                                    { offset: 1, color: 'rgba(255, 193, 7, 0.1)' }
                                ]
                            }
                        }
                    }
                ]
            };
            
            chart.setOption(option);
            return chart;
        }
        
        // 初始化转化漏斗图
        function initConversionFunnel() {
            const chart = echarts.init(document.getElementById('conversionFunnel'));
            
            const option = {
                tooltip: {
                    trigger: 'item',
                    formatter: '{a} <br/>{b} : {c}%'
                },
                series: [
                    {
                        name: '转化漏斗',
                        type: 'funnel',
                        left: '10%',
                        top: 60,
                        bottom: 60,
                        width: '80%',
                        data: [
                            { value: 100, name: '访问', itemStyle: { color: chartColors.primary } },
                            { value: 80, name: '浏览', itemStyle: { color: chartColors.secondary } },
                            { value: 60, name: '点击', itemStyle: { color: chartColors.success } },
                            { value: 40, name: '加购', itemStyle: { color: chartColors.warning } },
                            { value: 20, name: '购买', itemStyle: { color: chartColors.danger } }
                        ]
                    }
                ]
            };
            
            chart.setOption(option);
            return chart;
        }
        
        // 初始化热力图
        function initActivityHeatmap() {
            const chart = echarts.init(document.getElementById('activityHeatmap'));
            
            const hours = [];
            const days = ['周一', '周二', '周三', '周四', '周五', '周六', '周日'];
            
            for (let i = 0; i < 24; i++) {
                hours.push(i + ':00');
            }
            
            const data = [];
            for (let i = 0; i < 7; i++) {
                for (let j = 0; j < 24; j++) {
                    data.push([j, i, Math.floor(Math.random() * 100)]);
                }
            }
            
            const option = {
                tooltip: {
                    position: 'top'
                },
                grid: {
                    height: '50%',
                    top: '10%'
                },
                xAxis: {
                    type: 'category',
                    data: hours,
                    splitArea: {
                        show: true
                    }
                },
                yAxis: {
                    type: 'category',
                    data: days,
                    splitArea: {
                        show: true
                    }
                },
                visualMap: {
                    min: 0,
                    max: 100,
                    calculable: true,
                    orient: 'horizontal',
                    left: 'center',
                    bottom: '15%',
                    inRange: {
                        color: ['#e8f4fd', '#667eea']
                    }
                },
                series: [
                    {
                        name: '活跃度',
                        type: 'heatmap',
                        data: data,
                        label: {
                            show: false
                        },
                        emphasis: {
                            itemStyle: {
                                shadowBlur: 10,
                                shadowColor: 'rgba(0, 0, 0, 0.5)'
                            }
                        }
                    }
                ]
            };
            
            chart.setOption(option);
            return chart;
        }
        
        // 更新统计数据
        function updateStats() {
            const revenue = Math.floor(Math.random() * 100000) + 500000;
            const users = Math.floor(Math.random() * 10000) + 50000;
            const orders = Math.floor(Math.random() * 1000) + 5000;
            const conversion = (Math.random() * 5 + 2).toFixed(1);
            
            document.getElementById('totalRevenue').textContent = `¥${revenue.toLocaleString()}`;
            document.getElementById('totalUsers').textContent = users.toLocaleString();
            document.getElementById('totalOrders').textContent = orders.toLocaleString();
            document.getElementById('conversionRate').textContent = conversion + '%';
        }
        
        // 刷新图表
        function refreshChart(chartId) {
            const chart = charts[chartId];
            if (chart) {
                chart.showLoading();
                setTimeout(() => {
                    chart.hideLoading();
                    // 这里可以添加数据刷新逻辑
                }, 1000);
            }
        }
        
        // 导出图表
        function exportChart(chartId) {
            const chart = charts[chartId];
            if (chart) {
                const url = chart.getDataURL({
                    pixelRatio: 2,
                    backgroundColor: '#fff'
                });
                const link = document.createElement('a');
                link.download = `${chartId}.png`;
                link.href = url;
                link.click();
            }
        }
        
        // 切换实时数据
        let realtimeInterval;
        function toggleRealtime(chartId) {
            const btn = event.target;
            if (btn.textContent === '开始') {
                btn.textContent = '停止';
                btn.style.background = '#dc3545';
                
                realtimeInterval = setInterval(() => {
                    const chart = charts[chartId];
                    if (chart) {
                        const option = chart.getOption();
                        const data = option.series[0].data;
                        data.shift();
                        const now = new Date();
                        data.push([
                            now.toISOString().substr(11, 5),
                            Math.floor(Math.random() * 100) + 50
                        ]);
                        chart.setOption(option);
                    }
                }, 2000);
            } else {
                btn.textContent = '开始';
                btn.style.background = '#28a745';
                clearInterval(realtimeInterval);
            }
        }
        
        // 存储图表实例
        const charts = {};
        
        // 页面加载完成后初始化所有图表
        document.addEventListener('DOMContentLoaded', function() {
            charts.salesTrend = initSalesTrend();
            charts.userDistribution = initUserDistribution();
            charts.productSales = initProductSales();
            charts.realtimeData = initRealtimeData();
            charts.conversionFunnel = initConversionFunnel();
            charts.activityHeatmap = initActivityHeatmap();
            
            updateStats();
            
            // 每30秒更新一次统计数据
            setInterval(updateStats, 30000);
            
            // 响应式处理
            window.addEventListener('resize', function() {
                Object.values(charts).forEach(chart => {
                    if (chart) chart.resize();
                });
            });
        });
    </script>
</body>
</html>
```

**AI辅助学习**:
- 💡 提示词: "ECharts中不同图表类型的适用场景和配置技巧"
- 🔧 调试技巧: 使用ECharts的setOption方法动态更新图表数据
- 📚 扩展阅读: 搜索"ECharts官方文档和示例"

**每日挑战**: 添加数据钻取功能，或集成WebSocket实现实时数据更新

---

## 🏆 专家级 (Day 26-30) - 综合项目实战

### Day 26: 个人博客系统
**难度**: ⭐⭐⭐⭐⭐  
**知识点**: 综合应用、路由模拟、内容管理、主题切换
**项目描述**: 创建一个功能完整的个人博客系统，包含文章列表、详情页、分类等

**代码示例**:
```html
<!DOCTYPE html>
<html lang="zh-CN">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>个人博客系统</title>
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }
        
        :root {
            --primary-color: #667eea;
            --secondary-color: #764ba2;
            --text-color: #333;
            --bg-color: #ffffff;
            --card-bg: #f8f9fa;
            --border-color: #e1e5e9;
        }
        
        [data-theme="dark"] {
            --primary-color: #4ecdc4;
            --secondary-color: #44a08d;
            --text-color: #ffffff;
            --bg-color: #1a1a1a;
            --card-bg: #2d2d2d;
            --border-color: #404040;
        }
        
        body {
            font-family: 'Arial', sans-serif;
            background: var(--bg-color);
            color: var(--text-color);
            line-height: 1.6;
            transition: all 0.3s ease;
        }
        
        .container {
            max-width: 1200px;
            margin: 0 auto;
            padding: 0 2rem;
        }
        
        /* 导航栏 */
        .navbar {
            background: var(--bg-color);
            border-bottom: 2px solid var(--border-color);
            padding: 1rem 0;
            position: sticky;
            top: 0;
            z-index: 100;
            backdrop-filter: blur(10px);
        }
        
        .nav-content {
            display: flex;
            justify-content: space-between;
            align-items: center;
        }
        
        .logo {
            font-size: 1.5rem;
            font-weight: bold;
            color: var(--primary-color);
            text-decoration: none;
        }
        
        .nav-links {
            display: flex;
            gap: 2rem;
            list-style: none;
        }
        
        .nav-links a {
            color: var(--text-color);
            text-decoration: none;
            font-weight: 500;
            transition: color 0.3s ease;
        }
        
        .nav-links a:hover,
        .nav-links a.active {
            color: var(--primary-color);
        }
        
        .theme-toggle {
            background: none;
            border: none;
            font-size: 1.5rem;
            cursor: pointer;
            color: var(--text-color);
            transition: transform 0.3s ease;
        }
        
        .theme-toggle:hover {
            transform: scale(1.1);
        }
        
        /* 主要内容区域 */
        .main-content {
            display: grid;
            grid-template-columns: 1fr 300px;
            gap: 2rem;
            padding: 2rem 0;
            min-height: calc(100vh - 200px);
        }
        
        /* 文章列表 */
        .posts-section {
            display: none;
        }
        
        .posts-section.active {
            display: block;
        }
        
        .post-card {
            background: var(--card-bg);
            border: 2px solid var(--border-color);
            border-radius: 15px;
            padding: 2rem;
            margin-bottom: 2rem;
            transition: all 0.3s ease;
        }
        
        .post-card:hover {
            border-color: var(--primary-color);
            transform: translateY(-2px);
        }
        
        .post-meta {
            display: flex;
            gap: 1rem;
            margin-bottom: 1rem;
            font-size: 0.9rem;
            color: #666;
        }
        
        .post-category {
            background: var(--primary-color);
            color: white;
            padding: 0.25rem 0.75rem;
            border-radius: 20px;
            font-size: 0.8rem;
        }
        
        .post-title {
            font-size: 1.5rem;
            font-weight: bold;
            margin-bottom: 1rem;
            color: var(--text-color);
        }
        
        .post-title a {
            color: inherit;
            text-decoration: none;
        }
        
        .post-title a:hover {
            color: var(--primary-color);
        }
        
        .post-excerpt {
            color: var(--text-color);
            opacity: 0.8;
            margin-bottom: 1rem;
            line-height: 1.6;
        }
        
        .post-footer {
            display: flex;
            justify-content: space-between;
            align-items: center;
            padding-top: 1rem;
            border-top: 1px solid var(--border-color);
        }
        
        .read-more {
            color: var(--primary-color);
            text-decoration: none;
            font-weight: 500;
            transition: all 0.3s ease;
        }
        
        .read-more:hover {
            transform: translateX(5px);
        }
        
        /* 侧边栏 */
        .sidebar {
            display: flex;
            flex-direction: column;
            gap: 2rem;
        }
        
        .sidebar-widget {
            background: var(--card-bg);
            border: 2px solid var(--border-color);
            border-radius: 15px;
            padding: 1.5rem;
        }
        
        .widget-title {
            font-size: 1.2rem;
            font-weight: bold;
            margin-bottom: 1rem;
            color: var(--text-color);
        }
        
        .category-list,
        .tag-list {
            list-style: none;
        }
        
        .category-list li,
        .tag-list li {
            margin-bottom: 0.5rem;
        }
        
        .category-list a,
        .tag-list a {
            color: var(--text-color);
            text-decoration: none;
            transition: color 0.3s ease;
        }
        
        .category-list a:hover,
        .tag-list a:hover {
            color: var(--primary-color);
        }
        
        .tag-list {
            display: flex;
            flex-wrap: wrap;
            gap: 0.5rem;
        }
        
        .tag-list li {
            background: var(--primary-color);
            color: white;
            padding: 0.25rem 0.75rem;
            border-radius: 20px;
            font-size: 0.8rem;
        }
        
        /* 文章详情页 */
        .post-detail {
            display: none;
        }
        
        .post-detail.active {
            display: block;
        }
        
        .post-content {
            background: var(--card-bg);
            border: 2px solid var(--border-color);
            border-radius: 15px;
            padding: 2rem;
        }
        
        .post-content h2,
        .post-content h3 {
            color: var(--text-color);
            margin: 2rem 0 1rem;
        }
        
        .post-content p {
            margin-bottom: 1rem;
            line-height: 1.8;
        }
        
        .post-content code {
            background: var(--border-color);
            padding: 0.2rem 0.5rem;
            border-radius: 5px;
            font-family: 'Courier New', monospace;
        }
        
        .post-content pre {
            background: var(--border-color);
            padding: 1rem;
            border-radius: 10px;
            overflow-x: auto;
            margin: 1rem 0;
        }
        
        .back-btn {
            background: var(--primary-color);
            color: white;
            border: none;
            padding: 0.75rem 1.5rem;
            border-radius: 8px;
            cursor: pointer;
            margin-bottom: 2rem;
            transition: all 0.3s ease;
        }
        
        .back-btn:hover {
            background: var(--secondary-color);
            transform: translateY(-2px);
        }
        
        /* 关于页面 */
        .about-section {
            display: none;
        }
        
        .about-section.active {
            display: block;
        }
        
        .about-content {
            background: var(--card-bg);
            border: 2px solid var(--border-color);
            border-radius: 15px;
            padding: 2rem;
        }
        
        .profile-section {
            display: flex;
            gap: 2rem;
            margin-bottom: 2rem;
            align-items: center;
        }
        
        .profile-avatar {
            width: 150px;
            height: 150px;
            border-radius: 50%;
            object-fit: cover;
            border: 5px solid var(--primary-color);
        }
        
        .profile-info h2 {
            color: var(--text-color);
            margin-bottom: 0.5rem;
        }
        
        .profile-info p {
            color: var(--text-color);
            opacity: 0.8;
            line-height: 1.6;
        }
        
        .skills-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(200px, 1fr));
            gap: 1rem;
            margin-top: 2rem;
        }
        
        .skill-item {
            background: var(--border-color);
            padding: 1rem;
            border-radius: 10px;
            text-align: center;
        }
        
        .skill-name {
            font-weight: bold;
            margin-bottom: 0.5rem;
        }
        
        .skill-level {
            width: 100%;
            height: 8px;
            background: #e1e5e9;
            border-radius: 4px;
            overflow: hidden;
            margin-top: 0.5rem;
        }
        
        .skill-progress {
            height: 100%;
            background: var(--primary-color);
            border-radius: 4px;
            transition: width 2s ease;
        }
        
        /* 页脚 */
        .footer {
            background: var(--card-bg);
            border-top: 2px solid var(--border-color);
            padding: 2rem 0;
            text-align: center;
            margin-top: 2rem;
        }
        
        .footer-content {
            color: var(--text-color);
            opacity: 0.8;
        }
        
        /* 响应式设计 */
        @media (max-width: 768px) {
            .main-content {
                grid-template-columns: 1fr;
            }
            
            .nav-links {
                display: none;
            }
            
            .profile-section {
                flex-direction: column;
                text-align: center;
            }
            
            .skills-grid {
                grid-template-columns: 1fr;
            }
        }
        
        @media (max-width: 480px) {
            body {
                padding: 0;
            }
            
            .container {
                padding: 0 1rem;
            }
            
            .post-card,
            .sidebar-widget,
            .post-content,
            .about-content {
                padding: 1rem;
            }
        }
    </style>
</head>
<body>
    <!-- 导航栏 -->
    <nav class="navbar">
        <div class="container">
            <div class="nav-content">
                <a href="#" class="logo" onclick="showHome()">我的博客</a>
                <ul class="nav-links">
                    <li><a href="#" class="active" onclick="showHome()">首页</a></li>
                    <li><a href="#" onclick="showCategory('tech')">技术</a></li>
                    <li><a href="#" onclick="showCategory('life')">生活</a></li>
                    <li><a href="#" onclick="showAbout()">关于</a></li>
                </ul>
                <button class="theme-toggle" onclick="toggleTheme()" id="themeToggle">🌙</button>
            </div>
        </div>
    </nav>
    
    <!-- 主要内容 -->
    <div class="container">
        <div class="main-content">
            <!-- 文章列表 -->
            <div class="posts-section active" id="postsSection">
                <!-- 文章卡片将在这里动态生成 -->
            </div>
            
            <!-- 文章详情 -->
            <div class="post-detail" id="postDetail">
                <!-- 文章详情将在这里显示 -->
            </div>
            
            <!-- 关于页面 -->
            <div class="about-section" id="aboutSection">
                <!-- 关于内容将在这里显示 -->
            </div>
            
            <!-- 侧边栏 -->
            <aside class="sidebar">
                <!-- 分类 -->
                <div class="sidebar-widget">
                    <h3 class="widget-title">文章分类</h3>
                    <ul class="category-list" id="categoryList">
                        <!-- 分类列表将在这里生成 -->
                    </ul>
                </div>
                
                <!-- 标签 -->
                <div class="sidebar-widget">
                    <h3 class="widget-title">热门标签</h3>
                    <ul class="tag-list" id="tagList">
                        <!-- 标签列表将在这里生成 -->
                    </ul>
                </div>
                
                <!-- 最新文章 -->
                <div class="sidebar-widget">
                    <h3 class="widget-title">最新文章</h3>
                    <ul class="category-list" id="recentPosts">
                        <!-- 最新文章列表将在这里生成 -->
                    </ul>
                </div>
            </aside>
        </div>
    </div>
    
    <!-- 页脚 -->
    <footer class="footer">
        <div class="container">
            <div class="footer-content">
                <p>&copy; 2025 我的博客. All rights reserved.</p>
                <p>用心记录，分享成长</p>
            </div>
        </div>
    </footer>
    
    <script>
        // 博客数据
        const blogData = {
            posts: [
                {
                    id: 1,
                    title: 'JavaScript异步编程完全指南',
                    category: 'tech',
                    tags: ['JavaScript', '异步编程', 'Promise', 'async/await'],
                    excerpt: '深入理解JavaScript中的异步编程概念，从回调函数到Promise，再到async/await的完整学习路径。',
                    content: `
                        <h2>什么是异步编程？</h2>
                        <p>异步编程是JavaScript中最重要的概念之一，它允许程序在等待某些操作完成时继续执行其他代码。</p>
                        
                        <h3>1. 回调函数</h3>
                        <p>回调函数是最基础的异步编程模式：</p>
                        <pre><code>function fetchData(callback) {
    setTimeout(() => {
        const data = { name: 'John', age: 30 };
        callback(data);
    }, 1000);
}</code></pre>
                        
                        <h3>2. Promise</h3>
                        <p>Promise提供了更优雅的异步处理方式：</p>
                        <pre><code>function fetchData() {
    return new Promise((resolve, reject) => {
        setTimeout(() => {
            const data = { name: 'John', age: 30 };
            resolve(data);
        }, 1000);
    });
}</code></pre>
                        
                        <h3>3. Async/Await</h3>
                        <p>Async/Await让异步代码看起来像同步代码：</p>
                        <pre><code>async function fetchData() {
    const result = await api.get('/users');
    return result.data;
}</code></pre>
                    `,
                    date: '2025-01-15',
                    readTime: '8分钟'
                },
                {
                    id: 2,
                    title: 'CSS Grid布局实战教程',
                    category: 'tech',
                    tags: ['CSS', 'Grid', '布局', '响应式'],
                    excerpt: '掌握CSS Grid布局系统，创建复杂而灵活的网页布局。',
                    content: `
                        <h2>CSS Grid简介</h2>
                        <p>CSS Grid是一个二维布局系统，它可以同时处理行和列。</p>
                        
                        <h3>基本用法</h3>
                        <pre><code>.container {
    display: grid;
    grid-template-columns: 1fr 2fr 1fr;
    grid-template-rows: auto 1fr auto;
    gap: 20px;
}</code></pre>
                    `,
                    date: '2025-01-10',
                    readTime: '6分钟'
                },
                {
                    id: 3,
                    title: '我的2025年度总结',
                    category: 'life',
                    tags: ['年度总结', '成长', '反思'],
                    excerpt: '回顾2025年的成长历程，分享经验和感悟。',
                    content: `
                        <h2>2025年回顾</h2>
                        <p>这一年充满了挑战和成长...</p>
                    `,
                    date: '2025-01-05',
                    readTime: '5分钟'
                }
            ],
            categories: [
                { name: 'tech', label: '技术', count: 2 },
                { name: 'life', label: '生活', count: 1 }
            ],
            tags: ['JavaScript', 'CSS', '异步编程', 'Grid', '年度总结', '成长']
        };
        
        let currentTheme = localStorage.getItem('theme') || 'light';
        
        // 初始化
        document.addEventListener('DOMContentLoaded', function() {
            applyTheme(currentTheme);
            showHome();
            renderSidebar();
        });
        
        // 主题切换
        function toggleTheme() {
            currentTheme = currentTheme === 'light' ? 'dark' : 'light';
            applyTheme(currentTheme);
            localStorage.setItem('theme', currentTheme);
        }
        
        function applyTheme(theme) {
            document.documentElement.setAttribute('data-theme', theme);
            const themeToggle = document.getElementById('themeToggle');
            themeToggle.textContent = theme === 'light' ? '🌙' : '☀️';
        }
        
        // 显示首页
        function showHome() {
            hideAllSections();
            document.getElementById('postsSection').classList.add('active');
            updateNavigation('home');
            renderPosts();
        }
        
        // 显示分类
        function showCategory(category) {
            hideAllSections();
            document.getElementById('postsSection').classList.add('active');
            updateNavigation(category);
            renderPosts(category);
        }
        
        // 显示关于页面
        function showAbout() {
            hideAllSections();
            document.getElementById('aboutSection').classList.add('active');
            updateNavigation('about');
            renderAbout();
        }
        
        // 显示文章详情
        function showPost(postId) {
            hideAllSections();
            document.getElementById('postDetail').classList.add('active');
            renderPostDetail(postId);
        }
        
        // 隐藏所有区域
        function hideAllSections() {
            document.querySelectorAll('.posts-section, .post-detail, .about-section').forEach(section => {
                section.classList.remove('active');
            });
        }
        
        // 更新导航状态
        function updateNavigation(active) {
            document.querySelectorAll('.nav-links a').forEach(link => {
                link.classList.remove('active');
            });
            
            if (active === 'home') {
                document.querySelector('.nav-links a').classList.add('active');
            }
        }
        
        // 渲染文章列表
        function renderPosts(category = null) {
            const postsSection = document.getElementById('postsSection');
            let posts = blogData.posts;
            
            if (category) {
                posts = posts.filter(post => post.category === category);
            }
            
            postsSection.innerHTML = posts.map(post => `
                <article class="post-card">
                    <div class="post-meta">
                        <span class="post-category">${getCategoryLabel(post.category)}</span>
                        <span>${post.date}</span>
                        <span>阅读时间: ${post.readTime}</span>
                    </div>
                    <h2 class="post-title">
                        <a href="#" onclick="showPost(${post.id})">${post.title}</a>
                    </h2>
                    <p class="post-excerpt">${post.excerpt}</p>
                    <div class="post-footer">
                        <div class="post-tags">
                            ${post.tags.map(tag => `<span class="tag">${tag}</span>`).join('')}
                        </div>
                        <a href="#" class="read-more" onclick="showPost(${post.id})">阅读更多 →</a>
                    </div>
                </article>
            `).join('');
        }
        
        // 渲染文章详情
        function renderPostDetail(postId) {
            const post = blogData.posts.find(p => p.id === postId);
            if (!post) return;
            
            const postDetail = document.getElementById('postDetail');
            postDetail.innerHTML = `
                <button class="back-btn" onclick="showHome()">← 返回列表</button>
                <article class="post-content">
                    <h1 class="post-title">${post.title}</h1>
                    <div class="post-meta">
                        <span class="post-category">${getCategoryLabel(post.category)}</span>
                        <span>${post.date}</span>
                        <span>阅读时间: ${post.readTime}</span>
                    </div>
                    <div class="post-body">
                        ${post.content}
                    </div>
                    <div class="post-tags">
                        ${post.tags.map(tag => `<span class="tag">${tag}</span>`).join('')}
                    </div>
                </article>
            `;
        }
        
        // 渲染关于页面
        function renderAbout() {
            const aboutSection = document.getElementById('aboutSection');
            aboutSection.innerHTML = `
                <button class="back-btn" onclick="showHome()">← 返回首页</button>
                <div class="about-content">
                    <div class="profile-section">
                        <img src="https://picsum.photos/150/150?random=1" alt="头像" class="profile-avatar">
                        <div class="profile-info">
                            <h2>张三</h2>
                            <p>前端开发工程师，热爱技术和分享。专注于JavaScript、CSS、Vue.js等现代前端技术栈。</p>
                            <p>在这个博客中，我会分享我的技术心得、学习笔记和生活感悟。</p>
                        </div>
                    </div>
                    
                    <h3>技能专长</h3>
                    <div class="skills-grid">
                        <div class="skill-item">
                            <div class="skill-name">HTML5 & CSS3</div>
                            <div class="skill-level">
                                <div class="skill-progress" style="width: 90%"></div>
                            </div>
                        </div>
                        <div class="skill-item">
                            <div class="skill-name">JavaScript</div>
                            <div class="skill-level">
                                <div class="skill-progress" style="width: 85%"></div>
                            </div>
                        </div>
                        <div class="skill-item">
                            <div class="skill-name">Vue.js</div>
                            <div class="skill-level">
                                <div class="skill-progress" style="width: 80%"></div>
                            </div>
                        </div>
                        <div class="skill-item">
                            <div class="skill-name">React</div>
                            <div class="skill-level">
                                <div class="skill-progress" style="width: 75%"></div>
                            </div>
                        </div>
                    </div>
                    
                    <h3>联系方式</h3>
                    <p>邮箱: zhangsan@example.com</p>
                    <p>GitHub: github.com/zhangsan</p>
                </div>
            `;
        }
        
        // 渲染侧边栏
        function renderSidebar() {
            // 渲染分类
            const categoryList = document.getElementById('categoryList');
            categoryList.innerHTML = blogData.categories.map(cat => `
                <li><a href="#" onclick="showCategory('${cat.name}')">${cat.label} (${cat.count})</a></li>
            `).join('');
            
            // 渲染标签
            const tagList = document.getElementById('tagList');
            tagList.innerHTML = blogData.tags.map(tag => `
                <li><a href="#">${tag}</a></li>
            `).join('');
            
            // 渲染最新文章
            const recentPosts = document.getElementById('recentPosts');
            recentPosts.innerHTML = blogData.posts.slice(0, 3).map(post => `
                <li><a href="#" onclick="showPost(${post.id})">${post.title}</a></li>
            `).join('');
        }
        
        // 获取分类标签
        function getCategoryLabel(category) {
            const map = {
                tech: '技术',
                life: '生活'
            };
            return map[category] || category;
        }
        
        // 页面加载时动画效果
        window.addEventListener('load', function() {
            const skillProgress = document.querySelectorAll('.skill-progress');
            skillProgress.forEach(bar => {
                const width = bar.style.width;
                bar.style.width = '0%';
                setTimeout(() => {
                    bar.style.width = width;
                }, 500);
            });
        });
    </script>
</body>
</html>
```

**AI辅助学习**:
- 💡 提示词: "单页应用(SPA)的路由实现原理和最佳实践"
- 🔧 调试技巧: 使用浏览器历史API调试页面路由切换
- 📚 扩展阅读: 搜索"前端路由实现原理"

**每日挑战**: 添加文章搜索功能，或实现文章评论系统

---

### Day 27: 电商产品展示页
**难度**: ⭐⭐⭐⭐⭐  
**知识点**: 产品展示、购物车、筛选排序、响应式设计
**项目描述**: 创建一个现代化的电商产品展示页面，包含完整的产品浏览和筛选功能

**代码示例**:
```html
<!DOCTYPE html>
<html lang="zh-CN">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>电商产品展示</title>
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }
        
        body {
            font-family: 'Arial', sans-serif;
            background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
            min-height: 100vh;
            padding: 2rem;
        }
        
        .container {
            max-width: 1400px;
            margin: 0 auto;
        }
        
        .header {
            text-align: center;
            color: white;
            margin-bottom: 2rem;
        }
        
        .header h1 {
            font-size: 2.5rem;
            margin-bottom: 0.5rem;
        }
        
        .shop-container {
            background: white;
            border-radius: 20px;
            padding: 2rem;
            box-shadow: 0 10px 30px rgba(0,0,0,0.1);
        }
        
        .shop-header {
            display: flex;
            justify-content: space-between;
            align-items: center;
            margin-bottom: 2rem;
            padding-bottom: 1rem;
            border-bottom: 2px solid #e1e5e9;
        }
        
        .shop-title {
            font-size: 1.8rem;
            font-weight: bold;
            color: #333;
        }
        
        .cart-summary {
            display: flex;
            align-items: center;
            gap: 1rem;
        }
        
        .cart-count {
            background: #dc3545;
            color: white;
            padding: 0.5rem 1rem;
            border-radius: 20px;
            font-weight: bold;
        }
        
        .cart-total {
            font-size: 1.2rem;
            font-weight: bold;
            color: #28a745;
        }
        
        .view-cart-btn {
            background: #667eea;
            color: white;
            border: none;
            padding: 0.75rem 1.5rem;
            border-radius: 8px;
            cursor: pointer;
            transition: all 0.3s ease;
        }
        
        .view-cart-btn:hover {
            background: #5a6fd8;
            transform: scale(1.05);
        }
        
        .shop-controls {
            display: grid;
            grid-template-columns: 250px 1fr auto;
            gap: 2rem;
            margin-bottom: 2rem;
        }
        
        .filters-sidebar {
            background: #f8f9fa;
            padding: 1.5rem;
            border-radius: 15px;
            height: fit-content;
        }
        
        .filter-section {
            margin-bottom: 2rem;
        }
        
        .filter-title {
            font-size: 1.1rem;
            font-weight: bold;
            margin-bottom: 1rem;
            color: #333;
        }
        
        .filter-options {
            display: flex;
            flex-direction: column;
            gap: 0.5rem;
        }
        
        .filter-option {
            display: flex;
            align-items: center;
            gap: 0.5rem;
        }
        
        .filter-option input[type="checkbox"] {
            width: 18px;
            height: 18px;
        }
        
        .price-range {
            display: flex;
            flex-direction: column;
            gap: 0.5rem;
        }
        
        .price-inputs {
            display: flex;
            gap: 0.5rem;
        }
        
        .price-input {
            flex: 1;
            padding: 8px;
            border: 2px solid #e1e5e9;
            border-radius: 5px;
            font-size: 14px;
        }
        
        .filter-btn {
            background: #667eea;
            color: white;
            border: none;
            padding: 0.5rem 1rem;
            border-radius: 5px;
            cursor: pointer;
            font-size: 14px;
            transition: all 0.3s ease;
        }
        
        .filter-btn:hover {
            background: #5a6fd8;
        }
        
        .clear-filters {
            background: #6c757d;
        }
        
        .clear-filters:hover {
            background: #5a6268;
        }
        
        .products-grid {
            display: grid;
            grid-template-columns: repeat(auto-fill, minmax(280px, 1fr));
            gap: 2rem;
        }
        
        .product-card {
            background: white;
            border: 2px solid #e1e5e9;
            border-radius: 15px;
            padding: 1.5rem;
            transition: all 0.3s ease;
            position: relative;
        }
        
        .product-card:hover {
            border-color: #667eea;
            transform: translateY(-5px);
            box-shadow: 0 10px 30px rgba(0,0,0,0.1);
        }
        
        .product-badge {
            position: absolute;
            top: 1rem;
            right: 1rem;
            background: #dc3545;
            color: white;
            padding: 0.25rem 0.75rem;
            border-radius: 20px;
            font-size: 0.8rem;
            font-weight: bold;
        }
        
        .product-badge.new {
            background: #28a745;
        }
        
        .product-badge.sale {
            background: #ffc107;
            color: #333;
        }
        
        .product-image {
            width: 100%;
            height: 200px;
            object-fit: cover;
            border-radius: 10px;
            margin-bottom: 1rem;
            cursor: pointer;
            transition: transform 0.3s ease;
        }
        
        .product-image:hover {
            transform: scale(1.05);
        }
        
        .product-name {
            font-size: 1.2rem;
            font-weight: bold;
            margin-bottom: 0.5rem;
            color: #333;
        }
        
        .product-description {
            color: #666;
            font-size: 0.9rem;
            margin-bottom: 1rem;
            line-height: 1.4;
        }
        
        .product-rating {
            display: flex;
            align-items: center;
            gap: 0.5rem;
            margin-bottom: 1rem;
        }
        
        .stars {
            color: #ffc107;
        }
        
        .rating-count {
            color: #666;
            font-size: 0.8rem;
        }
        
        .product-price {
            display: flex;
            align-items: center;
            gap: 0.5rem;
            margin-bottom: 1rem;
        }
        
        .current-price {
            font-size: 1.5rem;
            font-weight: bold;
            color: #28a745;
        }
        
        .original-price {
            font-size: 1rem;
            color: #666;
            text-decoration: line-through;
        }
        
        .product-actions {
            display: flex;
            gap: 0.5rem;
        }
        
        .quantity-control {
            display: flex;
            align-items: center;
            border: 2px solid #e1e5e9;
            border-radius: 5px;
            overflow: hidden;
        }
        
        .quantity-btn {
            background: #f8f9fa;
            border: none;
            padding: 0.5rem;
            cursor: pointer;
            font-size: 1rem;
            transition: background 0.2s ease;
        }
        
        .quantity-btn:hover {
            background: #e9ecef;
        }
        
        .quantity-input {
            width: 50px;
            text-align: center;
            border: none;
            padding: 0.5rem;
            font-size: 1rem;
        }
        
        .add-to-cart {
            flex: 1;
            background: #667eea;
            color: white;
            border: none;
            padding: 0.75rem;
            border-radius: 8px;
            cursor: pointer;
            font-weight: bold;
            transition: all 0.3s ease;
        }
        
        .add-to-cart:hover {
            background: #5a6fd8;
            transform: scale(1.02);
        }
        
        .add-to-cart:disabled {
            opacity: 0.6;
            cursor: not-allowed;
            transform: none;
        }
        
        .sort-controls {
            display: flex;
            flex-direction: column;
            gap: 1rem;
        }
        
        .sort-select {
            padding: 12px;
            border: 2px solid #e1e5e9;
            border-radius: 8px;
            font-size: 16px;
            background: white;
            cursor: pointer;
        }
        
        .view-modes {
            display: flex;
            gap: 0.5rem;
        }
        
        .view-btn {
            background: #f8f9fa;
            border: 2px solid #e1e5e9;
            padding: 0.5rem;
            border-radius: 5px;
            cursor: pointer;
            transition: all 0.3s ease;
        }
        
        .view-btn.active {
            background: var(--primary-color);
            color: white;
            border-color: var(--primary-color);
        }
        
        /* 购物车模态框 */
        .cart-modal {
            position: fixed;
            top: 0;
            left: 0;
            width: 100%;
            height: 100%;
            background: rgba(0, 0, 0, 0.5);
            display: flex;
            justify-content: center;
            align-items: center;
            z-index: 1000;
            opacity: 0;
            visibility: hidden;
            transition: all 0.3s ease;
        }
        
        .cart-modal.show {
            opacity: 1;
            visibility: visible;
        }
        
        .cart-content {
            background: white;
            border-radius: 20px;
            padding: 2rem;
            max-width: 600px;
            width: 90%;
            max-height: 80vh;
            overflow-y: auto;
            transform: scale(0.7);
            transition: transform 0.3s ease;
        }
        
        .cart-modal.show .cart-content {
            transform: scale(1);
        }
        
        .cart-header {
            display: flex;
            justify-content: space-between;
            align-items: center;
            margin-bottom: 2rem;
            padding-bottom: 1rem;
            border-bottom: 2px solid #e1e5e9;
        }
        
        .cart-title {
            font-size: 1.5rem;
            font-weight: bold;
            color: #333;
        }
        
        .close-cart {
            background: none;
            border: none;
            font-size: 1.5rem;
            cursor: pointer;
            color: #666;
        }
        
        .cart-items {
            margin-bottom: 2rem;
        }
        
        .cart-item {
            display: flex;
            gap: 1rem;
            padding: 1rem;
            border: 1px solid #e1e5e9;
            border-radius: 10px;
            margin-bottom: 1rem;
        }
        
        .cart-item-image {
            width: 80px;
            height: 80px;
            object-fit: cover;
            border-radius: 8px;
        }
        
        .cart-item-details {
            flex: 1;
        }
        
        .cart-item-name {
            font-weight: bold;
            margin-bottom: 0.5rem;
        }
        
        .cart-item-price {
            color: #28a745;
            font-weight: bold;
        }
        
        .cart-summary {
            text-align: center;
            padding-top: 1rem;
            border-top: 2px solid #e1e5e9;
        }
        
        .cart-total-price {
            font-size: 1.5rem;
            font-weight: bold;
            color: #28a745;
            margin-bottom: 1rem;
        }
        
        .checkout-btn {
            background: #28a745;
            color: white;
            border: none;
            padding: 1rem 2rem;
            border-radius: 8px;
            cursor: pointer;
            font-size: 1.1rem;
            font-weight: bold;
            transition: all 0.3s ease;
        }
        
        .checkout-btn:hover {
            background: #218838;
            transform: scale(1.05);
        }
        
        /* 响应式设计 */
        @media (max-width: 768px) {
            .shop-controls {
                grid-template-columns: 1fr;
            }
            
            .filters-sidebar {
                order: -1;
            }
            
            .products-grid {
                grid-template-columns: repeat(auto-fill, minmax(250px, 1fr));
            }
            
            body {
                padding: 1rem;
            }
        }
        
        @media (max-width: 480px) {
            .product-actions {
                flex-direction: column;
            }
            
            .quantity-control {
                width: 100%;
                justify-content: center;
            }
        }
    </style>
</head>
<body>
    <div class="container">
        <div class="header">
            <h1>🛍️ 电商产品展示</h1>
            <p>精选优质商品，品质保证</p>
        </div>
        
        <div class="shop-container">
            <div class="shop-header">
                <h2 class="shop-title">产品列表</h2>
                <div class="cart-summary">
                    <span class="cart-count" id="cartCount">0</span>
                    <span class="cart-total" id="cartTotal">¥0</span>
                    <button class="view-cart-btn" onclick="toggleCart()">查看购物车</button>
                </div>
            </div>
            
            <div class="shop-controls">
                <div class="filters-sidebar">
                    <div class="filter-section">
                        <h3 class="filter-title">分类</h3>
                        <div class="filter-options" id="categoryFilters">
                            <!-- 分类过滤器将在这里生成 -->
                        </div>
                    </div>
                    
                    <div class="filter-section">
                        <h3 class="filter-title">价格区间</h3>
                        <div class="price-range">
                            <div class="price-inputs">
                                <input type="number" class="price-input" id="minPrice" placeholder="最低价">
                                <input type="number" class="price-input" id="maxPrice" placeholder="最高价">
                            </div>
                            <button class="filter-btn" onclick="applyPriceFilter()">应用</button>
                        </div>
                    </div>
                    
                    <div class="filter-section">
                        <h3 class="filter-title">评分</h3>
                        <div class="filter-options" id="ratingFilters">
                            <div class="filter-option">
                                <input type="checkbox" id="rating4" value="4">
                                <label for="rating4">4星及以上</label>
                            </div>
                            <div class="filter-option">
                                <input type="checkbox" id="rating3" value="3">
                                <label for="rating3">3星及以上</label>
                            </div>
                            <div class="filter-option">
                                <input type="checkbox" id="rating2" value="2">
                                <label for="rating2">2星及以上</label>
                            </div>
                        </div>
                    </div>
                    
                    <button class="filter-btn clear-filters" onclick="clearAllFilters()">清除所有筛选</button>
                </div>
                
                <div class="products-grid" id="productsGrid">
                    <!-- 产品卡片将在这里生成 -->
                </div>
                
                <div class="sort-controls">
                    <select class="sort-select" id="sortSelect" onchange="sortProducts()">
                        <option value="default">默认排序</option>
                        <option value="price-asc">价格从低到高</option>
                        <option value="price-desc">价格从高到低</option>
                        <option value="rating">评分最高</option>
                        <option value="name">名称排序</option>
                    </select>
                    
                    <div class="view-modes">
                        <button class="view-btn active" onclick="changeView('grid')">⊞</button>
                        <button class="view-btn" onclick="changeView('list')">☰</button>
                    </div>
                </div>
            </div>
        </div>
    </div>
    
    <!-- 购物车模态框 -->
    <div class="cart-modal" id="cartModal">
        <div class="cart-content">
            <div class="cart-header">
                <h3 class="cart-title">购物车</h3>
                <button class="close-cart" onclick="toggleCart()">&times;</button>
            </div>
            
            <div class="cart-items" id="cartItems">
                <!-- 购物车商品将在这里显示 -->
            </div>
            
            <div class="cart-summary">
                <div class="cart-total-price" id="cartTotalPrice">总计: ¥0</div>
                <button class="checkout-btn" onclick="checkout()">结算</button>
            </div>
        </div>
    </div>
    
    <script>
        // 产品数据
        const products = [
            {
                id: 1,
                name: '智能手表 Pro',
                description: '高端智能手表，支持心率监测、GPS定位、防水设计',
                price: 1299,
                originalPrice: 1599,
                category: 'electronics',
                image: 'https://picsum.photos/300/200?random=1',
                rating: 4.5,
                reviews: 234,
                badge: 'sale'
            },

