---
tags: Song  
banner: "![[Ultimate FM Gold (2022).jpg]]"
---
[Time:: 3:54]
[Artist:: [[Rose Royce]] ]
[Genre:: Pop]
[Played:: 23]
[Album:: [[Ultimate FM Gold (2022)]]]
[Year:: 2022]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[Love Don't Live Here Anymore]]
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
		intensity: page["Love_Don't_Live_Here_Anymore"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
