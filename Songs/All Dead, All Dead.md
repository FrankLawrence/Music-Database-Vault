---
tags: Song ⭐⭐⭐⭐⭐ 
banner: "![[News of the World (1977).jpg]]"
---
[Time:: 3:21]
[Artist:: [[Queen]] ]
[Genre:: Rock]
[Played:: 65]
[Album:: [[News of the World (1977)]]]
[Year:: 1977]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[All Dead, All Dead]]
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
		intensity: page["All_Dead,_All_Dead"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
