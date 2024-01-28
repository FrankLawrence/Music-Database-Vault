---
tags: Song ⭐⭐⭐ 
banner: "![[30 #1 Hits (2002).jpg]]"
---
[Time:: 3:33]
[Artist:: [[Elvis Presley]] ]
[Genre:: Rock]
[Played:: 36]
[Album:: [[30 #1 Hits (2002)]]]
[Year:: 2002]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[A Little Less Conversation (JXL Radio Edit Remix)]]
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
		intensity: page["A_Little_Less_Conversation_(JXL_Radio_Edit_Remix)"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
