---
tags: Song ⭐⭐⭐⭐⭐ 💛
banner: "![[MONTERO (2021).jpg]]"
---
[Time:: 3:33]
[Artist:: [[Lil Nas X]] [[Jack Harlow]] ]
[Genre:: Pop Rap]
[Played:: 41]
[Album:: [[MONTERO (2021)]]]
[Year:: 2021]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[INDUSTRY BABY]]
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
		intensity: page["INDUSTRY_BABY"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
