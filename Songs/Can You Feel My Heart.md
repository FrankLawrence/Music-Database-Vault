---
tags: Song ⭐⭐⭐⭐⭐ 💛
banner: "![[Sempiternal (2013).jpg]]"
---
[Time:: 3:48]
[Artist:: [[Bring Me The Horizon]] ]
[Genre:: Rock]
[Played:: 47]
[Album:: [[Sempiternal (2013)]]]
[Year:: 2013]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[Can You Feel My Heart]]
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
		intensity: page["Can_You_Feel_My_Heart"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
