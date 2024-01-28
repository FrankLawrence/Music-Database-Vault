---
tags: Song ⭐⭐⭐⭐ 
banner: "![[A Day at the Races (1976).jpg]]"
---
[Time:: 4:58]
[Artist:: [[Queen]] ]
[Genre:: Rock]
[Played:: 2]
[Album:: [[A Day at the Races (1976)]]]
[Year:: 1976]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[Somebody To Love]]
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
		intensity: page["Somebody_To_Love"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
