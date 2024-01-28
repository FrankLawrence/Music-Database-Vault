---
tags: Song ⭐⭐⭐⭐⭐ 
banner: "![[Hope (2016).jpg]]"
---
[Time:: 14:08]
[Artist:: [[Martin Garrix & Third Party]] ]
[Genre:: Progressive House]
[Played:: 12]
[Album:: [[Hope (2016)]]]
[Year:: 2016]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[Lions In The Wild]]
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
		intensity: page["Lions_In_The_Wild"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
