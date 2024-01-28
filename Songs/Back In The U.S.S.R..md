---
tags: Song ⭐⭐⭐⭐⭐ 
banner: "![[The Beatles (1968).jpg]]"
---
[Time:: 2:43]
[Artist:: [[The Beatles]] ]
[Genre:: Rock]
[Played:: ]
[Album:: [[The Beatles (1968)]]]
[Year:: 1968]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[Back In The U.S.S.R.]]
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
		intensity: page["Back_In_The_U.S.S.R."]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
