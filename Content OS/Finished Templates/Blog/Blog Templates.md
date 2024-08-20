```dataview
TABLE WITHOUT ID file.link AS "Page", file.mtime AS "Last Modified" FROM #Blog-Content WHERE file.name != "Templatized Content Template"SORT file.mtime DESC
```
