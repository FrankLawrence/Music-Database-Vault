---
tags: Song ⭐⭐⭐⭐⭐ 
banner: "![[Le Carnaval des Animaux (1886).jpg]]"
---
[Time:: 2:47]
[Artist:: [[Pascal Roge]] [[Cristina Ortiz - pianos]] [[London Sinfonietta]] [[con. Charles Dutoit]] ]
[Genre:: Classical]
[Played:: 2]
[Album:: [[Le Carnaval des Animaux (1886)]]]
[Year:: 1886]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[Le Cygne]]
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
		intensity: page["Le_Cygne"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
