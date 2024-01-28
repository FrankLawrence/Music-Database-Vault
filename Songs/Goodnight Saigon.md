---
tags: Song  
banner: "![[Piano Man (1982).jpg]]"
---
[Time:: 7:02]
[Artist:: [[Billy Joel]] ]
[Genre:: Pop]
[Played:: 1]
[Album:: [[Piano Man (1982)]]]
[Year:: 1982]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[Goodnight Saigon]]
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
		intensity: page["Goodnight_Saigon"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
