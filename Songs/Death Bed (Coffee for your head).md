---
tags: Song ⭐⭐⭐⭐ 
banner: "![[Poems of the Past (2020).jpg]]"
---
[Time:: 2:54]
[Artist:: [[Powfu]] [[beabadoobee]] ]
[Genre:: Lo-fi hip hop]
[Played:: 6]
[Album:: [[Poems of the Past (2020)]]]
[Year:: 2020]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[Death Bed (Coffee for your head)]]
````

  ```dataviewjs
const calendarData = { 
	colors: { 
		blue: ["#9ccfd8", "#5BAAB8", "#57A1BB", "#5da8c7", "#3e8fb0"] 
	}, 
	entries: [] 
}; 

for (let page of dv.pages('"Daily Notes"')) { 
	calendarData.entries.push({ 
		date: page.file.name, 
		intensity: page["Death_Bed_(Coffee_for_your_head)"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
