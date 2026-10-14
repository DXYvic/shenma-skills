# 来源与修改

- 来源：[mizzlelover/gongwen-gbt9704-skill](https://github.com/mizzlelover/gongwen-gbt9704-skill)，提交 `6a5e47a9077d30aa62d6a1cd511bcac6887a7b75`。
- 本 Skill 保留并改编上游 `scripts/generate_gongwen_docx.mjs` 和 `references/gbt9704-2012-summary.md`。原作者为 mizzlelover（“谁是专家”），许可见根目录 `LICENSE`（MIT）。
- 本地改动：把原本仅调用 Unix `zip` 的 DOCX 打包过程增加 Windows PowerShell `Compress-Archive` 分支；完整电子红头增加三个定位网格行，修复在本机 Word 渲染时机关标志与文号重叠的问题。
- 公司制度 PDF 仅用于本地测试参考，没有复制进可分发 Skill。
