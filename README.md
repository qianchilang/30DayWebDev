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

由于篇幅限制，我会继续为你生成剩余的项目。以上是前12天的详细项目内容，每个项目都包含：

1. **完整的HTML/CSS/JavaScript代码**
2. **详细的知识点说明**
3. **AI辅助学习提示**
4. **调试技巧和扩展阅读**
5. **每日挑战任务**

**接下来我会继续生成Day 13-30的项目内容...**
