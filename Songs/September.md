---
tags: Song ⭐⭐⭐⭐ 
banner: "![[The Best of Earth, Wind & Fire, Vol. 1 (1978).jpg]]"
---
[Time:: 3:35]
[Artist:: [[Earth, Wind & Fire]] ]
[Genre:: R&B]
[Played:: 2]
[Album:: [[The Best of Earth, Wind & Fire, Vol. 1 (1978)]]]
[Year:: 1978]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[September]]
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
		intensity: page["September"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
