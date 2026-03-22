# 🎯 快速修改参考卡

## 📁 唯一文件：`index.html`

## 🔥 最常修改的部分

### 📝 添加新论文
**位置**: 第 377-397 行
**方法**: 在 `<ol>` 标签内添加新的 `<li>` 标签

```html
<li>
  <strong>论文标题</strong><br />
  <span style="color: #3498db;">作者</span><br />
  <i>会议/期刊</i>, 年份.<br />
  <a href="链接">[Paper]</a>
</li>
```

---

### 🚀 添加新项目
**位置**: 第 400-430 行
**方法**: 在 `<ul>` 标签内添加新的 `<li>` 标签

```html
<li>
  <strong>项目名称</strong><br />
  <span style="color: #7f8c8d;">类型 • 年份</span><br />
  <span>项目描述... <a href="链接">[GitHub]</a></span>
</li>
```

---

### 💼 添加新实习
**位置**: 第 432-454 行
**方法**: 在最后添加新的实习段落

```html
<h3>职位</h3>
<p>
  <strong>公司</strong>, 城市 (时间)<br />
  <span>描述</span>
</p>
<ul>
  <li>工作1</li>
  <li>工作2</li>
</ul>
```

---

### 🎓 添加教育经历
**位置**: 第 338-362 行
**方法**: 在 `<tbody>` 内添加新的 `<tr>`

```html
<tr>
  <td>2020 - 2024</td>
  <td>学校名称</td>
  <td>专业</td>
  <td>学位</td>
</tr>
```

---

### 🏆 添加新奖项
**位置**: 第 364-374 行
**方法**: 在 `<ul>` 内添加新的 `<li>`

```html
<li><span class="award">🏅</span> 奖项名称</li>
```

---

## ⚡ 快速命令

### 修改后提交
```bash
git add index.html
git commit -m "更新内容"
git push origin master
```

### 本地预览
```bash
open index.html
```

---

## 📋 部分ID对照表

| ID | 名称 | 用途 |
|----|------|------|
| #about | About Me | 个人介绍 |
| #education | Education | 教育背景 |
| #honors | Honors & Awards | 荣誉奖项 |
| #publications | Publications | 论文发表 |
| #projects | Projects | 项目经历 |
| #internships | Internships | 实习经历 |

---

## 🎨 常用样式

### 蓝色高亮作者名
```html
<span style="color: #3498db; font-weight: 500;">作者名</span>
```

### 灰色副标题
```html
<span style="color: #7f8c8d; font-size: 0.95em;">副标题</span>
```

### GitHub链接
```html
<a href="https://github.com/..." target="_blank" style="color: #3498db;">[GitHub]</a>
```

---

## 📸 更换照片

1. 准备照片 (400x400px 推荐)
2. 命名为 `profile.jpg`
3. 放入 `images/` 文件夹
4. 提交到 GitHub

---

## ⚠️ 重要提示

1. **只需修改 `index.html`**
2. **保持HTML结构完整**
3. **本地测试后再推送**
4. **论文和项目按时间倒序**（最新的在上面）

---

**详细指南**: 查看 `EDITING_GUIDE.md`
