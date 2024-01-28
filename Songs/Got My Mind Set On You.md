---
tags: Song ⭐⭐⭐⭐ 
banner: "![[Cloud Nine (1987).jpg]]"
---
[Time:: 3:52]
[Artist:: [[George Harrison]] ]
[Genre:: Rock]
[Played:: ]
[Album:: [[Cloud Nine (1987)]]]
[Year:: 1987]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[Got My Mind Set On You]]
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
		intensity: page["Got_My_Mind_Set_On_You"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
