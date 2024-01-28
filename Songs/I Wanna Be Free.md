---
tags: Song  
banner: "![[The Monkees Greatest Hits (1966).jpg]]"
---
[Time:: 2:27]
[Artist:: [[The Monkees]] ]
[Genre:: Pop]
[Played:: 1]
[Album:: [[The Monkees Greatest Hits (1966)]]]
[Year:: 1966]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[I Wanna Be Free]]
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
		intensity: page["I_Wanna_Be_Free"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
