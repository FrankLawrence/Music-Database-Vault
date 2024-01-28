---
tags: Song ⭐⭐⭐⭐⭐ 
banner: "![[Back to Bedlam (2004).jpg]]"
---
[Time:: 3:37]
[Artist:: [[James Blunt]] ]
[Genre:: Pop Rock]
[Played:: 3]
[Album:: [[Back to Bedlam (2004)]]]
[Year:: 2004]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[Billy]]
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
		intensity: page["Billy"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
