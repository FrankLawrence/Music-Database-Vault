---
tags: Song  
banner: "![[Ultimate FM Gold (2022).jpg]]"
---
[Time:: 5:33]
[Artist:: [[A Flock of Seagulls]] ]
[Genre:: Pop]
[Played:: ]
[Album:: [[Ultimate FM Gold (2022)]]]
[Year:: 2022]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[Wishing (If I Had a Photograph of You)]]
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
		intensity: page["Wishing_(If_I_Had_a_Photograph_of_You)"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
