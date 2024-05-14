---
tags: Song ⭐⭐⭐⭐⭐ 💛
banner: "![[Music Of The Spheres (2021).jpg]]"
---
[Time:: 10:19]
[Artist:: [[Coldplay]] ]
[Genre:: Electronic, Rock, Pop]
[Played:: 38]
[Album:: [[Music Of The Spheres (2021)]]]
[Year:: 2021]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[Coloratura]]
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
		intensity: page["Coloratura"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
