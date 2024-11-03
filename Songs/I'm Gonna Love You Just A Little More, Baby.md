---
tags: Song  
banner: "![[Barry White's Greatest Hits (1975).jpg]]"
---
[Time:: 4:13]
[Artist:: [[Barry White]] ]
[Genre:: R&B]
[Played:: 5]
[Album:: [[Barry White's Greatest Hits (1975)]]]
[Year:: 1975]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[I'm Gonna Love You Just A Little More, Baby]]
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
		intensity: page["I'm_Gonna_Love_You_Just_A_Little_More,_Baby"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
