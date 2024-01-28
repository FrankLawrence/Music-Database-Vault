---
tags: Song ⭐⭐⭐⭐⭐ 
banner: "![[The Marshall Mathers LP (2000).jpg]]"
---
[Time:: 4:28]
[Artist:: [[Eminem]] ]
[Genre:: Hip-Hop/Rap]
[Played:: 12]
[Album:: [[The Marshall Mathers LP (2000)]]]
[Year:: 2000]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[Real Slim Shady]]
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
		intensity: page["Real_Slim_Shady"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
