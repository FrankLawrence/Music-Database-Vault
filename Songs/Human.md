---
tags: Song ⭐⭐ 
banner: "![[Human (2017).jpg]]"
---
[Time:: 3:18]
[Artist:: [[RagnBone Man]] ]
[Genre:: Soul]
[Played:: 2]
[Album:: [[Human (2017)]]]
[Year:: 2017]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[Human]]
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
		intensity: page["Human"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
