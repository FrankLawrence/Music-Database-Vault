---
tags: Song ⭐ 💔
banner: "![[All The Best (1974).jpg]]"
---
[Time:: 4:24]
[Artist:: [[Paul McCartney & Wings]] ]
[Genre:: Pop]
[Played:: ]
[Album:: [[All The Best (1974)]]]
[Year:: 1974]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[Junior's Farm]]
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
		intensity: page["Junior's_Farm"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
