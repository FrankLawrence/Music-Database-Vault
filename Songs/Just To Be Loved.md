---
tags: Song ⭐⭐⭐⭐⭐ 
banner: "![[Jazz (2000).jpg]]"
---
[Time:: 4:10]
[Artist:: [[Al Jarreau]] ]
[Genre:: Jazz]
[Played:: 36]
[Album:: [[Jazz (2000)]]]
[Year:: 2000]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[Just To Be Loved]]
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
		intensity: page["Just_To_Be_Loved"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
