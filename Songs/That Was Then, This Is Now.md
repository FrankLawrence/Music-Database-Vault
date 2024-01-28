---
tags: Song ⭐⭐ 
banner: "![[The Monkees Greatest Hits (1986).jpg]]"
---
[Time:: 4:04]
[Artist:: [[Micky Dolenz & Peter Tork]] ]
[Genre:: Pop]
[Played:: ]
[Album:: [[The Monkees Greatest Hits (1986)]]]
[Year:: 1986]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[That Was Then, This Is Now]]
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
		intensity: page["That_Was_Then,_This_Is_Now"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
