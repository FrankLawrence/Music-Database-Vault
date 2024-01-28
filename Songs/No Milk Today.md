---
tags: Song ⭐⭐⭐⭐⭐ 
banner: "![[The Best of Herman and the Hermits (1966).jpg]]"
---
[Time:: 2:58]
[Artist:: [[Herman's Hermits]] ]
[Genre:: Pop]
[Played:: 6]
[Album:: [[The Best of Herman and the Hermits (1966)]]]
[Year:: 1966]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[No Milk Today]]
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
		intensity: page["No_Milk_Today"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
