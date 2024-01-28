---
tags: Song ⭐⭐ 
banner: "![[Ring Ring (1973).jpg]]"
---
[Time:: 3:11]
[Artist:: [[ABBA]] ]
[Genre:: Pop]
[Played:: ]
[Album:: [[Ring Ring (1973)]]]
[Year:: 1973]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[Ring Ring (German Version)]]
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
		intensity: page["Ring_Ring_(German_Version)"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
