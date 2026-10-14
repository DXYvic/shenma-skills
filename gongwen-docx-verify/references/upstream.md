# 来源与修改

- 来源：[mizzlelover/gongwen-gbt9704-skill](https://github.com/mizzlelover/gongwen-gbt9704-skill)，提交 `6a5e47a9077d30aa62d6a1cd511bcac6887a7b75`。
- 本 Skill 保留并改编上游 `scripts/verify_gongwen_docx.mjs` 和 `references/gbt9704-audit-matrix.md`。原作者为 mizzlelover（“谁是专家”），许可见根目录 `LICENSE`（MIT）。
- 本地改动：为 DOCX 内部 XML 读取增加 Windows 系统 `tar` 分支；Unix 平台沿用 `unzip`。增加电子红头 Word 定位网格检查，用于拦截上游版本在本机 Word 中出现的机关标志与文号重叠。版记检测改为识别实际的底部定位表格，避免把正文标题中的“印发”误判为版记。Skill 指令明确限定此脚本主要适用于同源生成器结果。
- 公司制度 PDF 仅用于本地测试参考，没有复制进可分发 Skill。
