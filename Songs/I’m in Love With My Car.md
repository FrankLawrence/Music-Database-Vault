---
tags: Song  
banner: "![[A Night at the Opera (1975).jpg]]"
---
[Time:: 3:05]
[Artist:: [[Queen]] ]
[Genre:: ]
[Played:: ]
[Album:: [[A Night at the Opera (1975)]]]
[Year:: 1975]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[I’m in Love With My Car]]
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
		intensity: page["I’m_in_Love_With_My_Car"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
