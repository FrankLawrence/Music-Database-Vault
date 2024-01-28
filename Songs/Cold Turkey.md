---
tags: Song ⭐⭐⭐⭐ 
banner: "![[The John Lennon Collection (1969).jpg]]"
---
[Time:: 5:01]
[Artist:: [[John Lennon]] ]
[Genre:: Rock]
[Played:: 1]
[Album:: [[The John Lennon Collection (1969)]]]
[Year:: 1969]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[Cold Turkey]]
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
		intensity: page["Cold_Turkey"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
