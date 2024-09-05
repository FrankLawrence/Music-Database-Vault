---
tags: Song ⭐⭐⭐⭐⭐ 
banner: "![[Le Carnaval des Animaux (1886).jpg]]"
---
[Time:: 0:30]
[Artist:: [[Pascal Roge]] [[Cristina Ortiz - pianos]] [[London Sinfonietta]] [[con. Charles Dutoit]] ]
[Genre:: Classical]
[Played:: 10]
[Album:: [[Le Carnaval des Animaux (1886)]]]
[Year:: 1886]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[Hemiones]]
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
		intensity: page["Hemiones"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
