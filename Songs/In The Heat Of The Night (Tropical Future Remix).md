---
tags: Song ⭐ 
banner: "![[The Very Best Of Sandra [Disc 2] (2016).jpg]]"
---
[Time:: 4:04]
[Artist:: [[Sandra]] ]
[Genre:: Pop]
[Played:: ]
[Album:: [[The Very Best Of Sandra [Disc 2] (2016)]]]
[Year:: 2016]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[In The Heat Of The Night (Tropical Future Remix)]]
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
		intensity: page["In_The_Heat_Of_The_Night_(Tropical_Future_Remix)"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
