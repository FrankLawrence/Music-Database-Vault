---
tags: Song ⭐⭐⭐⭐ 
banner: "![[Ultimate FM Gold (2022).jpg]]"
---
[Time:: 4:19]
[Artist:: [[The Dream Academy]] ]
[Genre:: Pop]
[Played:: 5]
[Album:: [[Ultimate FM Gold (2022)]]]
[Year:: 2022]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[Life in a Northern Town]]
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
		intensity: page["Life_in_a_Northern_Town"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
