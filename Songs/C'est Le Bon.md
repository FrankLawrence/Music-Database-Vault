---
tags: Song  
banner: "![[..Famous Last Words.. (1982).jpg]]"
---
[Time:: 5:32]
[Artist:: [[Supertramp]] ]
[Genre:: Progressive Rock]
[Played:: ]
[Album:: [[..Famous Last Words.. (1982)]]]
[Year:: 1982]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[C'est Le Bon]]
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
		intensity: page["C'est_Le_Bon"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
