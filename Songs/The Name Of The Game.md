---
tags: Song ⭐⭐⭐⭐⭐ 💛
banner: "![[The Album (1977).jpg]]"
---
[Time:: 4:00]
[Artist:: [[ABBA]] ]
[Genre:: Electronic, Rock, Pop, Stage & Screen]
[Played:: 21]
[Album:: [[The Album (1977)]]]
[Year:: 1977]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[The Name Of The Game]]
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
		intensity: page["The_Name_Of_The_Game"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
