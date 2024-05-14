---
tags: Song ⭐⭐⭐⭐⭐ 
banner: "![[Le Carnaval des Animaux (1886).jpg]]"
---
[Time:: 2:31]
[Artist:: [[Pascal Roge]] [[Cristina Ortiz - pianos]] [[London Sinfonietta]] [[con. Charles Dutoit]] ]
[Genre:: Classical]
[Played:: 14]
[Album:: [[Le Carnaval des Animaux (1886)]]]
[Year:: 1886]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[Aquarium]]
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
		intensity: page["Aquarium"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
