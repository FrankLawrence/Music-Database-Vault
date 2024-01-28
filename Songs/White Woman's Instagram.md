---
tags: Song ⭐⭐⭐⭐⭐ 
banner: "![[Inside (2020).jpg]]"
---
[Time:: 4:07]
[Artist:: [[Bo Burnham]] ]
[Genre:: Pop]
[Played:: 20]
[Album:: [[Inside (2020)]]]
[Year:: 2020]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[White Woman's Instagram]]
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
		intensity: page["White_Woman's_Instagram"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
