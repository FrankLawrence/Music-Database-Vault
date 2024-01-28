---
tags: Song  
banner: "![[The Monkees Greatest Hits (1966).jpg]]"
---
[Time:: 2:47]
[Artist:: [[The Monkees]] ]
[Genre:: Pop]
[Played:: ]
[Album:: [[The Monkees Greatest Hits (1966)]]]
[Year:: 1966]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[Last Train To Clarksville]]
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
		intensity: page["Last_Train_To_Clarksville"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
