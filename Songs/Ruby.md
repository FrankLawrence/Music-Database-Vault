---
tags: Song ⭐⭐⭐⭐ 
banner: "![[Yours Truly, Angry Mob (2007).jpg]]"
---
[Time:: 3:25]
[Artist:: [[Kaiser Chiefs]] ]
[Genre:: Rock]
[Played:: 2]
[Album:: [[Yours Truly, Angry Mob (2007)]]]
[Year:: 2007]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[Ruby]]
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
		intensity: page["Ruby"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
