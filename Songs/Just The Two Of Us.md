---
tags: Song ⭐⭐⭐⭐⭐ 💛
banner: "![[Winelight (1981).jpg]]"
---
[Time:: 3:18]
[Artist:: [[Grover Washington Jr. & Bill Withers]] ]
[Genre:: R&B]
[Played:: 67]
[Album:: [[Winelight (1981)]]]
[Year:: 1981]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[Just The Two Of Us]]
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
		intensity: page["Just_The_Two_Of_Us"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
