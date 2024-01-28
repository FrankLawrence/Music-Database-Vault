---
tags: Song ⭐⭐⭐⭐⭐ 💛
banner: "![[Hunting High And Low (1985).jpg]]"
---
[Time:: 3:10]
[Artist:: [[a-ha]] ]
[Genre:: Electronic, Rock, Pop]
[Played:: 49]
[Album:: [[Hunting High And Low (1985)]]]
[Year:: 1985]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[Dream Myself Alive]]
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
		intensity: page["Dream_Myself_Alive"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
