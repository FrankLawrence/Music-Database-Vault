---
tags: Song  
banner: "![[The Best Of Aretha Franklin (1984).jpg]]"
---
[Time:: 3:17]
[Artist:: [[Aretha Franklin]] ]
[Genre:: R&B]
[Played:: ]
[Album:: [[The Best Of Aretha Franklin (1984)]]]
[Year:: 1984]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[Right Woman - Do Right Man]]
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
		intensity: page["Right_Woman_-_Do_Right_Man"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
