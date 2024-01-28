---
tags: Song ⭐⭐⭐⭐⭐ 
banner: "![[ABBA (1975).jpg]]"
---
[Time:: 3:34]
[Artist:: [[ABBA]] ]
[Genre:: Rock, Pop]
[Played:: 5]
[Album:: [[ABBA (1975)]]]
[Year:: 1975]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[Mamma Mia]]
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
		intensity: page["Mamma_Mia"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
