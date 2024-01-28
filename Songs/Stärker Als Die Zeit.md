---
tags: Song  
banner: "![[Stärker Als Die Zeit (2016).jpg]]"
---
[Time:: 4:08]
[Artist:: [[Udo Lindenberg]] ]
[Genre:: Rock]
[Played:: ]
[Album:: [[Stärker Als Die Zeit (2016)]]]
[Year:: 2016]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[Stärker Als Die Zeit]]
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
		intensity: page["Stärker_Als_Die_Zeit"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
