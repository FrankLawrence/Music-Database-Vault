---
tags: Song ⭐⭐⭐ 
banner: "![[Idea (1968).jpg]]"
---
[Time:: 3:08]
[Artist:: [[Bee Gees]] ]
[Genre:: Pop]
[Played:: 1]
[Album:: [[Idea (1968)]]]
[Year:: 1968]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[I've Gotta Get A Message To You]]
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
		intensity: page["I've_Gotta_Get_A_Message_To_You"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
