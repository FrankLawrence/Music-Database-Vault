---
tags: Song ⭐⭐⭐⭐ 
banner: "![[Frida ensam (1975).jpg]]"
---
[Time:: 4:14]
[Artist:: [[Anni-Frid Lyngstad]] ]
[Genre:: Pop]
[Played:: 2]
[Album:: [[Frida ensam (1975)]]]
[Year:: 1975]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[Fernando]]
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
		intensity: page["Fernando"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
