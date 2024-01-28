---
tags: Song ⭐⭐ 
banner: "![[Ghost Stories (2014).jpg]]"
---
[Time:: 5:24]
[Artist:: [[Coldplay]] ]
[Genre:: Rock, Pop]
[Played:: 2]
[Album:: [[Ghost Stories (2014)]]]
[Year:: 2014]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[O (Fly On)]]
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
		intensity: page["O_(Fly_On)"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
