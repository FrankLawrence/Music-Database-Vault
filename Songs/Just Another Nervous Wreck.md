---
tags: Song ⭐⭐⭐⭐ 💛
banner: "![[Breakfast In America (1979).jpg]]"
---
[Time:: 4:26]
[Artist:: [[Supertramp]] ]
[Genre:: Rock]
[Played:: 29]
[Album:: [[Breakfast In America (1979)]]]
[Year:: 1979]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[Just Another Nervous Wreck]]
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
		intensity: page["Just_Another_Nervous_Wreck"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
