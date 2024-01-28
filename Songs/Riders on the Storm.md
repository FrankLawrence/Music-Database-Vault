---
tags: Song ⭐⭐⭐⭐⭐ 💛
banner: "![[L.A. Woman (1971).jpg]]"
---
[Time:: 7:14]
[Artist:: [[The Doors]] ]
[Genre:: Classic Rock]
[Played:: 59]
[Album:: [[L.A. Woman (1971)]]]
[Year:: 1971]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[Riders on the Storn]]
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
		intensity: page["Riders_on_the_Storm"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
