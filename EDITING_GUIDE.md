# 📝 网站内容修改指南

## 🎯 主要文件位置

**唯一需要修改的文件**: `index.html`

所有内容都在这一个文件中，按照下面的行数和位置进行修改。

---

## 📋 各部分修改位置详解

### 1. 👤 个人信息 (侧边栏)
**位置**: 第 299-318 行

```html
<!-- 第 301 行：个人照片 -->
<img src="/images/profile.jpg" alt="Ming Ji" ... />

<!-- 第 302 行：姓名 -->
<h2>Ming Ji</h2>

<!-- 第 303 行：职位 -->
<h3>Master's Student</h3>

<!-- 第 306-311 行：详细信息 -->
<p>
  <strong>Master's Student</strong><br />
  <a href="https://www.isee.zju.edu.cn/">Zhejiang University</a><br />
  College of Information Science & Electronic Engineering<br />
  <span>Hangzhou, China</span>
</p>
```

**修改内容**:
- 照片：更换 `/images/profile.jpg` 文件
- 姓名：修改 "Ming Ji"
- 职位：修改 "Master's Student"
- 学校和联系方式：修改对应的链接和文本

---

### 2. 🏠 导航栏菜单
**位置**: 第 266-280 行

```html
<li class="nav-item">
  <a class="nav-link" href="#top">Home</a>
</li>
<li class="nav-item">
  <a class="nav-link" href="#about">About</a>
</li>
<li class="nav-item">
  <a class="nav-link" href="#publications">Publications</a>
</li>
<li class="nav-item">
  <a class="nav-link" href="#projects">Projects</a>
</li>
<li class="nav-item">
  <a class="nav-link" href="#internships">Internships</a>
</li>
```

**添加新菜单项**:
```html
<li class="nav-item">
  <a class="nav-link" href="#新部分ID">新菜单名</a>
</li>
```

---

### 3. 📖 About Me (关于我)
**位置**: 第 329-336 行

```html
<h2 id="about">About Me</h2>
<p>
  I am a Master's student at the College of Information Science
  & Electronic Engineering, Zhejiang University...
</p>
```

**修改内容**:
- 修改个人介绍段落
- 添加新的段落

---

### 4. 🎓 Education (教育背景)
**位置**: 第 338-362 行

```html
<h2 id="education">🎓 Education</h2>
<table class="table">
  <thead>
    <tr>
      <th>Period</th>
      <th>Institution</th>
      <th>Major</th>
      <th>Degree</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>2024 - Present</td>
      <td>Zhejiang University</td>
      <td>Information & Electronic Engineering</td>
      <td>Master</td>
    </tr>
  </tbody>
</table>
```

**添加新教育经历**:
```html
<tr>
  <td>时间段</td>
  <td>学校名称</td>
  <td>专业</td>
  <td>学位</td>
</tr>
```

---

### 5. 🏆 Honors & Awards (荣誉奖项)
**位置**: 第 364-374 行

```html
<h2 id="honors">🏆 Honors & Awards</h2>
<ul>
  <li><span class="award">🥇</span> Outstanding Student, Zhejiang University</li>
  <li><span class="award">🥈</span> Second-Class Scholarship, Jilin University</li>
</ul>
```

**添加新奖项**:
```html
<li><span class="award">🏅</span> 你的奖项名称</li>
```

**可用的奖项图标**:
- 🥇 金奖
- 🥈 银奖
- 🥉 铜奖
- 🏅 一般奖项
- 📄 论文/证书
- 🔬 专利/研究

---

### 6. 📝 Publications (论文发表) ⭐ 重要
**位置**: 第 377-397 行

```html
<h2 id="publications">📝 Publications</h2>
<ol>
  <li>
    <strong>论文标题</strong><br />
    <span style="color: #3498db;">作者列表</span><br />
    <i>会议/期刊名称</i>, 年份.<br />
    <a href="论文链接">[Paper]</a> <a href="代码链接">[Code]</a>
  </li>
</ol>
```

**添加新论文**:
```html
<li>
  <strong>你的新论文标题</strong><br />
  <span style="color: #3498db;">你的名字</span>, 合作者<br />
  <i>会议/期刊名称</i>, 年份.<br />
  <a href="https://..." target="_blank">[Paper]</a>
</li>
```

**论文显示顺序**: 从上到下，最新的放在最上面

---

### 7. 🚀 Projects (项目经历) ⭐ 重要
**位置**: 第 400-430 行

```html
<h2 id="projects">🚀 Projects</h2>
<ul>
  <li>
    <strong>项目名称</strong><br />
    <span style="color: #7f8c8d;">项目类型 • 年份</span><br />
    <span style="font-size: 0.95em;">项目描述...</span>
  </li>
</ul>
```

**添加新项目**:
```html
<li>
  <strong>你的新项目名称</strong><br />
  <span style="color: #7f8c8d;">项目类型 • 2025</span><br />
  <span style="font-size: 0.95em;">
    项目详细描述，可以包括技术栈、成果等。<br />
    <a href="https://github.com/..." target="_blank" style="color: #3498db;">[GitHub]</a>
  </span>
</li>
```

**项目类型示例**:
- Research Project
- Intelligent Agent System
- Internship Project
- Course Project

---

### 8. 💼 Internships (实习经历)
**位置**: 第 432-454 行

```html
<h2 id="internships">💼 Internships</h2>
<h3>Algorithm Intern</h3>
<p>
  <strong>公司名称</strong>, 城市 (时间段)<br />
  <span style="color: #7f8c8d;">工作描述</span>
</p>
<ul>
  <li>具体工作内容1</li>
  <li>具体工作内容2</li>
</ul>
```

**添加新实习经历**:
```html
<h3>职位名称</h3>
<p>
  <strong>公司名称</strong>, 城市 (Month Year – Month Year)<br />
  <span style="color: #7f8c8d;">简短描述</span>
</p>
<ul>
  <li>工作内容1</li>
  <li>工作内容2</li>
  <li>工作内容3</li>
</ul>
```

---

## 🔧 添加全新的部分

如果你想添加一个全新的部分（比如"Skills"、"Teaching"等）：

### 步骤 1: 在导航栏添加链接
在第 276-280 行之间添加：
```html
<li class="nav-item">
  <a class="nav-link" href="#新部分ID">新菜单名</a>
</li>
```

### 步骤 2: 在内容区域添加新部分
在第 454 行之前（Internships 之后）添加：
```html
<h2 id="新部分ID">🎯 新部分标题</h2>
<p>你的内容...</p>
<ul>
  <li>列表项1</li>
  <li>列表项2</li>
</ul>
```

---

## 🎨 样式修改

### 修改主题颜色
**位置**: 第 28-252 行的 `<style>` 标签内

**主要颜色**:
- 蓝色主题: `#3498db` (搜索并替换)
- 深色文字: `#2c3e50`
- 灰色文字: `#7f8c8d`
- 背景色: `#fafafa`

### 修改边栏宽度
**位置**: 第 299 行
```html
width: 260px;  /* 改为你想要的宽度 */
```

---

## 📸 图片管理

### 个人照片
**文件路径**: `/images/profile.jpg`
**建议尺寸**: 400x400 像素（正方形）
**文件格式**: JPG 或 PNG
**文件大小**: 50-200KB

### 更换照片
1. 将新照片命名为 `profile.jpg`
2. 放到 `images/` 文件夹
3. 提交到 GitHub

---

## 🚀 快速修改流程

### 标准流程
1. **打开文件**: `index.html`
2. **找到位置**: 使用行号定位
3. **修改内容**: 编辑对应部分
4. **本地测试**: 浏览器打开 `index.html` 预览
5. **提交更改**:
   ```bash
   git add index.html
   git commit -m "更新内容"
   git push origin master
   ```
6. **查看网站**: 1-2分钟后访问 https://Jim3503.github.io

---

## 📝 常见修改示例

### 示例 1: 添加新论文
在第 386 行后添加：
```html
<li>
  <strong>My New Paper: Novel Deep Learning Approach</strong><br />
  <span style="color: #3498db;">Ming Ji</span>, John Doe<br />
  <i>CVPR 2026</i>, 2026.<br />
  <a href="https://arxiv.org/abs/xxxx.xxxxx" target="_blank">[Paper]</a>
  <a href="https://github.com/Jim3503/new-paper" target="_blank">[Code]</a>
</li>
```

### 示例 2: 添加新项目
在第 408 行后添加：
```html
<li>
  <strong>My Awesome Project</strong><br />
  <span style="color: #7f8c8d;">Research Project • 2025</span><br />
  <span style="font-size: 0.95em;">
    Developed a novel system for XYZ problem using ABC technology.
    Achieved 95% accuracy on test set.<br />
    <a href="https://github.com/Jim3503/awesome-project" target="_blank" style="color: #3498db;">[GitHub]</a>
  </span>
</li>
```

### 示例 3: 更新联系方式
修改第 314-315 行：
```html
<svg ...></svg> <a href="mailto:你的新邮箱">你的新邮箱</a><br />
<svg ...></svg> <a href="https://你的新链接.com">你的新链接</a>
```

---

## ⚠️ 注意事项

1. **保持格式**: 严格遵守HTML格式，不要破坏标签结构
2. **行号参考**: 行号可能会变化，用标题内容来定位更准确
3. **备份重要**: 修改前可以先备份文件
4. **本地测试**: 一定要在本地浏览器测试后再推送
5. **提交信息**: 写清楚修改了什么内容

---

## 🆘 需要帮助？

如果遇到问题：
1. 检查HTML标签是否完整
2. 确保链接格式正确
3. 在本地浏览器测试
4. 查看浏览器控制台是否有错误

---

## 📊 快速查找表

| 想要修改... | 位置 | 行号范围 |
|------------|------|---------|
| 个人信息 | 侧边栏 | 299-318 |
| 导航菜单 | navbar | 266-280 |
| 关于我 | #about | 329-336 |
| 教育背景 | #education | 338-362 |
| 荣誉奖项 | #honors | 364-374 |
| 论文发表 | #publications | 377-397 |
| 项目经历 | #projects | 400-430 |
| 实习经历 | #internships | 432-454 |

---

**记住**: 只需要修改 `index.html` 这一个文件就可以了！ 🎯
