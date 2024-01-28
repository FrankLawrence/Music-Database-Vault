---
tags: Song ⭐ 
banner: "![[30 #1 Hits (1961).jpg]]"
---
[Time:: 2:09]
[Artist:: [[Elvis Presley]] ]
[Genre:: Rock]
[Played:: 1]
[Album:: [[30 #1 Hits (1961)]]]
[Year:: 1961]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[(Marie's The Name) His Latest Flame]]
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
		intensity: page["(Marie's_The_Name)_His_Latest_Flame"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
