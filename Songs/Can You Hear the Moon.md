---
tags: Song ⭐⭐⭐⭐⭐ 💛
banner: 
---
[Time:: 3:02]
[Artist:: [[Grady]] ]
[Genre:: Pop]
[Played:: 26]
[Year:: 2019]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[Can You Hear the Moon]]
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
		intensity: page["Can_You_Hear_the_Moon"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
