---
tags: Song ⭐⭐⭐⭐⭐ 
banner: "![[Listen (2014).jpg]]"
---
[Time:: 3:24]
[Artist:: [[David Guetta]] [[Sam Martin]] ]
[Genre:: Progressive House]
[Played:: 9]
[Album:: [[Listen (2014)]]]
[Year:: 2014]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[Lovers on the Sun]]
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
		intensity: page["Lovers_on_the_Sun"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
