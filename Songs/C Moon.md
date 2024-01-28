---
tags: Song ⭐⭐⭐ 
banner: "![[All The Best (1972).jpg]]"
---
[Time:: 4:34]
[Artist:: [[Wings]] ]
[Genre:: Pop]
[Played:: 1]
[Album:: [[All The Best (1972)]]]
[Year:: 1972]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[C Moon]]
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
		intensity: page["C_Moon"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
