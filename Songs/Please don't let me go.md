---
tags: Song ⭐⭐⭐⭐ 
banner: "![[Olly Murs (2012).jpg]]"
---
[Time:: 3:28]
[Artist:: [[Olly Murs]] ]
[Genre:: Pop]
[Played:: ]
[Album:: [[Olly Murs (2012)]]]
[Year:: 2012]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[Please don't let me go]]
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
		intensity: page["Please_don't_let_me_go"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
