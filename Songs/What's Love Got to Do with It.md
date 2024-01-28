---
tags: Song ⭐⭐⭐ 
banner: "![[Ultimate FM Gold (2022).jpg]]"
---
[Time:: 3:49]
[Artist:: [[Tina Turner]] ]
[Genre:: R&B]
[Played:: ]
[Album:: [[Ultimate FM Gold (2022)]]]
[Year:: 2022]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[What's Love Got to Do with It]]
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
		intensity: page["What's_Love_Got_to_Do_with_It"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
