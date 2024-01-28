---
tags: Song  
banner: "![[Best Of Bowie (1985).jpg]]"
---
[Time:: 3:53]
[Artist:: [[David Bowie]] ]
[Genre:: Rock]
[Played:: 2]
[Album:: [[Best Of Bowie (1985)]]]
[Year:: 1985]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[This Is Not America]]
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
		intensity: page["This_Is_Not_America"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
