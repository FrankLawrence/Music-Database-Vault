---
tags: Song  
banner: "![[The Best Of Aretha Franklin (1984).jpg]]"
---
[Time:: 3:28]
[Artist:: [[Aretha Franklin]] ]
[Genre:: R&B]
[Played:: ]
[Album:: [[The Best Of Aretha Franklin (1984)]]]
[Year:: 1984]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[Until You Come Back To Me (That's What I'm Gonna Do)]]
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
		intensity: page["Until_You_Come_Back_To_Me_(That's_What_I'm_Gonna_Do)"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
