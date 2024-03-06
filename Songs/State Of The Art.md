---
tags: Song ⭐⭐⭐⭐ 
banner: "![[Making Mirrors (2011).jpg]]"
---
[Time:: 5:23]
[Artist:: [[Gotye]] ]
[Genre:: Indie Rock]
[Played:: 28]
[Album:: [[Making Mirrors (2011)]]]
[Year:: 2011]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[State Of The Art]]
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
		intensity: page["State_Of_The_Art"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
