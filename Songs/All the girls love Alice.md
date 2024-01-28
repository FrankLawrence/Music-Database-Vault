---
tags: Song ⭐⭐⭐⭐⭐ 
banner: "![[Goodbye Yellow Brick Road (1973).jpg]]"
---
[Time:: 5:09]
[Artist:: [[Elton John]] ]
[Genre:: Pop]
[Played:: 5]
[Album:: [[Goodbye Yellow Brick Road (1973)]]]
[Year:: 1973]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[All the girls love Alice]]
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
		intensity: page["All_the_girls_love_Alice"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
