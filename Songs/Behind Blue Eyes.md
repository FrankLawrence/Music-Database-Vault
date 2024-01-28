---
tags: Song ⭐⭐⭐⭐⭐ 💛
banner: "![[Who's Next (1971).jpg]]"
---
[Time:: 3:42]
[Artist:: [[The Who]] ]
[Genre:: Hard Rock]
[Played:: 17]
[Album:: [[Who's Next (1971)]]]
[Year:: 1971]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[Behind Blue Eyes]]
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
		intensity: page["Behind_Blue_Eyes"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
