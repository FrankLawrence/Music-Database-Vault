---
tags: Song ⭐⭐⭐ 
banner: "![[Swaay (2015).jpg]]"
---
[Time:: 4:17]
[Artist:: [[DNCE]] ]
[Genre:: Funk]
[Played:: ]
[Album:: [[Swaay (2015)]]]
[Year:: 2015]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[Cake by the Ocean]]
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
		intensity: page["Cake_by_the_Ocean"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
