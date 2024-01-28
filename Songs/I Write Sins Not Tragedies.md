---
tags: Song ⭐⭐⭐⭐ 
banner: "![[A Fever You Can't Sweat Out (2005).jpg]]"
---
[Time:: 3:06]
[Artist:: [[Panic! At The Disco]] ]
[Genre:: Pop Rock]
[Played:: 3]
[Album:: [[A Fever You Can't Sweat Out (2005)]]]
[Year:: 2005]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[I Write Sins Not Tragedies]]
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
		intensity: page["I_Write_Sins_Not_Tragedies"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
