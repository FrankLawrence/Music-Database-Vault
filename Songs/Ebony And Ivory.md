---
tags: Song ⭐⭐⭐⭐ 
banner: "![[All The Best (1982).jpg]]"
---
[Time:: 3:43]
[Artist:: [[Paul McCartney & Stevie Wonder]] ]
[Genre:: Pop]
[Played:: 8]
[Album:: [[All The Best (1982)]]]
[Year:: 1982]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[Ebony And Ivory]]
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
		intensity: page["Ebony_And_Ivory"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
