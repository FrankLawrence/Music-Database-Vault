---
tags: Song ⭐⭐⭐ 
banner: "![[Revolver (1966).jpg]]"
---
[Time:: 2:25]
[Artist:: [[The Beatles]] ]
[Genre:: Rock]
[Played:: 4]
[Album:: [[Revolver (1966)]]]
[Year:: 1966]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[Here, There And Everywhere]]
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
		intensity: page["Here,_There_And_Everywhere"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
