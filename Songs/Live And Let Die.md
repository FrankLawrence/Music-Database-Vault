---
tags: Song ⭐⭐ 
banner: "![[All The Best (1973).jpg]]"
---
[Time:: 3:13]
[Artist:: [[Paul McCartney & Wings]] ]
[Genre:: Pop]
[Played:: ]
[Album:: [[All The Best (1973)]]]
[Year:: 1973]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[Live And Let Die]]
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
		intensity: page["Live_And_Let_Die"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
