---
tags: Song  
banner: "![[Alles klar auf der Andrea Doria (1973).jpg]]"
---
[Time:: 4:00]
[Artist:: [[Udo Lindenberg]] ]
[Genre:: German Rock-Pop]
[Played:: ]
[Album:: [[Alles klar auf der Andrea Doria (1973)]]]
[Year:: 1973]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[Er wollte nach London]]
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
		intensity: page["Er_wollte_nach_London"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
