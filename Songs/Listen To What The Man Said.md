---
tags: Song ⭐⭐ 
banner: "![[All The Best (1975).jpg]]"
---
[Time:: 3:56]
[Artist:: [[Wings]] ]
[Genre:: Pop]
[Played:: 1]
[Album:: [[All The Best (1975)]]]
[Year:: 1975]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[Listen To What The Man Said]]
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
		intensity: page["Listen_To_What_The_Man_Said"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
