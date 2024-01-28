---
tags: Song ⭐⭐⭐⭐⭐ 
banner: "![[Some Kind of Trouble (2010).jpg]]"
---
[Time:: 3:01]
[Artist:: [[James Blunt]] ]
[Genre:: ]
[Played:: 8]
[Album:: [[Some Kind of Trouble (2010)]]]
[Year:: 2010]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[This Love Again]]
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
		intensity: page["This_Love_Again"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
