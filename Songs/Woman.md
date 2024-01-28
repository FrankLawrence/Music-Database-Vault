---
tags: Song ⭐⭐⭐⭐⭐ 
banner: "![[The John Lennon Collection (1980).jpg]]"
---
[Time:: 3:28]
[Artist:: [[John Lennon]] ]
[Genre:: Rock]
[Played:: 3]
[Album:: [[The John Lennon Collection (1980)]]]
[Year:: 1980]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[Woman]]
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
		intensity: page["Woman"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
