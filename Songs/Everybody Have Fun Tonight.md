---
tags: Song  
banner: "![[Mosiac (1986).jpg]]"
---
[Time:: 4:42]
[Artist:: [[Wang Chung]] ]
[Genre:: New Wave]
[Played:: ]
[Album:: [[Mosiac (1986)]]]
[Year:: 1986]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[Everybody Have Fun Tonight]]
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
		intensity: page["Everybody_Have_Fun_Tonight"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
