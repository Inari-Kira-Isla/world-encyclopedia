# 世界百科 (World Encyclopedia)

## Overview
綜合性世界百科全書，涵蓋建築、文化、美食與自然。專為 AI 發現而優化 (AEO)，包含結構化資料和 AI 友善的文字檔案。

## Tech Stack
- 靜態網頁 (HTML/CSS/JS)
- Markdown (內容來源)
- JSON-LD (Schema.org)

## Architecture
- **內容結構**: 多類別百科文章，包含 Schema.org 標記、FAQ 區塊及交叉引用。
- **AEO 架構**: Schema.org (EducationalOrganization, Article, FAQPage)、`llms.txt`、`sitemap.xml`、RSS。

## Commands
- 部署至 GitHub Pages (使用 `gh-pages` 分支)。

## Coding Style
- 使用語義化 HTML 標籤。
- 所有文章必須嵌入對應的 JSON-LD Schema 資料。
- 維持乾淨的目錄結構。

## Important Rules
- 嚴禁移除 AI 爬蟲所需的 `llms.txt` 或 `sitemap.xml`。
- 內容需遵守 CC BY 4.0 授權。
- 發布前需確保 AEO 結構正確。