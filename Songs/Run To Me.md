---
tags: Song ⭐⭐⭐⭐⭐ 💛
banner: "![[To Whom It May Concern (1972).jpg]]"
---
[Time:: 3:07]
[Artist:: [[Bee Gees]] ]
[Genre:: Pop Rock]
[Played:: 49]
[Album:: [[To Whom It May Concern (1972)]]]
[Year:: 1972]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[Run To Me]]
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
		intensity: page["Run_To_Me"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
