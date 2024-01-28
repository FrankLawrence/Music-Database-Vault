---
tags: Song ⭐⭐⭐⭐ 
banner: "![[On Her Majesty's Secret Service (1969).jpg]]"
---
[Time:: 3:13]
[Artist:: [[Louis Armstrong]] ]
[Genre:: Jazz]
[Played:: 6]
[Album:: [[On Her Majesty's Secret Service (1969)]]]
[Year:: 1969]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[We Have All The Time In The World]]
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
		intensity: page["We_Have_All_The_Time_In_The_World"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
