---
tags: Song ⭐⭐⭐⭐⭐ 💛
banner: 
---
[Time:: 3:36]
[Artist:: [[Sylo Nozra]] ]
[Genre:: Pop]
[Played:: 57]
[Year:: 2020]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[Why R U Back?]]
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
		intensity: page["Why_R_U_Back?"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
