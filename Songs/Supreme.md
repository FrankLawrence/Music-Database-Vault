---
tags: Song ⭐⭐⭐⭐⭐ 💛
banner: "![[Sing When You're Winning (2000).jpg]]"
---
[Time:: 4:15]
[Artist:: [[Robbie Williams]] ]
[Genre:: Pop]
[Played:: 31]
[Album:: [[Sing When You're Winning (2000)]]]
[Year:: 2000]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[Supreme]]
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
		intensity: page["Supreme"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
