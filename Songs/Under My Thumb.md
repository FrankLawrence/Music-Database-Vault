---
tags: Song ⭐⭐⭐⭐ 
banner: "![[Aftermath (1966).jpg]]"
---
[Time:: 3:43]
[Artist:: [[The Rolling Stones]] ]
[Genre:: Pop Rock]
[Played:: 4]
[Album:: [[Aftermath (1966)]]]
[Year:: 1966]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[Under My Thumb]]
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
		intensity: page["Under_My_Thumb"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
