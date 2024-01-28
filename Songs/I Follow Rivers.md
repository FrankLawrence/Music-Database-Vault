---
tags: Song ⭐⭐⭐ 

[Time:: 4:07]
[Artist:: [[Lykke Li]] ]
[Genre:: ]
[Played:: ]
[Album:: ]
[Year:: 2011]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[I Follow Rivers]]
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
		intensity: page["I_Follow_Rivers"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
