---
tags: Song ⭐⭐⭐⭐⭐ 💛
banner: "![[Starboy (2016).jpg]]"
---
[Time:: 4:29]
[Artist:: [[The Weeknd]] [[Daft Punk]] ]
[Genre:: Disco]
[Played:: 24]
[Album:: [[Starboy (2016)]]]
[Year:: 2016]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[I Feel It Coming]]
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
		intensity: page["I_Feel_It_Coming"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
