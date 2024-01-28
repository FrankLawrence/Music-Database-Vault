---
tags: Song ⭐⭐⭐⭐⭐ 
banner: "![[The Beatles (1968).jpg]]"
---
[Time:: 1:42]
[Artist:: [[The Beatles]] ]
[Genre:: Rock]
[Played:: 2]
[Album:: [[The Beatles (1968)]]]
[Year:: 1968]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[Why Don't We Do It In The Road?]]
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
		intensity: page["Why_Don't_We_Do_It_In_The_Road?"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
