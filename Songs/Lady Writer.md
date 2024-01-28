---
tags: Song ⭐⭐⭐⭐⭐ 
banner: "![[Communiqué (1979).jpg]]"
---
[Time:: 3:46]
[Artist:: [[Dire Straits]] ]
[Genre:: Rock]
[Played:: 22]
[Album:: [[Communiqué (1979)]]]
[Year:: 1979]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[Lady Writer]]
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
		intensity: page["Lady_Writer"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
