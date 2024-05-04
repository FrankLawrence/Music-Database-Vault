---
tags: Song ⭐⭐⭐⭐ 
banner: "![[A Rush of Blood To The Head ().jpg]]"
---
[Time:: 4:57]
[Artist:: [[Coldplay]] ]
[Genre:: Soul]
[Played:: 9]
[Album:: [[A Rush of Blood To The Head ()]]]
[Year:: ]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[God Put A Smile Upon Your Face]]
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
		intensity: page["God_Put_A_Smile_Upon_Your_Face"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
