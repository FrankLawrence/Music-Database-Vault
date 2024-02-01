---
tags: Song ⭐⭐⭐⭐⭐ 💛
banner: "![[E.S.P. (1987).jpg]]"
---
[Time:: 3:58]
[Artist:: [[Bee Gees]] ]
[Genre:: Synth-Pop]
[Played:: 74]
[Album:: [[E.S.P. (1987)]]]
[Year:: 1987]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[You Win Again]]
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
		intensity: page["You_Win_Again"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
