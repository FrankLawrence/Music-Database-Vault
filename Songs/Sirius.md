---
tags: Song ⭐⭐⭐⭐⭐ 
banner: "![[Eye In The Sky (1982).jpg]]"
---
[Time:: 1:52]
[Artist:: [[Alan Parsons Project]] ]
[Genre:: Progressive Rock]
[Played:: 39]
[Album:: [[Eye In The Sky (1982)]]]
[Year:: 1982]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[Sirius]]
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
		intensity: page["Sirius"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
