---
tags: Song ⭐⭐⭐⭐⭐ 
banner: "![[(Pronounced 'Lĕh-'nérd 'Skin-'nérd) (1973).jpg]]"
---
[Time:: 9:10]
[Artist:: [[Lynyrd Skynyrd]] ]
[Genre:: Southern Rock]
[Played:: 12]
[Album:: [[(Pronounced 'Lĕh-'nérd 'Skin-'nérd) (1973)]]]
[Year:: 1973]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[Freebird]]
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
		intensity: page["Freebird"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
