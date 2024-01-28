---
tags: Song ⭐⭐⭐⭐⭐ 
banner: "![[Eye In The Sky (1982).jpg]]"
---
[Time:: 4:37]
[Artist:: [[Alan Parsons Project]] ]
[Genre:: Rock]
[Played:: 46]
[Album:: [[Eye In The Sky (1982)]]]
[Year:: 1982]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[Eye In The Sky]]
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
		intensity: page["Eye_In_The_Sky"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
