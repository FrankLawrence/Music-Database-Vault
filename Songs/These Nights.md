---
tags: Song ⭐⭐⭐⭐⭐ 
banner: "![[These Nights (2017).jpg]]"
---
[Time:: 4:07]
[Artist:: [[Darci]] ]
[Genre:: ]
[Played:: 39]
[Album:: [[These Nights (2017)]]]
[Year:: 2017]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[These Nights]]
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
		intensity: page["These_Nights"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
