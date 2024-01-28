---
tags: Song ⭐⭐⭐⭐ 
banner: "![[The Very Best Of Sandra [Disc 1] (2016).jpg]]"
---
[Time:: 3:58]
[Artist:: [[Sandra]] ]
[Genre:: Pop]
[Played:: 2]
[Album:: [[The Very Best Of Sandra [Disc 1] (2016)]]]
[Year:: 2016]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[(I'll Never Be) Maria Magdalena]]
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
		intensity: page["(I'll_Never_Be)_Maria_Magdalena"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
