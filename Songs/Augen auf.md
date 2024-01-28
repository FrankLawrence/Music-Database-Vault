---
tags: Song ⭐⭐⭐⭐⭐ 
banner: "![[Ich und meine Maske (2008).jpg]]"
---
[Time:: 4:35]
[Artist:: [[SIDO]] ]
[Genre:: Hip-Hop/Rap]
[Played:: 7]
[Album:: [[Ich und meine Maske (2008)]]]
[Year:: 2008]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[Augen auf]]
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
		intensity: page["Augen_auf"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
