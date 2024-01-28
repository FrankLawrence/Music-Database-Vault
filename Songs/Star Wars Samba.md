---
tags: Song ⭐⭐⭐ 
banner: "![[Brasilian Skies (1978).jpg]]"
---
[Time:: 3:45]
[Artist:: [[Masayoshi Takanaka (高中正義)]] ]
[Genre:: Jazz]
[Played:: 1]
[Album:: [[Brasilian Skies (1978)]]]
[Year:: 1978]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[Star Wars Samba]]
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
		intensity: page["Star_Wars_Samba"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
