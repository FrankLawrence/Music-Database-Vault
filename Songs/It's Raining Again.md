---
tags: Song ⭐⭐⭐⭐⭐ 💛
banner: "![[..Famous Last Words.. (1982).jpg]]"
---
[Time:: 4:19]
[Artist:: [[Supertramp]] ]
[Genre:: Progressive Rock]
[Played:: 40]
[Album:: [[..Famous Last Words.. (1982)]]]
[Year:: 1982]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[It's Raining Again]]
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
		intensity: page["It's_Raining_Again"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
