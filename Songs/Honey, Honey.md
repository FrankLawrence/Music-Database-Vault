---
tags: Song ⭐⭐⭐⭐⭐ 
banner: "![[Waterloo (2011).jpg]]"
---
[Time:: 2:57]
[Artist:: [[ABBA]] ]
[Genre:: Rock, Pop]
[Played:: 8]
[Album:: [[Waterloo (2011)]]]
[Year:: 2011]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[Honey, Honey]]
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
		intensity: page["Honey,_Honey"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
