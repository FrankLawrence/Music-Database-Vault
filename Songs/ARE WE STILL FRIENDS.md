---
tags: Song ⭐⭐⭐⭐ 
banner: "![[IGOR (2019).jpg]]"
---
[Time:: 4:26]
[Artist:: [[Tyler, the Creator]] [[Pharrell Williams]] ]
[Genre:: Hip-Hop/Rap]
[Played:: 34]
[Album:: [[IGOR (2019)]]]
[Year:: 2019]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[ARE WE STILL FRIENDS]]
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
		intensity: page["ARE_WE_STILL_FRIENDS"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
