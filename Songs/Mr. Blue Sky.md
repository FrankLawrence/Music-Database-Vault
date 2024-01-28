---
tags: Song ⭐⭐⭐⭐ 
banner: "![[Out of the Blue (1977).jpg]]"
---
[Time:: 5:06]
[Artist:: [[Electric Light Orchestra]] ]
[Genre:: Rock]
[Played:: 4]
[Album:: [[Out of the Blue (1977)]]]
[Year:: 1977]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[Mr. Blue Sky]]
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
		intensity: page["Mr._Blue_Sky"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
