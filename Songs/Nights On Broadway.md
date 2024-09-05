---
tags: Song ⭐⭐⭐⭐⭐ 💛
banner: "![[Main Course (1975).jpg]]"
---
[Time:: 4:28]
[Artist:: [[Bee Gees]] ]
[Genre:: Pop Rock]
[Played:: 55]
[Album:: [[Main Course (1975)]]]
[Year:: 1975]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[Nights On Broadway]]
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
		intensity: page["Nights_On_Broadway"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
