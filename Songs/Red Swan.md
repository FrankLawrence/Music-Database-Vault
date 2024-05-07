---
tags: Song ⭐⭐⭐⭐⭐ 💛
banner: "![[Attack on Titan Original Soundtrack ().jpg]]"
---
[Time:: 4:29]
[Artist:: [[Yoshiki]] [[Hyde]] ]
[Genre:: J-Pop]
[Played:: 66]
[Album:: [[Attack on Titan Original Soundtrack ()]]]
[Year:: ]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[Red Swan]]
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
		intensity: page["Red_Swan"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
