---
tags: Song ⭐⭐⭐ 
banner: "![[Küssen verboten (1992).jpg]]"
---
[Time:: 3:05]
[Artist:: [[Die Prinzen]] ]
[Genre:: German Rock-Pop]
[Played:: ]
[Album:: [[Küssen verboten (1992)]]]
[Year:: 1992]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[Warum hast du das getan]]
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
		intensity: page["Warum_hast_du_das_getan"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
