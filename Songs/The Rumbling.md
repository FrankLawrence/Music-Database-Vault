---
tags: Song ⭐⭐⭐⭐⭐ 💛
banner: "![[Attack on Titan Original Soundtrack (2017).jpg]]"
---
[Time:: 1:30]
[Artist:: [[SiM]] ]
[Genre:: J-Pop]
[Played:: 54]
[Album:: [[Attack on Titan Original Soundtrack (2017)]]]
[Year:: 2022]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[The Rumbling]]
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
		intensity: page["The_Rumbling"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
