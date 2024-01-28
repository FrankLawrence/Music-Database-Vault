---
tags: Song ⭐⭐⭐ 
banner: "![[The Very Best Of Smooth Jazz [Disc 1] (2001).jpg]]"
---
[Time:: 4:07]
[Artist:: [[Freddie Ravel]] ]
[Genre:: Jazz]
[Played:: ]
[Album:: [[The Very Best Of Smooth Jazz [Disc 1] (2001)]]]
[Year:: 2001]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[Sunny Side Up]]
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
		intensity: page["Sunny_Side_Up"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
