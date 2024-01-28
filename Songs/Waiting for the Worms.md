---
tags: Song ⭐⭐⭐⭐⭐ 💛
banner: "![[The Wall (1979).jpg]]"
---
[Time:: 3:57]
[Artist:: [[Pink Floyd]] ]
[Genre:: Progressive Rock]
[Played:: 50]
[Album:: [[The Wall (1979)]]]
[Year:: 1979]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[Waiting for the Worms]]
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
		intensity: page["Waiting_for_the_Worms"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
