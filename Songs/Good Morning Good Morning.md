---
tags: Song  
banner: "![[Sgt. Pepper's Lonely Hearts Club Band ().jpg]]"
---
[Time:: 2:41]
[Artist:: [[The Beatles]] ]
[Genre:: ]
[Played:: ]
[Album:: [[Sgt. Pepper's Lonely Hearts Club Band ()]]]
[Year:: ]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[Good Morning Good Morning]]
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
		intensity: page["Good_Morning_Good_Morning"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
