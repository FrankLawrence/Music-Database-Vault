---
tags: Song ⭐⭐⭐⭐ 
banner: "![[Flower Boy (2017).jpg]]"
---
[Time:: 3:14]
[Artist:: [[Tyler, the Creator]] [[Rex Orange County]] ]
[Genre:: Hip-Hop/Rap]
[Played:: 24]
[Album:: [[Flower Boy (2017)]]]
[Year:: 2017]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[Foreword]]
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
		intensity: page["Foreword"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
