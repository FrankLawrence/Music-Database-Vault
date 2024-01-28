---
tags: Song ⭐⭐⭐⭐⭐ 
banner: "![[Quo Vadis (1989).jpg]]"
---
[Time:: 4:14]
[Artist:: [[Frank Zander]] ]
[Genre:: ]
[Played:: 2]
[Album:: [[Quo Vadis (1989)]]]
[Year:: 1989]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[Hier kommt Kurt]]
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
		intensity: page["Hier_kommt_Kurt"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
