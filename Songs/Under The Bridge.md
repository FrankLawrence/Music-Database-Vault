---
tags: Song ⭐⭐⭐⭐ 
banner: "![[Blood Sugar Sex Magik (1992).jpg]]"
---
[Time:: 4:27]
[Artist:: [[Red Hot Chili Peppers]] ]
[Genre:: Alternative Rock]
[Played:: 3]
[Album:: [[Blood Sugar Sex Magik (1992)]]]
[Year:: 1992]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[Under The Bridge]]
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
		intensity: page["Under_The_Bridge"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
