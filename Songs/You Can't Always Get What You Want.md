---
tags: Song ⭐⭐ 
banner: "![[Let It Bleed (2007).jpg]]"
---
[Time:: 7:28]
[Artist:: [[The Rolling Stones]] ]
[Genre:: Rock]
[Played:: ]
[Album:: [[Let It Bleed (2007)]]]
[Year:: 2007]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[You Can't Always Get What You Want]]
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
		intensity: page["You_Can't_Always_Get_What_You_Want"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
