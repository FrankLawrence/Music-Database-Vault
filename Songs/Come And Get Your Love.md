---
tags: Song ⭐⭐⭐⭐⭐ 💛
banner: "![[Wovoka (1973).jpg]]"
---
[Time:: 3:27]
[Artist:: [[Redbone]] ]
[Genre:: Pop Rock]
[Played:: 15]
[Album:: [[Wovoka (1973)]]]
[Year:: 1973]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[Come And Get Your Love]]
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
		intensity: page["Come_And_Get_Your_Love"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
