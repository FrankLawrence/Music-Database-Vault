---
tags: Song ⭐⭐⭐ 
banner: "![[Very Best Of The Bee Gees (1990).jpg]]"
---
[Time:: 3:07]
[Artist:: [[Bee Gees]] ]
[Genre:: Pop]
[Played:: 2]
[Album:: [[Very Best Of The Bee Gees (1990)]]]
[Year:: 1990]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[Saved By The Bell]]
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
		intensity: page["Saved_By_The_Bell"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
