---
tags: Song ⭐⭐⭐⭐⭐ 💛
banner: "![[The slow rush (2020).jpg]]"
---
[Time:: 4:10]
[Artist:: [[Tame Impala]] ]
[Genre:: Psychedelic Pop]
[Played:: 41]
[Album:: [[The slow rush (2020)]]]
[Year:: 2020]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[Lost in Yesterday]]
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
		intensity: page["Lost_in_Yesterday"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
