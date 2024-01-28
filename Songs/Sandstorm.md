---
tags: Song ⭐⭐⭐⭐⭐ 
banner: "![[La Bionda (1978).jpg]]"
---
[Time:: 10:17]
[Artist:: [[La Bionda]] ]
[Genre:: Disco]
[Played:: 11]
[Album:: [[La Bionda (1978)]]]
[Year:: 1978]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[Sandstorm]]
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
		intensity: page["Sandstorm"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
