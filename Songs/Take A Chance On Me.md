---
tags: Song ⭐⭐⭐⭐⭐ 
banner: "![[ABBA: The Album (1977).jpg]]"
---
[Time:: 4:05]
[Artist:: [[ABBA]] ]
[Genre:: Pop]
[Played:: 5]
[Album:: [[ABBA: The Album (1977)]]]
[Year:: 1977]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[Take A Chance On Me]]
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
		intensity: page["Take_A_Chance_On_Me"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
