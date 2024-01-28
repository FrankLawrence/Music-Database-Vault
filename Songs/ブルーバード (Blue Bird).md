---
tags: Song ⭐⭐⭐⭐⭐ 💛
banner: "![[Chou Ikimonobakari Tennen Kinen Members (2008).jpg]]"
---
[Time:: 3:39]
[Artist:: [[Ikimonogakaru]] ]
[Genre:: J-Pop]
[Played:: 41]
[Album:: [[Chou Ikimonobakari Tennen Kinen Members (2008)]]]
[Year:: 2008]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[ブルーバード (Blue Bird)]]
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
		intensity: page["ブルーバード_(Blue_Bird)"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
