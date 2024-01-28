---
tags: Song ⭐⭐⭐⭐⭐ 
banner: "![[Arrival (1976).jpg]]"
---
[Time:: 4:02]
[Artist:: [[ABBA]] ]
[Genre:: Pop]
[Played:: 6]
[Album:: [[Arrival (1976)]]]
[Year:: 1976]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[Knowing Me, Knowing You]]
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
		intensity: page["Knowing_Me,_Knowing_You"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
