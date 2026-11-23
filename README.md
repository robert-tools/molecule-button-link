# 🗂️ @robert.tools/molecule-button-link

A Component to provide a wrapper between button and link.

## 📜 Usage

### 🟢 Installation

```bash
npm install @robert.tools/molecule-button-link
```

#### 🔐 dependencies

- [Component: molecule-link](https://github.com/robert-tools/molecule-link)
- [Component: atom-button](https://github.com/robert-tools/atom-button)
- [Filter: safeParam](https://github.com/robert-tools/eleventy-filter-safe-param)
- [Filter: svg](https://github.com/robert-tools/eleventy-filter-svg)
- [Filter: merge](https://github.com/robert-tools/eleventy-filter-merge)

### 📝 Sample usage

#### prerequisites

- define css variables

#### Template

Use the footer component as shown below:

```html
{{ component("molecule/button-link", {
    "type": "link",
    "text": "My Button",
    "url": "https://example.com",
    "disabled": false
}) }}
```

##### ⚙️ parameter

- **class**: CSS class for the link-button
- **class_modifier**: CSS class modifier for the link-button
- **url**: URL of the link-button
- **target**: target attribute of the link-button
- **disabled**: whether the link-button is disabled
- **text**: text of the link-button
- **collapseID**: ID for collapsible content
- **collapseShow**: whether the collapsible content is shown
- **type_content**: type of content within the link-button
- **pre_html**: HTML to be inserted before the link-button
- **post_html**: HTML to be inserted after the link-button
- **attributes**: additional attributes for the link-button

#### CSS

Use the basic styling

```css
@import '@robert.tools/molecule-button-link/src/index.css';
```

#### TypeScript

Include TypeScript by importing the component

```typescript
import * as MoleculeButtonLink from '@robert.tools/molecule-button-link';
```


## ⚖️ Notes

This software is hand-crafted, test-driven and assisted by AI tools. I know each
line of my code. ✌️

| Tool | Comment |
| --- | --- |
| ![assisted by Jest](https://img.shields.io/badge/Jest-TDD-008800?logo=jest) | Test-driven development with Jest |
| ![assisted by robert.tools](https://img.shields.io/badge/robert.tools-ecosystem-008800) | Part of the robert.tools ecosystem |
| ![assisted by GitHub Copilot](https://img.shields.io/badge/GitHub_Copilot-assisted-8A2BE2?logo=githubcopilot) | Code completion |
| ![assisted by OpenAI](https://img.shields.io/badge/OpenAI-assisted-8A2BE2?logo=openai) | chatGPT research |
