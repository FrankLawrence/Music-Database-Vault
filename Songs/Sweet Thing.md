---
tags: Song  
banner: "![[Jazz (1975).jpg]]"
---
[Time:: 3:58]
[Artist:: [[Chaka Khan]] ]
[Genre:: Jazz]
[Played:: ]
[Album:: [[Jazz (1975)]]]
[Year:: 1975]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[Sweet Thing]]
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
		intensity: page["Sweet_Thing"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
