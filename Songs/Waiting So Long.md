---
tags: Song  
banner: "![[..Famous Last Words.. (1982).jpg]]"
---
[Time:: 6:35]
[Artist:: [[Supertramp]] ]
[Genre:: Progressive Rock]
[Played:: 5]
[Album:: [[..Famous Last Words.. (1982)]]]
[Year:: 1982]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[Waiting So Long]]
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
		intensity: page["Waiting_So_Long"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
