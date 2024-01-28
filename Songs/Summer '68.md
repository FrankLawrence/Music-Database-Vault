---
tags: Song ⭐⭐⭐⭐ 
banner: "![[Atom Heart Mother (1970).jpg]]"
---
[Time:: 5:29]
[Artist:: [[Pink Floyd]] ]
[Genre:: Progressive Rock]
[Played:: 22]
[Album:: [[Atom Heart Mother (1970)]]]
[Year:: 1970]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[Summer '68]]
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
		intensity: page["Summer_'68"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
