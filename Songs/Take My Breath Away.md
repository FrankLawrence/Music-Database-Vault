---
tags: Song ⭐⭐⭐⭐ 
banner: "![[Top Gun (1986).jpg]]"
---
[Time:: 4:11]
[Artist:: [[Berlin]] ]
[Genre:: Pop]
[Played:: 2]
[Album:: [[Top Gun (1986)]]]
[Year:: 1986]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[Take My Breath Away]]
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
		intensity: page["Take_My_Breath_Away"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
