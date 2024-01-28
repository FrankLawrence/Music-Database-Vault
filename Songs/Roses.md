---
tags: Song ⭐⭐⭐⭐⭐ 
banner: "![[Bouquet (2015).jpg]]"
---
[Time:: 3:48]
[Artist:: [[The Chainsmokers]] [[Rozes]] ]
[Genre:: Dance-pop]
[Played:: 7]
[Album:: [[Bouquet (2015)]]]
[Year:: 2015]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[Roses]]
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
		intensity: page["Roses"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
