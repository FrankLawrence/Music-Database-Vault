---
tags: Song ⭐⭐⭐ 
banner: "![[Scoundrel Days (1986).jpg]]"
---
[Time:: 3:13]
[Artist:: [[A-ha]] ]
[Genre:: Pop Rock]
[Played:: 4]
[Album:: [[Scoundrel Days (1986)]]]
[Year:: 1986]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[Soft Rains of April]]
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
		intensity: page["Soft_Rains_of_April"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
