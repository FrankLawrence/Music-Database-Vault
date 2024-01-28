---
tags: Song  
banner: "![[Out of Our Heads (1965).jpg]]"
---
[Time:: 3:44]
[Artist:: [[The Rolling Stones]] ]
[Genre:: Rock]
[Played:: 1]
[Album:: [[Out of Our Heads (1965)]]]
[Year:: 1965]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[(I Can't Get No) Satisfaction]]
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
		intensity: page["(I_Can't_Get_No)_Satisfaction"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
