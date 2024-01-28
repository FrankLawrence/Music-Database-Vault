---
tags: Song  
banner: "![[Stark Wie Zwei (2008).jpg]]"
---
[Time:: 5:07]
[Artist:: [[Udo Lindenberg]] [[Till Brönner]] ]
[Genre:: German Rock-Pop]
[Played:: ]
[Album:: [[Stark Wie Zwei (2008)]]]
[Year:: 2008]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[Verbotene Stadt]]
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
		intensity: page["Verbotene_Stadt"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
