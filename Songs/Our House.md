---
tags: Song  
banner: "![[The Rise & Fall (1982).jpg]]"
---
[Time:: 3:22]
[Artist:: [[Madness]] ]
[Genre:: New Wave]
[Played:: ]
[Album:: [[The Rise & Fall (1982)]]]
[Year:: 1982]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[Our House]]
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
		intensity: page["Our_House"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
