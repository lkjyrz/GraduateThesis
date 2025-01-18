```dataview
Table without ID 
	file.link as "名称",
	file.mday as "上次修改日期",
	Finish,
	Chapter
Where 
	file.name != "开题报告" and
	file.name != "文献综述" and
	file.name != "README" and
	file.name != "Todo List" and
	file.name != "View of All"
Group By Chapter
```

```dataview

```