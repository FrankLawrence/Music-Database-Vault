---
tags: Song ⭐⭐⭐⭐⭐ 
banner: "![[Demon Days (2005).jpg]]"
---
[Time:: 3:41]
[Artist:: [[Gorillaz]] [[De La Soul]] ]
[Genre:: Alternative Rock]
[Played:: 23]
[Album:: [[Demon Days (2005)]]]
[Year:: 2005]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[Feel Good Inc]]
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
		intensity: page["Feel_Good_Inc"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
