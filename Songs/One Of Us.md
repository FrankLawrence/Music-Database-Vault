---
tags: Song  
banner: "![[The Visitors (1981).jpg]]"
---
[Time:: 3:58]
[Artist:: [[ABBA]] ]
[Genre:: Pop]
[Played:: 80]
[Album:: [[The Visitors (1981)]]]
[Year:: 1981]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[One Of Us]]
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
		intensity: page["One_Of_Us"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
