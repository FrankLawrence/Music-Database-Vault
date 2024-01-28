---
tags: Song ⭐⭐⭐⭐ 
banner: "![[Zodiac (2016).jpg]]"
---
[Time:: 3:54]
[Artist:: [[Maddix]] ]
[Genre:: Dance]
[Played:: 2]
[Album:: [[Zodiac (2016)]]]
[Year:: 2016]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[Zodiac (Original Mix)]]
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
		intensity: page["Zodiac_(Original_Mix)"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
