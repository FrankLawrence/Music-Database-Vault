---
tags: Song ⭐⭐⭐⭐⭐ 
banner: "![[Jake Chudnow (2012).jpg]]"
---
[Time:: 4:03]
[Artist:: [[Jake Chudnow]] ]
[Genre:: Instrumental]
[Played:: 10]
[Album:: [[Jake Chudnow (2012)]]]
[Year:: 2012]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[Hydrogen]]
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
		intensity: page["Hydrogen"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
