---
tags: Song ⭐⭐⭐⭐ 
banner: "![[AM (2013).jpg]]"
---
[Time:: 4:26]
[Artist:: [[Arctic Monkeys]] ]
[Genre:: Psychedelic Rock]
[Played:: 13]
[Album:: [[AM (2013)]]]
[Year:: 2013]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[Do I Wanna Know]]
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
		intensity: page["Do_I_Wanna_Know"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
