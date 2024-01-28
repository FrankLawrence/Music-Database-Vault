---
tags: Song ⭐⭐⭐⭐⭐ 
banner: "![[Inside (2020).jpg]]"
---
[Time:: 4:36]
[Artist:: [[Bo Burnham]] ]
[Genre:: Hip-Hop/Rap]
[Played:: 17]
[Album:: [[Inside (2020)]]]
[Year:: 2020]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[Welcome to the Internet]]
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
		intensity: page["Welcome_to_the_Internet"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
