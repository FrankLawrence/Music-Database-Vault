---
tags: Song ⭐⭐⭐⭐⭐ 
banner: "![[A Rush of Blood To The Head (2002).jpg]]"
---
[Time:: 4:30]
[Artist:: [[Coldplay]] ]
[Genre:: Rock]
[Played:: 36]
[Album:: [[A Rush of Blood To The Head (2002)]]]
[Year:: 2002]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[Clocks]]
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
		intensity: page["Clocks"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
