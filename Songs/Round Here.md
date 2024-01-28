---
tags: Song  
banner: "![[Twenty Five (2006).jpg]]"
---
[Time:: 5:56]
[Artist:: [[George Michael]] ]
[Genre:: Pop]
[Played:: 2]
[Album:: [[Twentyfive (2006)]]]
[Year:: 2006]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[Round Here]]
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
		intensity: page["Round_Here"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
