---
tags: Song ⭐⭐⭐ 
banner: "![[The slow rush (2020).jpg]]"
---
[Time:: 4:35]
[Artist:: [[Tame Impala]] ]
[Genre:: Psychedelic Rock]
[Played:: 6]
[Album:: [[The slow rush (2020)]]]
[Year:: 2020]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[It Might Be Time]]
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
		intensity: page["It_Might_Be_Time"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
