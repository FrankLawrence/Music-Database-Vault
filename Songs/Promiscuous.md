---
tags: Song ⭐⭐⭐⭐ 💛
banner: "![[Loose (2006).jpg]]"
---
[Time:: 4:03]
[Artist:: [[Nelly Furtado]] ]
[Genre:: Electropop]
[Played:: 18]
[Album:: [[Loose (2006)]]]
[Year:: 2006]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[Promiscuous]]
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
		intensity: page["Promiscuous"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
