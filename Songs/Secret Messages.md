---
tags: Song ⭐⭐⭐⭐⭐ 💛
banner: "![[Secret Messages (1983).jpg]]"
---
[Time:: 4:50]
[Artist:: [[Electric Light Orchestra]] ]
[Genre:: Rock, Pop]
[Played:: 83]
[Album:: [[Secret Messages (1983)]]]
[Year:: 1983]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[Secret Messages]]
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
		intensity: page["Secret_Messages"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
