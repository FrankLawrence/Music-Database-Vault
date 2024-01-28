---
tags: Song ⭐⭐⭐⭐ 
banner: "![[The Very Best Of Smooth Jazz [Disc 1] (1965).jpg]]"
---
[Time:: 2:53]
[Artist:: [[Nina Simone]] ]
[Genre:: Jazz]
[Played:: 1]
[Album:: [[The Very Best Of Smooth Jazz [Disc 1] (1965)]]]
[Year:: 1965]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[Feeling Good]]
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
		intensity: page["Feeling_Good"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
