---
tags: Song ⭐⭐⭐ 
banner: "![[Invisible Touch (1986).jpg]]"
---
[Time:: 3:28]
[Artist:: [[Genesis]] ]
[Genre:: Dance-rock]
[Played:: 3]
[Album:: [[Invisible Touch (1986)]]]
[Year:: 1986]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[Invisible Touch]]
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
		intensity: page["Invisible_Touch"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
