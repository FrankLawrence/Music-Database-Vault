---
tags: Song  
banner: "![[The Works (1977).jpg]]"
---
[Time:: 3:41]
[Artist:: [[Queen]] ]
[Genre:: Rock]
[Played:: ]
[Album:: [[The Works (1977)]]]
[Year:: 1977]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[Hammer To Fall]]
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
		intensity: page["Hammer_To_Fall"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
