---
tags: Song ⭐⭐⭐⭐⭐ 
banner: "![[Electric Ladyland (1968).jpg]]"
---
[Time:: 4:01]
[Artist:: [[The Jimi Hendrix Experience]] ]
[Genre:: Folk rock]
[Played:: 5]
[Album:: [[Electric Ladyland (1968)]]]
[Year:: 1968]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[All Along The Watchtower]]
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
		intensity: page["All_Along_The_Watchtower"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
