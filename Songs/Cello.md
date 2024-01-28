---
tags: Song ⭐⭐⭐⭐ 
banner: "![[Alles klar auf der Andrea Doria (1973).jpg]]"
---
[Time:: 3:01]
[Artist:: [[Udo Lindenberg]] ]
[Genre:: German Rock-Pop]
[Played:: 1]
[Album:: [[Alles klar auf der Andrea Doria (1973)]]]
[Year:: 1973]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[Cello]]
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
		intensity: page["Cello"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
