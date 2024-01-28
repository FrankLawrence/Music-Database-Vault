---
tags: Song ⭐⭐⭐⭐ 
banner: "![[Time Flies.. The Best of Huey Lewis & The News (1996).jpg]]"
---
[Time:: 3:55]
[Artist:: [[Huey Lewis & The News]] ]
[Genre:: Rock]
[Played:: 1]
[Album:: [[Time Flies.. The Best of Huey Lewis & The News (1996)]]]
[Year:: 1996]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[The Power Of Love]]
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
		intensity: page["The_Power_Of_Love"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
