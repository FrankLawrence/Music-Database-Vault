---
tags: Song ⭐⭐⭐⭐ 
banner: "![[Barry White's Greatest Hits (1975).jpg]]"
---
[Time:: 4:32]
[Artist:: [[Barry White]] ]
[Genre:: R&B]
[Played:: 3]
[Album:: [[Barry White's Greatest Hits (1975)]]]
[Year:: 1975]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[Can't Get Enough Of Your Love, Babe]]
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
		intensity: page["Can't_Get_Enough_Of_Your_Love,_Babe"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
