---
tags: Song ⭐⭐⭐⭐⭐ 
banner: "![[Greatest Kiss (1997).jpg]]"
---
[Time:: 3:39]
[Artist:: [[Kiss]] ]
[Genre:: Rock]
[Played:: ]
[Album:: [[Greatest Kiss (1997)]]]
[Year:: 1997]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[Shout It Out Loud (New Video Version)]]
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
		intensity: page["Shout_It_Out_Loud_(New_Video_Version)"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
