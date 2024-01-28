---
tags: Song ⭐⭐⭐⭐ 
banner: "![[The Final Cut (1983).jpg]]"
---
[Time:: 4:26]
[Artist:: [[Pink Floyd]] ]
[Genre:: Art rock]
[Played:: 8]
[Album:: [[The Final Cut (1983)]]]
[Year:: 1983]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[Your Possible Pasts]]
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
		intensity: page["Your_Possible_Pasts"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
