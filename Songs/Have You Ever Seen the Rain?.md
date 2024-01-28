---
tags: Song ⭐⭐⭐ 
banner: "![[Pendulum (1971).jpg]]"
---
[Time:: 3:04]
[Artist:: [[Creedence Clearwater Revival]] ]
[Genre:: Country Rock]
[Played:: ]
[Album:: [[Pendulum (1971)]]]
[Year:: 1971]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[Have You Ever Seen the Rain?]]
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
		intensity: page["Have_You_Ever_Seen_the_Rain?"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
