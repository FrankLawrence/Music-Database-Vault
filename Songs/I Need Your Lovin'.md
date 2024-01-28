---
tags: Song ⭐⭐⭐ 
banner: "![[Pure Disco (1980).jpg]]"
---
[Time:: 3:34]
[Artist:: [[Teena Marie]] ]
[Genre:: Pop]
[Played:: 1]
[Album:: [[Pure Disco (1980)]]]
[Year:: 1980]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[I Need Your Lovin']]
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
		intensity: page["I_Need_Your_Lovin'"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
