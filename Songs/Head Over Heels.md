---
tags: Song ⭐⭐⭐⭐⭐ 
banner: "![[The Visitors (1981).jpg]]"
---
[Time:: 3:47]
[Artist:: [[ABBA]] ]
[Genre:: Pop]
[Played:: 11]
[Album:: [[The Visitors (1981)]]]
[Year:: 1981]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[Head Over Heels]]
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
		intensity: page["Head_Over_Heels"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
