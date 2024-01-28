---
tags: Song  
banner: "![[Vital Idol (1987).jpg]]"
---
[Time:: 5:11]
[Artist:: [[Billy Idol]] ]
[Genre:: Rock]
[Played:: ]
[Album:: [[Vital Idol (1987)]]]
[Year:: 1987]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[Hot In The City]]
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
		intensity: page["Hot_In_The_City"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
