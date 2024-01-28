---
tags: Song ⭐⭐⭐⭐ 
banner: "![[Some Kind of Trouble (2010).jpg]]"
---
[Time:: 3:27]
[Artist:: [[James Blunt]] ]
[Genre:: ]
[Played:: 1]
[Album:: [[Some Kind of Trouble (2010)]]]
[Year:: 2010]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[If Time Is All I Have]]
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
		intensity: page["If_Time_Is_All_I_Have"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
