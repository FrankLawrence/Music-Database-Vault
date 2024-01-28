---
tags: Song ⭐⭐ 
banner: "![[All The Best (1976).jpg]]"
---
[Time:: 5:55]
[Artist:: [[Wings]] ]
[Genre:: Pop]
[Played:: 1]
[Album:: [[All The Best (1976)]]]
[Year:: 1976]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[Silly Love Songs]]
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
		intensity: page["Silly_Love_Songs"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
