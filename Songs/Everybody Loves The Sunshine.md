---
tags: Song  
banner: "![[Jazz (1976).jpg]]"
---
[Time:: 3:42]
[Artist:: [[Roy Ayers]] ]
[Genre:: Jazz]
[Played:: 4]
[Album:: [[Jazz (1976)]]]
[Year:: 1976]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[Everybody Loves The Sunshine]]
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
		intensity: page["Everybody_Loves_The_Sunshine"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
