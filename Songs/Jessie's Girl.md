---
tags: Song  
banner: "![[Working Class Dog (1981).jpg]]"
---
[Time:: 3:12]
[Artist:: [[Rick Springfield]] ]
[Genre:: Power pop]
[Played:: 1]
[Album:: [[Working Class Dog (1981)]]]
[Year:: 1981]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[Jessie's Girl]]
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
		intensity: page["Jessie's_Girl"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
