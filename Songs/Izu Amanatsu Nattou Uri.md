---
tags: Song ⭐⭐⭐⭐ 
banner: "![[Brasilian Skies (1978).jpg]]"
---
[Time:: 6:49]
[Artist:: [[Masayoshi Takanaka (高中正義)]] ]
[Genre:: Jazz]
[Played:: 1]
[Album:: [[Brasilian Skies (1978)]]]
[Year:: 1978]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[Izu Amanatsu Nattou Uri]]
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
		intensity: page["Izu_Amanatsu_Nattou_Uri"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
