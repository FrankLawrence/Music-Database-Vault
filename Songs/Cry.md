---
tags: Song ⭐⭐⭐⭐ 
banner: "![[Back to Bedlam (2004).jpg]]"
---
[Time:: 4:07]
[Artist:: [[James Blunt]] ]
[Genre:: Pop Rock]
[Played:: 2]
[Album:: [[Back to Bedlam (2004)]]]
[Year:: 2004]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[Cry]]
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
		intensity: page["Cry"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
