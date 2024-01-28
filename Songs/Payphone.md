---
tags: Song ⭐⭐⭐⭐ 
banner: "![[Overexposed (2012).jpg]]"
---
[Time:: 3:51]
[Artist:: [[Maroon 5]] [[Wiz Khalifa]] ]
[Genre:: Pop]
[Played:: 2]
[Album:: [[Overexposed (2012)]]]
[Year:: 2012]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[Payphone]]
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
		intensity: page["Payphone"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
