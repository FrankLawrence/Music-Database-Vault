---
tags: Song ⭐⭐⭐ 
banner: "![[Back in the High Life (1986).jpg]]"
---
[Time:: 4:13]
[Artist:: [[Steve Winwood]] ]
[Genre:: Pop]
[Played:: 2]
[Album:: [[Back in the High Life (1986)]]]
[Year:: 1986]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[Higher Love]]
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
		intensity: page["Higher_Love"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
