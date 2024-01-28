---
tags: Song ⭐⭐ 
banner: "![[The Final Cut (1983).jpg]]"
---
[Time:: 5:19]
[Artist:: [[Pink Floyd]] ]
[Genre:: Art rock]
[Played:: 4]
[Album:: [[The Final Cut (1983)]]]
[Year:: 1983]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[Two Suns In The Sunset]]
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
		intensity: page["Two_Suns_In_The_Sunset"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
