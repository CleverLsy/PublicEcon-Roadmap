# 🗺️ Public Economics Research Roadmap

## 🚦 急需解决的问题 (Urgent Issues)
> 这里的列表会自动抓取所有标记为 "Urgent" 的笔记。

```dataview
TABLE domain as "领域", link(file.link, title) as "问题", dateformat(file.mtime, "yyyy-MM-dd") as "最后更新"
FROM "10_Problem_Set"
WHERE contains(status, "Urgent")
SORT file.mtime DESC
```

## 🌳 知识树概览 (按领域)
### 🏛️ Taxation (税收)
```dataview
LIST FROM "10_Problem_Set/Taxation"
```
## 📉 最近收录的文献
```dataview
TABLE year as "年份", journal as "期刊"
FROM "20_Literature_Notes"
SORT file.ctime DESC
LIMIT 5
```
