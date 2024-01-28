---
tags: Song  
banner: "![[Barry White's Greatest Hits (1975).jpg]]"
---
[Time:: 3:41]
[Artist:: [[Barry White]] ]
[Genre:: R&B]
[Played:: 2]
[Album:: [[Barry White's Greatest Hits (1975)]]]
[Year:: 1975]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[I've Found Someone]]
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
		intensity: page["I've_Found_Someone"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
