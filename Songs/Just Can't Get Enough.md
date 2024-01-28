---
tags: Song ⭐⭐⭐ 

[Time:: 3:42]
[Artist:: [[The Black Eyed Peas]] ]
[Genre:: ]
[Played:: ]
[Album:: ]
[Year:: 2011]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[Just Can't Get Enough]]
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
		intensity: page["Just_Can't_Get_Enough"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
