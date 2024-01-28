---
tags: Song ⭐⭐⭐ 
banner: "![[Ultimate FM Gold (2022).jpg]]"
---
[Time:: 5:03]
[Artist:: [[Foreigner]] ]
[Genre:: Rock]
[Played:: ]
[Album:: [[Ultimate FM Gold (2022)]]]
[Year:: 2022]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[I Want to Know What Love Is]]
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
		intensity: page["I_Want_To_Know_What_Love_Is"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
