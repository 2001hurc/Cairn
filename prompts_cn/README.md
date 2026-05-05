# Cairn 项目提示词 - 中文翻译

本文件夹包含 Cairn 项目中所有提示词的中文翻译版本。

## 文件结构

```
prompts_cn/
├── default/          # 正式使用的提示词
│   ├── bootstrap.md
│   ├── bootstrap_conclude.md
│   ├── reason.md
│   ├── explore.md
│   └── explore_conclude.md
└── mock/            # 测试用的 JSON 格式提示词
    ├── bootstrap.md
    ├── bootstrap_conclude.md
    ├── reason.md
    ├── explore.md
    └── explore_conclude.md
```

## 说明

- **default/**：实际项目中使用的 Markdown 格式提示词
- **mock/**：测试时使用的 JSON 格式提示词（保持原样未翻译）

## 原文位置

原文提示词文件位于：
- [cairn/src/cairn/dispatcher/prompts/](../cairn/src/cairn/dispatcher/prompts/)
