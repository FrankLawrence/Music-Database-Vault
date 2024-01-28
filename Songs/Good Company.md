---
tags: Song  
banner: "![[A Night at the Opera (1975).jpg]]"
---
[Time:: 3:23]
[Artist:: [[Queen]] ]
[Genre:: ]
[Played:: 1]
[Album:: [[A Night at the Opera (1975)]]]
[Year:: 1975]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[Good Company]]
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
		intensity: page["Good_Company"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
