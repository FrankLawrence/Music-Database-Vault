---
tags: Song ⭐⭐⭐ 
banner: "![[The Best Of The Alan Parsons Project (1979).jpg]]"
---
[Time:: 3:12]
[Artist:: [[Alan Parsons Project]] ]
[Genre:: Pop]
[Played:: 1]
[Album:: [[The Best Of The Alan Parsons Project (1979)]]]
[Year:: 1979]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[I Wouldn't Want To Be Like You]]
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
		intensity: page["I_Wouldn't_Want_To_Be_Like_You"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
