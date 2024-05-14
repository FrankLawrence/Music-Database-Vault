---
tags: Song ⭐⭐⭐ 
banner: "![[Kaleidoscope EP (2017).jpg]]"
---
[Time:: 3:55]
[Artist:: [[Coldplay]] ]
[Genre:: Rock, Pop]
[Played:: 3]
[Album:: [[Kaleidoscope EP (2017)]]]
[Year:: 2017]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[Miracles (Someone Special)]]
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
		intensity: page["Miracles_(Someone_Special)"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
