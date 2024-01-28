---
tags: Song ⭐⭐⭐⭐⭐ 
banner: "![[If You Can Believe Your Eyes and Ears (1965).jpg]]"
---
[Time:: 2:43]
[Artist:: [[The Mamas & The Papas]] ]
[Genre:: Pop]
[Played:: 1]
[Album:: [[If You Can Believe Your Eyes and Ears (1965)]]]
[Year:: 1965]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[California Dreamin']]
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
		intensity: page["California_Dreamin'"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
