---
tags: Song ⭐⭐⭐⭐
banner: "!![["Awaken, My Love!" (2016).jpg]]"
---
[Time:: 6:19]
[Artist:: [[Childish Gambino]] ]
[Genre:: ]
[Played:: 20]
[Album:: [["Awaken, My Love!"]]]
[Year:: 2016]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[BiPolar ]]
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
		intensity: page["Me_and_Your_Mama"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
