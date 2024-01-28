---
tags: Song ⭐⭐ 
banner: "![[Pure Disco (1979).jpg]]"
---
[Time:: 3:14]
[Artist:: [[The Ritchie Family]] ]
[Genre:: Pop]
[Played:: 1]
[Album:: [[Pure Disco (1979)]]]
[Year:: 1979]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[Best Disco In Town]]
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
		intensity: page["Best_Disco_In_Town"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
