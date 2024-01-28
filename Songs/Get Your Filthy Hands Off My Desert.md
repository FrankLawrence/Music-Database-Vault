---
tags: Song ⭐⭐⭐ 
banner: "![[The Final Cut (1983).jpg]]"
---
[Time:: 1:17]
[Artist:: [[Pink Floyd]] ]
[Genre:: Art rock]
[Played:: 4]
[Album:: [[The Final Cut (1983)]]]
[Year:: 1983]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[Get Your Filthy Hands Off My Desert]]
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
		intensity: page["Get_Your_Filthy_Hands_Off_My_Desert"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
