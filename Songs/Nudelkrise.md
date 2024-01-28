---
tags: Song ⭐⭐⭐⭐ 
banner: "![[Heile Welt (1988).jpg]]"
---
[Time:: 2:31]
[Artist:: [[Loriot]] ]
[Genre:: Spoken & Audio]
[Played:: 3]
[Album:: [[Heile Welt (1988)]]]
[Year:: 1988]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[Nudelkrise]]
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
		intensity: page["Nudelkrise"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
