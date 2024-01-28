---
tags: Song ⭐⭐⭐⭐⭐ 
banner: "![[Happy Nation (1992).jpg]]"
---
[Time:: 3:33]
[Artist:: [[Ace Of Base]] ]
[Genre:: Electronic]
[Played:: 21]
[Album:: [[Happy Nation (1992)]]]
[Year:: 1992]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[All That She Wants]]
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
		intensity: page["All_That_She_Wants"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
