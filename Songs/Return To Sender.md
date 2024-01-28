---
tags: Song ⭐⭐⭐⭐⭐ 
banner: "![[30 #1 Hits (1962).jpg]]"
---
[Time:: 2:11]
[Artist:: [[Elvis Presley]] ]
[Genre:: Rock]
[Played:: 10]
[Album:: [[30 #1 Hits (1962)]]]
[Year:: 1962]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[Return To Sender]]
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
		intensity: page["Return_To_Sender"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
