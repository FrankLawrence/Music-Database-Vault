---
tags: Song  
banner: "![[Revolver (1966).jpg]]"
---
[Time:: 2:01]
[Artist:: [[The Beatles]] ]
[Genre:: Rock]
[Played:: 2]
[Album:: [[Revolver (1966)]]]
[Year:: 1966]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[And Your Bird Can Sing]]
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
		intensity: page["And_Your_Bird_Can_Sing"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
