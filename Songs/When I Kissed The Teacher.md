---
tags: Song ⭐⭐⭐ 
banner: "![[Arrival (1976).jpg]]"
---
[Time:: 3:03]
[Artist:: [[ABBA]] ]
[Genre:: Pop]
[Played:: ]
[Album:: [[Arrival (1976)]]]
[Year:: 1976]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[When I Kissed The Teacher]]
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
		intensity: page["When_I_Kissed_The_Teacher"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
