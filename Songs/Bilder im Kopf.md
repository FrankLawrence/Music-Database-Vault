---
tags: Song ⭐⭐⭐⭐ 

[Time:: 4:19]
[Artist:: [[SIDO]] ]
[Genre:: ]
[Played:: 1]
[Album:: ]
[Year:: ]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[Bilder im Kopf]]
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
		intensity: page["Bilder_im_Kopf"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
