---
tags: Song ⭐⭐⭐⭐⭐ 💛
banner: "![[The Works (1977).jpg]]"
---
[Time:: 4:19]
[Artist:: [[Queen]] ]
[Genre:: Rock]
[Played:: 51]
[Album:: [[The Works (1977)]]]
[Year:: 1977]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[I Want To Break Free]]
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
		intensity: page["I_Want_To_Break_Free"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
