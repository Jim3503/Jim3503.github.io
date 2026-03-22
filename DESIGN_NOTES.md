# Personal Website Design Update Notes

## Update Date
March 22, 2026

## Design Reference
Based on [XiaoBuL/xiaobul.github.io](https://xiaobul.github.io) layout design

## Major Changes

### 1. Page Structure
- ✅ Left fixed sidebar + right main content layout
- ✅ Top fixed navigation bar with anchor links
- ✅ Responsive design, sidebar auto-hides on mobile

### 2. Visual Design
- ✅ Modern clean color scheme (white background + light gray main background)
- ✅ Circular avatar with shadow effect
- ✅ Blue theme color (#3498db)
- ✅ Elegant transition animations

### 3. Content Organization
- ✅ About Me: Personal introduction and research interests
- ✅ Education: Table format display
- ✅ Honors & Awards: List format with emoji icons
- ✅ Publications: Reverse chronological order
- ✅ Projects: Research projects and internship projects
- ✅ Internships: Detailed work experience

### 4. Technical Implementation
- ✅ Pure HTML + CSS + JavaScript
- ✅ Bootstrap 4 framework
- ✅ Custom CSS styles
- ✅ Smooth scrolling effects
- ✅ Fixed navigation bar and sidebar

## File Description

### index.html
Newly created homepage file, including:
- Complete HTML structure
- Inline CSS styles
- Responsive JavaScript code

### _pages/about.md
Original homepage file (kept as backup)

## Usage Instructions

### Local Preview
Simply open `index.html` file in browser

### Deploy to GitHub Pages
1. Ensure files are committed to repository
2. Enable GitHub Pages in repository settings
3. Select main branch as publishing source
4. Visit `https://Jim3503.github.io` to view

### Content Updates
- **Personal Info**: Modify sidebar section (lines 301-317)
- **Publications**: Modify `<ol>` list in publications section (lines 379-395)
- **Projects**: Modify `<ul>` list in projects section (lines 402-428)
- **Internships**: Modify internships section (lines 432-454)

## Customization Suggestions

### Change Theme Color
Search `#3498db` in `<style>` tag and replace with other color values

### Add More Social Links
Add new links in sidebar contact section (lines 314-315)

### Adjust Sidebar Width
Modify `width: 260px` in line 299 to other values

### Modify Navigation Items
Add or delete navigation links in `<nav>` section (lines 266-280)

## Compatibility
- ✅ Chrome/Edge (recommended)
- ✅ Firefox
- ✅ Safari
- ✅ Mobile browsers

## Future Improvements
- [ ] Add dark mode toggle
- [ ] Add visitor statistics
- [ ] Add blog functionality
- [ ] Optimize mobile experience
- [ ] Add multi-language support

## Featured Projects
- **Tradeclaw**: Multi-Agent Trading Review System - Intelligent trading analysis system for A-share market
- **Hierarchical RAG Framework**: Knowledge distillation framework for sign language translation
- **RAG Framework**: Retrieval-augmented generation for low-resource scenarios
- **Script Generation Agent**: LLM-based script creation system

## Contact
For questions or suggestions: ming.ji@zju.edu.cn
