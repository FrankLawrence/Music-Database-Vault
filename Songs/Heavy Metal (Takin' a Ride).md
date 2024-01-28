---
tags: Song ⭐⭐⭐⭐⭐ 
banner: "![[Heavy Metal: Music from the Motion Picture (1981).jpg]]"
---
[Time:: 4:53]
[Artist:: [[Don Felder]] ]
[Genre:: Hard Rock]
[Played:: 56]
[Album:: [[Heavy Metal: Music from the Motion Picture (1981)]]]
[Year:: 1981]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[Heavy Metal (Takin' a Ride)]]
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
		intensity: page["Heavy_Metal_(Takin'_a_Ride)"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
