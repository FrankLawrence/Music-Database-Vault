---
tags: Song ⭐⭐⭐⭐ 
banner: "![[Making Spirits Bright (1959).jpg]]"
---
[Time:: 1:58]
[Artist:: [[Dean Martin]] ]
[Genre:: Easy Listening]
[Played:: ]
[Album:: [[Making Spirits Bright (1959)]]]
[Year:: 1959]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[Let It Snow! Let It Snow! Let It Snow!]]
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
		intensity: page["Let_It_Snow!_Let_It_Snow!_Let_It_Snow!"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
