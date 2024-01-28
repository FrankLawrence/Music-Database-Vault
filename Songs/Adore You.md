---
tags: Song ⭐⭐⭐⭐ 
banner: "![[Fine Line (2019).jpg]]"
---
[Time:: 3:27]
[Artist:: [[Harry Styles]] ]
[Genre:: Pop]
[Played:: 17]
[Album:: [[Fine Line]]]
[Year:: 2019]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[Adore You]]
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
		intensity: page["Adore_You"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
