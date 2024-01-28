---
tags: Song ⭐⭐⭐⭐ 
banner: "![[Back To Front [UK] (1992).jpg]]"
---
[Time:: 3:46]
[Artist:: [[Lionel Richie]] ]
[Genre:: Soul]
[Played:: 1]
[Album:: [[Back To Front [UK] (1992)]]]
[Year:: 1992]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[Still]]
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
		intensity: page["Still"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
