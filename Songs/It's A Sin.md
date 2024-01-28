---
tags: Song ⭐⭐⭐⭐⭐ 
banner: "![[Actually (1987).jpg]]"
---
[Time:: 5:01]
[Artist:: [[Pet Shop Boys]] ]
[Genre:: Synth-Pop]
[Played:: 27]
[Album:: [[Actually (1987)]]]
[Year:: 1987]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[It's A Sin]]
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
		intensity: page["It's_A_Sin"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
