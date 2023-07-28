---
tags: Song ⭐⭐⭐⭐⭐ 
---
[Time:: 3:44]
[Artist:: [[Modjo]] ]
[Genre:: French house]
[Played:: 24]
[Album:: [[Modjo (2000)]]]
[Year:: 2000]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[Lady (Hear Me Tonight)]]
````

```dataviewjs
const calendarData = {
	entries: []
}

let song_name = dv.current().file.name;

for(let page of dv.pages('"Daily Notes"').where(p => p.Favorite_Song == song_name)){
	calendarData.entries.push({
		data: page.file.name
	})
}

renderHeatmapCalendar(this.container, calendarData)
```

```dataviewjs
//dv.list(dv.pages('"Daily Notes"').where(p => p.Favorite_Song == dv.current().file.link))
dv.list(dv.pages('"Daily Notes"').where(p => p.file.name == "2023-03-13").Favorite_Song)

```
```dataviewjs
dv.span(dv.current().file.link)
```