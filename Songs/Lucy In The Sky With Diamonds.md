---
tags: Song ⭐⭐⭐⭐⭐ 
banner: "![[Sgt. Pepper's Lonely Hearts Club Band ().jpg]]"
---
[Time:: 3:29]
[Artist:: [[The Beatles]] ]
[Genre:: ]
[Played:: 6]
[Album:: [[Sgt. Pepper's Lonely Hearts Club Band ()]]]
[Year:: ]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[Lucy In The Sky With Diamonds]]
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
		intensity: page["Lucy_In_The_Sky_With_Diamonds"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
