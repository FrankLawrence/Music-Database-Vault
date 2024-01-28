---
tags: Song ⭐⭐⭐⭐ 
banner: "![[Max (2018).jpg]]"
---
[Time:: 3:45]
[Artist:: [[Max]] ]
[Genre:: ]
[Played:: ]
[Album:: [[Max (2018)]]]
[Year:: 2018]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[Max Adrian & Gryffin Mills -Fallin' (Dujak Edit) 1]]
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
		intensity: page["Max_Adrian_Eyes_Without_A_Face_Gryffin_Mills_-Fallin'_(Dujak_Edit)_1"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
