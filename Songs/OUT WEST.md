---
tags: Song ⭐⭐⭐ 
banner: "![[JackBoys (2019).jpg]]"
---
[Time:: 2:39]
[Artist:: [[JACKBOYS]] [[Travis Scott & Young Thug]] ]
[Genre:: Hip-Hop/Rap]
[Played:: 2]
[Album:: [[JackBoys (2019)]]]
[Year:: 2019]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[OUT WEST]]
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
		intensity: page["OUT_WEST"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
