---
tags: Song ⭐⭐⭐ 
banner: "![[A Head Full of Dreams (2015).jpg]]"
---
[Time:: 6:17]
[Artist:: [[Coldplay]] ]
[Genre:: Pop]
[Played:: ]
[Album:: [[A Head Full of Dreams (2015)]]]
[Year:: 2015]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[Army of One]]
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
		intensity: page["Army_of_One"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
