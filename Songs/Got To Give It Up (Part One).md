---
tags: Song ⭐⭐ 
banner: "![[Pure Disco (1977).jpg]]"
---
[Time:: 4:08]
[Artist:: [[Marvin Gaye]] ]
[Genre:: Pop]
[Played:: ]
[Album:: [[Pure Disco (1977)]]]
[Year:: 1977]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[Got To Give It Up (Part One)]]
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
		intensity: page["Got_To_Give_It_Up_(Part_One)"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
