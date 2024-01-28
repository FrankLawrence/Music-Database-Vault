---
tags: Song ⭐⭐⭐⭐ 
banner: "![[Torches (2011).jpg]]"
---
[Time:: 4:16]
[Artist:: [[Foster the People]] ]
[Genre:: Psychedelic Pop]
[Played:: 39]
[Album:: [[Torches (2011)]]]
[Year:: 2011]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[Pumped Up Kicks]]
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
		intensity: page["Pumped_Up_Kicks"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
