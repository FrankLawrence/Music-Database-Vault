---
tags: Song ⭐⭐⭐⭐⭐ 
banner: "![[ArtistCollection (1976).jpg]]"
---
[Time:: 2:26]
[Artist:: [[Hall & Oates]] ]
[Genre:: Pop]
[Played:: 17]
[Album:: [[ArtistCollection (1976)]]]
[Year:: 1976]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[Rich Girl]]
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
		intensity: page["Rich_Girl"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
