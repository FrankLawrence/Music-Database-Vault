---
tags: Song ⭐⭐⭐⭐ 
banner: "![[Max ().jpg]]"
---
[Time:: 4:04]
[Artist:: [[Max]] ]
[Genre:: ]
[Played:: 2]
[Album:: [[Max ()]]]
[Year:: ]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[Max Adrian & ID - ID (MASTER) v.3]]
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
		intensity: page["Max_Adrian_Eyes_Without_A_Face_ID_-_ID_(MASTER)_v.3"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
