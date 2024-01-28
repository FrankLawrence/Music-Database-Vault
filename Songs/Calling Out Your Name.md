---
tags: Song ⭐⭐⭐⭐ 
banner: "![[Some Kind of Trouble (2010).jpg]]"
---
[Time:: 3:23]
[Artist:: [[James Blunt]] ]
[Genre:: ]
[Played:: 2]
[Album:: [[Some Kind of Trouble (2010)]]]
[Year:: 2010]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[Calling Out Your Name]]
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
		intensity: page["Calling_Out_Your_Name"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
