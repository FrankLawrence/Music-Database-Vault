---
tags: Song ⭐⭐⭐⭐ 
banner: "![[Viva La Vida Or Death And All His Friends (2008).jpg]]"
---
[Time:: 4:02]
[Artist:: [[Coldplay]] ]
[Genre:: Rock, Pop]
[Played:: 2]
[Album:: [[Viva La Vida Or Death And All His Friends (2008)]]]
[Year:: 2008]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[Viva La Vida]]
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
		intensity: page["Viva_La_Vida"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
