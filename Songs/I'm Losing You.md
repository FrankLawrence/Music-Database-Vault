---
tags: Song ⭐⭐⭐⭐ 
banner: "![[The John Lennon Collection (1980).jpg]]"
---
[Time:: 4:00]
[Artist:: [[John Lennon]] ]
[Genre:: Rock]
[Played:: 2]
[Album:: [[The John Lennon Collection (1980)]]]
[Year:: 1980]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[I'm Losing You]]
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
		intensity: page["I'm_Losing_You"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
