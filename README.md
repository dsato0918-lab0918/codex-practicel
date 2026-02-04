# codex-practicel

建築・不動産AI OSのNotion構成（案件DB／AI判断ログDB／施主要望DB／トラブル予測DB）を
MarkdownまたはJSONで出力するテンプレジェネレーターです。

## 使い方

```bash
python notion_os.py --format md --output notion_template.md
python notion_os.py --format json --output notion_schema.json
```

## 出力ファイル

- `notion_template.md`: Notionに貼り付け可能なテンプレ本文。
- `notion_schema.json`: DB構造とテンプレ本文をまとめたJSON。
