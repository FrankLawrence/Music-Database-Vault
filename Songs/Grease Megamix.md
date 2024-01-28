---
tags: Song ⭐⭐ 
banner: "![[Pure Disco (1990).jpg]]"
---
[Time:: 4:51]
[Artist:: [[Olivia Newton-John & John Travolta]] ]
[Genre:: Pop]
[Played:: 2]
[Album:: [[Pure Disco (1990)]]]
[Year:: 1990]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[Grease Megamix]]
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
		intensity: page["Grease_Megamix"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
