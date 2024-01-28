---
tags: Song ⭐⭐⭐ 
banner: "![[Some Nights (2013).jpg]]"
---
[Time:: 16:48]
[Artist:: [[Fun]] ]
[Genre:: Rock/Pop]
[Played:: ]
[Album:: [[Some Nights (2013)]]]
[Year:: 2013]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[We Are Young (Ft. Janelle Monáe)]]
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
		intensity: page["We_Are_Young_(Ft._Janelle_Monáe)"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
