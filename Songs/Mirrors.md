---
tags: Song ⭐⭐⭐⭐ 
banner: "![[The 20/20 Experience (2014).jpg]]"
---
[Time:: 4:35]
[Artist:: [[Justin Timberlake]] ]
[Genre:: Rock/Pop]
[Played:: ]
[Album:: [[The 20/20 Experience (2014)]]]
[Year:: 2014]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[Mirrors]]
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
		intensity: page["Mirrors"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
