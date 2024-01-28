---
tags: Song  
banner: "![[The Visitors (1981).jpg]]"
---
[Time:: 3:17]
[Artist:: [[ABBA]] ]
[Genre:: Pop]
[Played:: 1]
[Album:: [[The Visitors (1981)]]]
[Year:: 1981]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[When All Is Said And Done]]
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
		intensity: page["When_All_Is_Said_And_Done"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
