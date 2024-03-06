---
tags: Song ⭐⭐⭐⭐⭐ 
banner: "![[IGOR (2019).jpg]]"
---
[Time:: 3:21]
[Artist:: [[Tyler, the Creator]] ]
[Genre:: Hip-Hop/Rap]
[Played:: 26]
[Album:: [[IGOR (2019)]]]
[Year:: 2019]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[IGOR'S THEME]]
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
		intensity: page["IGOR'S_THEME"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
