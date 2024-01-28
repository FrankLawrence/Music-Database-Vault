---
tags: Song  
banner: ""
---
[Time:: 3:06]
[Artist:: [[Amy Winehouse]] ]
[Genre:: R&B]
[Played:: 2]
[Album:: [[Back in Black (2007)]]]
[Year:: 2007]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[Amy Winehouse - Back To Black]]
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
		intensity: page["Amy_Winehouse_-_Back_To_Black"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
