---
tags: Song ⭐⭐⭐⭐⭐ 
banner: "![[Seychelles (1976).jpg]]"
---
[Time:: 4:13]
[Artist:: [[Masayoshi Takanaka (高中正義)]] ]
[Genre:: Jazz]
[Played:: 11]
[Album:: [[Seychelles (1976)]]]
[Year:: 1976]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[Oh! Tengo Suerte]]
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
		intensity: page["Oh!_Tengo_Suerte"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
