---
tags: Song ⭐⭐⭐ 
banner: "![[All Over the Place (2020).jpg]]"
---
[Time:: 3:12]
[Artist:: [[KSI]] [[Craig David & Digital Farm Animals]] ]
[Genre:: Dance-pop]
[Played:: 2]
[Album:: [[All Over the Place (2020)]]]
[Year:: 2020]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[Really Love]]
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
		intensity: page["Really_Love"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
