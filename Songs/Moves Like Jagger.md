---
tags: Song ⭐⭐⭐⭐⭐ 💛
banner: "![[Hands All Over (2011).jpg]]"
---
[Time:: 3:22]
[Artist:: [[Maroon 5]] [[Christina Aguilera]] ]
[Genre:: Disco]
[Played:: 42]
[Album:: [[Hands All Over (2011)]]]
[Year:: 2011]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[Moves Like Jagger]]
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
		intensity: page["Moves_Like_Jagger"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
