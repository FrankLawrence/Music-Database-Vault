---
tags: Song ⭐⭐⭐⭐⭐ 
banner: "![[Jutty Ranx (2013).jpg]]"
---
[Time:: 3:30]
[Artist:: [[Jutty Ranx]] ]
[Genre:: Pop]
[Played:: 3]
[Album:: [[Jutty Ranx (2013)]]]
[Year:: 2013]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[I See You]]
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
		intensity: page["I_See_You"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
