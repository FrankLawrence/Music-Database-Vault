---
tags: Song ⭐⭐⭐⭐ 
banner: "![[Bee Gees' 1st (1967).jpg]]"
---
[Time:: 2:12]
[Artist:: [[Bee Gees]] ]
[Genre:: Psychedelic Pop]
[Played:: 4]
[Album:: [[Bee Gees' 1st (1967)]]]
[Year:: 1967]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[New York Mining Disaster 1941]]
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
		intensity: page["New_York_Mining_Disaster_1941"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
