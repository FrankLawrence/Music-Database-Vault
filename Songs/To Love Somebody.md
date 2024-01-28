---
tags: Song ⭐⭐⭐⭐⭐ 
banner: "![[Bee Gees' 1st (1967).jpg]]"
---
[Time:: 3:02]
[Artist:: [[Bee Gees]] ]
[Genre:: Rock]
[Played:: 4]
[Album:: [[Bee Gees' 1st (1967)]]]
[Year:: 1967]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[To Love Somebody]]
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
		intensity: page["To_Love_Somebody"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
