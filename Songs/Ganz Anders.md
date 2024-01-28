---
tags: Song  
banner: "![[Stark Wie Zwei (2008).jpg]]"
---
[Time:: 4:07]
[Artist:: [[Udo Lindenberg]] [[Jan Delay]] ]
[Genre:: German Rock-Pop]
[Played:: ]
[Album:: [[Stark Wie Zwei (2008)]]]
[Year:: 2008]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[Ganz Anders]]
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
		intensity: page["Ganz_Anders"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
