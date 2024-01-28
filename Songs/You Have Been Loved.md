---
tags: Song  
banner: "![[Twenty Five (2006).jpg]]"
---
[Time:: 5:29]
[Artist:: [[George Michael]] ]
[Genre:: Pop]
[Played:: 2]
[Album:: [[Twentyfive (2006)]]]
[Year:: 2006]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[You Have Been Loved]]
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
		intensity: page["You_Have_Been_Loved"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
