---
tags: Song ⭐⭐ 

[Time:: 5:45]
[Artist:: [[Haddaway]] ]
[Genre:: Rock/Pop]
[Played:: ]
[Album:: ]
[Year:: 2018]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[What is Love (Deepjack & Mr  Nu Remix)]]
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
		intensity: page["What_is_Love_(Deepjack_Eyes_Without_A_Face_Mr__Nu_Remix)"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
