---
tags: Song ⭐⭐⭐⭐⭐ 💛
banner: "![[Piano Man (1977).jpg]]"
---
[Time:: 3:21]
[Artist:: [[Billy Joel]] ]
[Genre:: Pop]
[Played:: 44]
[Album:: [[Piano Man (1977)]]]
[Year:: 1977]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[She's Always A Woman]]
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
		intensity: page["She's_Always_A_Woman"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
