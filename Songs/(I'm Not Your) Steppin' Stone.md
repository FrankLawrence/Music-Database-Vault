---
tags: Song  
banner: "![[The Monkees Greatest Hits (1966).jpg]]"
---
[Time:: 2:23]
[Artist:: [[The Monkees]] ]
[Genre:: Pop]
[Played:: 3]
[Album:: [[The Monkees Greatest Hits (1966)]]]
[Year:: 1966]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[(I'm Not Your) Steppin' Stone]]
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
		intensity: page["(I'm_Not_Your)_Steppin'_Stone"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
