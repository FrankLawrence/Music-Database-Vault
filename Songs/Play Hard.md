---
tags: Song ⭐⭐⭐⭐⭐ 
banner: "![[Nothing but the Beat 2.0 (2012).jpg]]"
---
[Time:: 3:29]
[Artist:: [[David Guetta]] [[Ne-Yo & Akon]] ]
[Genre:: Electro House]
[Played:: 3]
[Album:: [[Nothing but the Beat 2.0 (2012)]]]
[Year:: 2012]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[Play Hard]]
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
		intensity: page["Play_Hard"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
