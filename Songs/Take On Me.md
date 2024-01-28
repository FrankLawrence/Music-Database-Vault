---
tags: Song ⭐⭐⭐⭐⭐ 
banner: "![[Hunting High And Low (1985).jpg]]"
---
[Time:: 3:48]
[Artist:: [[a-ha]] ]
[Genre:: Electronic, Rock, Pop]
[Played:: 6]
[Album:: [[Hunting High And Low (1985)]]]
[Year:: 1985]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[Take On Me]]
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
		intensity: page["Take_On_Me"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
