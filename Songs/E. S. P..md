---
tags: Song ⭐⭐⭐⭐⭐ 
banner: "![[An Insatiable High (1977).jpg]]"
---
[Time:: 4:11]
[Artist:: [[Masayoshi Takanaka (高中正義)]] ]
[Genre:: Jazz]
[Played:: 10]
[Album:: [[An Insatiable High (1977)]]]
[Year:: 1977]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[E. S. P.]]
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
		intensity: page["E._S._P."]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
