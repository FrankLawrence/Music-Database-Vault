---
tags: Song ⭐⭐⭐ 
banner: "![[A Momentary Lapse of Reason (1987).jpg]]"
---
[Time:: 5:09]
[Artist:: [[Pink Floyd]] ]
[Genre:: Progressive Rock]
[Played:: 4]
[Album:: [[A Momentary Lapse of Reason (1987)]]]
[Year:: 1987]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[One Slip]]
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
		intensity: page["One_Slip"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
