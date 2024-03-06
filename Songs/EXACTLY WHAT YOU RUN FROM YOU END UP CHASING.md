---
tags: Song ⭐⭐⭐ 
banner: "![[IGOR (2019).jpg]]"
---
[Time:: 0:15]
[Artist:: [[Tyler, the Creator]] ]
[Genre:: Hip-Hop/Rap]
[Played:: 21]
[Album:: [[IGOR (2019)]]]
[Year:: 2019]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[EXACTLY WHAT YOU RUN FROM YOU END UP CHASING]]
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
		intensity: page["EXACTLY_WHAT_YOU_RUN_FROM_YOU_END_UP_CHASING"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
