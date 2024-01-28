---
tags: Song ⭐⭐⭐⭐ 
banner: "![[Stellar (2018).jpg]]"
---
[Time:: 3:45]
[Artist:: [[Sansixto]] [[Max Adrian & Aftermarket]] ]
[Genre:: Big Room]
[Played:: 2]
[Album:: [[Stellar (2018)]]]
[Year:: 2018]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[Stellar (Extended Mix)]]
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
		intensity: page["Stellar_(Extended_Mix)"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
