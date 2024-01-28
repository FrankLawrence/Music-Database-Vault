---
tags: Song ⭐ 💔
banner: "![[Anthology 1 [Disc 2] (1963).jpg]]"
---
[Time:: 2:06]
[Artist:: [[The Beatles]] ]
[Genre:: Rock]
[Played:: ]
[Album:: [[Anthology 1 [Disc 2] (1963)]]]
[Year:: 1963]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[Speech: Eric Morecambe And Ernie Wise]]
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
		intensity: page["Speech:_Eric_Morecambe_And_Ernie_Wise"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
