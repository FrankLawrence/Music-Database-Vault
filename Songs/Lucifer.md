---
tags: Song ⭐⭐⭐⭐⭐ 
banner: "![[The Best Of The Alan Parsons Project (1979).jpg]]"
---
[Time:: 4:10]
[Artist:: [[Alan Parsons Project]] ]
[Genre:: Pop]
[Played:: 13]
[Album:: [[The Best Of The Alan Parsons Project (1979)]]]
[Year:: 1979]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[Lucifer]]
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
		intensity: page["Lucifer"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
