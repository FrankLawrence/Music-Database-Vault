---
tags: Song ⭐⭐⭐ 
banner: "![[A Head Full of Dreams (2015).jpg]]"
---
[Time:: 1:00]
[Artist:: [[Coldplay]] ]
[Genre:: Pop]
[Played:: 14]
[Album:: [[A Head Full of Dreams (2015)]]]
[Year:: 2015]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[Colour Spectrum]]
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
		intensity: page["Colour_Spectrum"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
