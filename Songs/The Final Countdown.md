---
tags: Song ⭐⭐⭐⭐ 
banner: "![[The Final Countdown (1986).jpg]]"
---
[Time:: 4:56]
[Artist:: [[Europe]] ]
[Genre:: Hard Rock]
[Played:: 13]
[Album:: [[The Final Countdown (1986)]]]
[Year:: 1986]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[The Final Countdown]]
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
		intensity: page["The_Final_Countdown"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
