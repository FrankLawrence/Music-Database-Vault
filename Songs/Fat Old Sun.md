---
tags: Song ⭐⭐⭐ 
banner: "![[Atom Heart Mother (1970).jpg]]"
---
[Time:: 5:24]
[Artist:: [[Pink Floyd]] ]
[Genre:: Progressive Rock]
[Played:: 5]
[Album:: [[Atom Heart Mother (1970)]]]
[Year:: 1970]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[Fat Old Sun]]
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
		intensity: page["Fat_Old_Sun"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
