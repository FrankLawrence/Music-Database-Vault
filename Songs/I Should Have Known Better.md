---
tags: Song ⭐⭐⭐⭐ 
banner: "![[A Hard Day's Night (1964).jpg]]"
---
[Time:: 2:44]
[Artist:: [[The Beatles]] ]
[Genre:: Pop]
[Played:: 1]
[Album:: [[A Hard Day's Night (1964)]]]
[Year:: 1964]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[I Should Have Known Better]]
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
		intensity: page["I_Should_Have_Known_Better"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
