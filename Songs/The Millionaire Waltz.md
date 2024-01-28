---
tags: Song ⭐⭐⭐⭐ 
banner: "![[A Day at the Races (1976).jpg]]"
---
[Time:: 4:55]
[Artist:: [[Queen]] ]
[Genre:: ]
[Played:: ]
[Album:: [[A Day at the Races (1976)]]]
[Year:: 1976]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[The Millionaire Waltz]]
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
		intensity: page["The_Millionaire_Waltz"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
