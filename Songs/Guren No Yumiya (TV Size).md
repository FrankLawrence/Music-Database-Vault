---
tags: Song ⭐⭐⭐⭐ 
banner: "![[Attack on Titan Original Soundtrack (2013).jpg]]"
---
[Time:: 1:32]
[Artist:: [[Linked Horizon]] ]
[Genre:: Anime]
[Played:: 9]
[Album:: [[Attack on Titan Original Soundtrack (2013)]]]
[Year:: 2013]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[Guren No Yumiya (TV Size)]]
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
		intensity: page["Guren_No_Yumiya_(TV_Size)"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
