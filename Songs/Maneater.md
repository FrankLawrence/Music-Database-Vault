---
tags: Song ⭐⭐⭐⭐⭐ 
banner: "![[ArtistCollection (1982).jpg]]"
---
[Time:: 4:36]
[Artist:: [[Hall & Oates]] ]
[Genre:: Pop]
[Played:: 3]
[Album:: [[ArtistCollection (1982)]]]
[Year:: 1982]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[Maneater]]
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
		intensity: page["Maneater"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
