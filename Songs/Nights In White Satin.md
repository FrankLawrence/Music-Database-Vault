---
tags: Song ⭐⭐⭐⭐⭐ 
banner: "![[Fading Shades (1995).jpg]]"
---
[Time:: 3:34]
[Artist:: [[Sandra]] ]
[Genre:: Electronic]
[Played:: 11]
[Album:: [[Fading Shades (1995)]]]
[Year:: 1995]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[Nights In White Satin]]
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
		intensity: page["Nights_In_White_Satin"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
