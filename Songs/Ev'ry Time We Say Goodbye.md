---
tags: Song  
banner: "![[Jazz (1956).jpg]]"
---
[Time:: 3:32]
[Artist:: [[Ella Fitzgerald]] ]
[Genre:: Jazz]
[Played:: ]
[Album:: [[Jazz (1956)]]]
[Year:: 1956]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[Ev'ry Time We Say Goodbye]]
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
		intensity: page["Ev'ry_Time_We_Say_Goodbye"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
