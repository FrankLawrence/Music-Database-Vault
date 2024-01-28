---
tags: Song  
banner: "![[With The Beatles (1963).jpg]]"
---
[Time:: 2:08]
[Artist:: [[The Beatles]] ]
[Genre:: Rock]
[Played:: ]
[Album:: [[With The Beatles (1963)]]]
[Year:: 1963]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[Not A Second Time]]
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
		intensity: page["Not_A_Second_Time"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
