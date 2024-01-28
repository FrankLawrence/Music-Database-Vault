---
tags: Song  
banner: "![[Twenty Five (2006).jpg]]"
---
[Time:: 4:24]
[Artist:: [[George Michael]] ]
[Genre:: Pop]
[Played:: ]
[Album:: [[Twentyfive (2006)]]]
[Year:: 2006]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[John And Elvis Are Dead]]
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
		intensity: page["John_And_Elvis_Are_Dead"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
