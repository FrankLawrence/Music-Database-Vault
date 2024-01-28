---
tags: Song ⭐⭐⭐⭐ 
banner: "![[Where The Light Is (2019).jpg]]"
---
[Time:: 2:57]
[Artist:: [[Surfaces]] ]
[Genre:: Hip Hop, Jazz, Reggae, Funk / Soul, Pop]
[Played:: 5]
[Album:: [[Where The Light Is (2019)]]]
[Year:: 2019]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[Sunday Best]]
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
		intensity: page["Sunday_Best"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
