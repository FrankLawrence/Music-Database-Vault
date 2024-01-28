---
tags: Song ⭐⭐⭐⭐⭐ 💛
banner: "![[Ylang Ylang - EP.jpg]]"
---
[Time:: 3:33]
[Artist:: [[FKJ]] [[((( O ))]] ]
[Genre:: Alternative]
[Played:: 26]
[Album:: [[Ylang Ylang - EP]]]
[Year:: 2019]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[Ylang Ylang]]
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
		intensity: page["Ylang_Ylang"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
