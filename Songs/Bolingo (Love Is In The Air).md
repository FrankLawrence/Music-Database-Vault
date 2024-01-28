---
tags: Song ⭐⭐⭐ 
banner: "![[Greatest Hits (1998).jpg]]"
---
[Time:: 4:30]
[Artist:: [[La Bouche]] ]
[Genre:: Pop]
[Played:: 2]
[Album:: [[Greatest Hits (1998)]]]
[Year:: 1998]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[Bolingo (Love Is In The Air)]]
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
		intensity: page["Bolingo_(Love_Is_In_The_Air)"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
