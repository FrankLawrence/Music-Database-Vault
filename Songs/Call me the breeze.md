---
tags: Song ⭐⭐⭐⭐ 
banner: "![[Naturally (1972).jpg]]"
---
[Time:: 2:38]
[Artist:: [[J.J. Cale]] ]
[Genre:: Blues]
[Played:: 5]
[Album:: [[Naturally (1972)]]]
[Year:: 1972]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[Call me the breeze]]
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
		intensity: page["Call_me_the_breeze"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
