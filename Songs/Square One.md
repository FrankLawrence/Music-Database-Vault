---
tags: Song ⭐⭐⭐⭐⭐ 
banner: "![[X&Y (2005).jpg]]"
---
[Time:: 4:48]
[Artist:: [[Coldplay]] ]
[Genre:: Rock]
[Played:: 27]
[Album:: [[X&Y (2005)]]]
[Year:: 2005]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[Square One]]
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
		intensity: page["Square_One"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
