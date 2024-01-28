---
tags: Song ⭐⭐⭐⭐⭐ 💛
banner: "![[NOT ALL HEROES WEAR CAPES (2018).jpg]]"
---
[Time:: 2:46]
[Artist:: [[Metro Boomin]] [[Travis Scott]] ]
[Genre:: Hip-Hop/Rap]
[Played:: 48]
[Album:: [[NOT ALL HEROES WEAR CAPES (2018)]]]
[Year:: 2018]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[Overdue]]
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
		intensity: page["Overdue"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
