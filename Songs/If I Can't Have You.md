---
tags: Song ⭐⭐ 
banner: "![[Pure Disco (1977).jpg]]"
---
[Time:: 2:55]
[Artist:: [[Yvonne Elliman]] ]
[Genre:: Pop]
[Played:: ]
[Album:: [[Pure Disco (1977)]]]
[Year:: 1977]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[If I Can't Have You]]
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
		intensity: page["If_I_Can't_Have_You"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
