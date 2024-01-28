---
tags: Song ⭐⭐⭐⭐⭐ 💛
banner: "![[The Singles - The First Ten Years (1982).jpg]]"
---
[Time:: 5:48]
[Artist:: [[ABBA]] ]
[Genre:: Pop]
[Played:: 19]
[Album:: [[The Singles - The First Ten Years (1982)]]]
[Year:: 1982]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[The Day Before You Came]]
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
		intensity: page["The_Day_Before_You_Came"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
