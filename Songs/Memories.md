---
tags: Song ⭐⭐⭐⭐ 
banner: "![[Jordi (2019).jpg]]"
---
[Time:: 3:11]
[Artist:: [[Maroon 5]] ]
[Genre:: Reggae-pop]
[Played:: 3]
[Album:: [[Jordi (2019)]]]
[Year:: 2019]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[Memories]]
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
		intensity: page["Memories"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
