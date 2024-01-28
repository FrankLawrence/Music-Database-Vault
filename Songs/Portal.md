---
tags: Song ⭐⭐⭐⭐ 
banner: "![[Max W (2019).jpg]]"
---
[Time:: 3:53]
[Artist:: [[Max W & Meikle]] ]
[Genre:: ]
[Played:: 3]
[Album:: [[Max W (2019)]]]
[Year:: 2019]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[Portal]]
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
		intensity: page["Portal"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
