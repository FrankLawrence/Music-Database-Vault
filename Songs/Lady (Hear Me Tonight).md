---
tags: Song ⭐⭐⭐⭐⭐ 
banner: "![[Modjo (2000).jpg]]"
---
[Time:: 3:44]
[Artist:: [[Modjo]] ]
[Genre:: French house]
[Played:: 24]
[Album:: [[Modjo (2000)]]]
[Year:: 2000]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[Lady (Hear Me Tonight)]]
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
		intensity: page["Lady_(Hear_Me_Tonight)"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
