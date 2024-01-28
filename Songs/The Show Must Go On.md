---
tags: Song ⭐⭐⭐⭐ 
banner: "![[Innuendo (1977).jpg]]"
---
[Time:: 4:24]
[Artist:: [[Queen]] ]
[Genre:: Rock]
[Played:: 3]
[Album:: [[Innuendo (1977)]]]
[Year:: 1977]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[The Show Must Go On]]
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
		intensity: page["The_Show_Must_Go_On"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
