---
tags: Song ⭐⭐⭐ 
banner: "![[I (2015).jpg]]"
---
[Time:: 3:08]
[Artist:: [[Felix Jaehn]] [[Jasmine Thompson]] ]
[Genre:: EDM]
[Played:: 6]
[Album:: [[I (2015)]]]
[Year:: 2015]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[Ain't Nobody (Loves Me Better)]]
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
		intensity: page["Ain't_Nobody_(Loves_Me_Better)"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
