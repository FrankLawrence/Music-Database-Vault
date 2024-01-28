---
tags: Song ⭐⭐⭐⭐⭐ 💛
banner: "![[Demon Days (2005).jpg]]"
---
[Time:: 3:45]
[Artist:: [[Gorillaz]] ]
[Genre:: Alternative Rock]
[Played:: 25]
[Album:: [[Demon Days (2005)]]]
[Year:: 2005]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[Kids With Guns]]
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
		intensity: page["Kids_With_Guns"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
