---
tags: Song  
banner: "![[Barry White's Greatest Hits (1975).jpg]]"
---
[Time:: 5:23]
[Artist:: [[Barry White]] ]
[Genre:: R&B]
[Played:: ]
[Album:: [[Barry White's Greatest Hits (1975)]]]
[Year:: 1975]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[Standing In The Shadows Of Love]]
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
		intensity: page["Standing_In_The_Shadows_Of_Love"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
