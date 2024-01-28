---
tags: Song ⭐⭐⭐⭐⭐ 
banner: "![[Second Helping (1974).jpg]]"
---
[Time:: 4:45]
[Artist:: [[Lynyrd Skynyrd]] ]
[Genre:: Country Rock]
[Played:: 1]
[Album:: [[Second Helping (1974)]]]
[Year:: 1974]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[Sweet Home Alabama]]
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
		intensity: page["Sweet_Home_Alabama"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
