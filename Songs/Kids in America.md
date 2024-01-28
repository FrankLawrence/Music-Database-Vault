---
tags: Song ⭐⭐⭐⭐ 
banner: "![[Die 80er Show 2 CD2 (2002).jpg]]"
---
[Time:: 3:24]
[Artist:: [[Kim Wilde]] ]
[Genre:: ]
[Played:: ]
[Album:: [[Die 80er Show 2 CD2 (2002)]]]
[Year:: 2002]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[Kids in America]]
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
		intensity: page["Kids_in_America"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
