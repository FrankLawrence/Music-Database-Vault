---
tags: Song ⭐⭐⭐⭐⭐ 
banner: "![[A Night at the Opera (1975).jpg]]"
---
[Time:: 5:58]
[Artist:: [[Queen]] ]
[Genre:: Rock]
[Played:: 3]
[Album:: [[A Night at the Opera (1975)]]]
[Year:: 1975]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[Bohemian Rhapsody]]
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
		intensity: page["Bohemian_Rhapsody"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
