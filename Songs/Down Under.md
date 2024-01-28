---
tags: Song ⭐⭐⭐⭐⭐ 
banner: "![[Buisness as Usual (1981).jpg]]"
---
[Time:: 3:42]
[Artist:: [[Men At Work]] ]
[Genre:: Pop Rock]
[Played:: 27]
[Album:: [[Buisness as Usual (1981)]]]
[Year:: 1981]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[Down Under]]
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
		intensity: page["Down_Under"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
