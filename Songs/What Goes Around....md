---
tags: Song ⭐⭐⭐ 
banner: "![[FutureSex/Lovesounds (2006).jpg]]"
---
[Time:: 7:29]
[Artist:: [[Justin Timberlake]] ]
[Genre:: Pop]
[Played:: ]
[Album:: [[FutureSex/Lovesounds (2006)]]]
[Year:: 2006]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[What Goes Around...]]
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
		intensity: page["What_Goes_Around..."]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
