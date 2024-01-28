---
tags: Song ⭐⭐⭐⭐⭐ 
banner: "![[Dancing on the Ceiling (1986).jpg]]"
---
[Time:: 4:03]
[Artist:: [[Lionel Richie]] ]
[Genre:: R&B]
[Played:: 8]
[Album:: [[Dancing on the Ceiling (1986)]]]
[Year:: 1986]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[Say You, Say Me]]
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
		intensity: page["Say_You,_Say_Me"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
