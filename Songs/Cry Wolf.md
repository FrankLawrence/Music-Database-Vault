---
tags: Song ⭐⭐⭐⭐ 
banner: "![[Scoundrel Days (1986).jpg]]"
---
[Time:: 4:08]
[Artist:: [[A-ha]] ]
[Genre:: Pop Rock]
[Played:: ]
[Album:: [[Scoundrel Days (1986)]]]
[Year:: 1986]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[Cry Wolf]]
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
		intensity: page["Cry_Wolf"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
