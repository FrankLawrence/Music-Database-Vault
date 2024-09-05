---
tags: Song ⭐⭐⭐⭐ 
banner: "![[Flower Boy (2017).jpg]]"
---
[Time:: 0:36]
[Artist:: [[Tyler, the Creator]] ]
[Genre:: Hip-Hop/Rap]
[Played:: 38]
[Album:: [[Flower Boy (2017)]]]
[Year:: 2017]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[Sometimes...]]
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
		intensity: page["Sometimes..."]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
