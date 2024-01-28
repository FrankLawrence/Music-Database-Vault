---
tags: Song ⭐⭐⭐⭐⭐ 💛
banner: "![[Chou Ikimonobakari Tennen Kinen Members (2014).jpg]]"
---
[Time:: 3:44]
[Artist:: [[Ikimonogakaru]] ]
[Genre:: J-Pop]
[Played:: 48]
[Album:: [[Chou Ikimonobakari Tennen Kinen Members (2014)]]]
[Year:: 2014]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[熱情のスペクトラム (Netsujo No Spectrum)]]
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
		intensity: page["熱情のスペクトラム_(Netsujo_No_Spectrum)"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
