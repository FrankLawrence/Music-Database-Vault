---
tags: Song ⭐⭐⭐⭐ 
banner: "![[1 (2000).jpg]]"
---
[Time:: 3:03]
[Artist:: [[The Beatles]] ]
[Genre:: ]
[Played:: ]
[Album:: [[1 (2000)]]]
[Year:: 2000]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[Ticket To Ride]]
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
		intensity: page["Ticket_To_Ride"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
