---
tags: Song ⭐⭐⭐ 
banner: "![[Aqualung (1971).jpg]]"
---
[Time:: 6:35]
[Artist:: [[Jethro Tull]] ]
[Genre:: Progressive Rock]
[Played:: 1]
[Album:: [[Aqualung (1971)]]]
[Year:: 1971]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[Aqualung]]
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
		intensity: page["Aqualung"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
