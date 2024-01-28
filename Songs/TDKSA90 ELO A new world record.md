---
tags: Song ⭐⭐ 
banner: "![[A new world record (1980).jpg]]"
---
[Time:: 47:16]
[Artist:: [[ELO]] ]
[Genre:: ]
[Played:: 1]
[Album:: [[A new world record (1980)]]]
[Year:: 1980]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[TDKSA90 ELO A new world record]]
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
		intensity: page["TDKSA90_ELO_A_new_world_record"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
