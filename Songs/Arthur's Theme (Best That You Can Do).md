---
tags: Song ⭐⭐⭐ 
banner: "![[Ultimate FM Gold (2022).jpg]]"
---
[Time:: 3:56]
[Artist:: [[Christopher Cross]] ]
[Genre:: Pop]
[Played:: 1]
[Album:: [[Ultimate FM Gold (2022)]]]
[Year:: 2022]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[Arthur's Theme (Best That You Can Do)]]
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
		intensity: page["Arthur's_Theme_(Best_That_You_Can_Do)"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
