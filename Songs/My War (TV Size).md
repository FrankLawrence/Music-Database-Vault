---
tags: Song ⭐⭐⭐⭐ 
banner: "![[Attack on Titan Original Soundtrack (2021).jpg]]"
---
[Time:: 1:30]
[Artist:: [[Shinsei Kamattechan]] ]
[Genre:: Anime]
[Played:: 9]
[Album:: [[Attack on Titan Original Soundtrack (2021)]]]
[Year:: 2021]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[My War (TV Size)]]
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
		intensity: page["My_War_(TV_Size)"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
