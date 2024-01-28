---
tags: Song ⭐⭐⭐⭐ 
banner: "![[Some Kind of Trouble (2010).jpg]]"
---
[Time:: 3:50]
[Artist:: [[James Blunt]] ]
[Genre:: ]
[Played:: 4]
[Album:: [[Some Kind of Trouble (2010)]]]
[Year:: 2010]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[No Tears]]
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
		intensity: page["No_Tears"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
