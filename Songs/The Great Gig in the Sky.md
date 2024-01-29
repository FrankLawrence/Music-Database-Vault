---
tags: Song ⭐⭐⭐⭐ 
banner: "![[The Dark Side of the Moon (1973).jpg]]"
---
[Time:: 4:44]
[Artist:: [[Pink Floyd]] ]
[Genre:: Progressive Rock]
[Played:: 16]
[Album:: [[The Dark Side of the Moon (1973)]]]
[Year:: 1973]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[The Great Gig in the Sky]]
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
		intensity: page["The_Great_Gig_in_the_Sky"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
