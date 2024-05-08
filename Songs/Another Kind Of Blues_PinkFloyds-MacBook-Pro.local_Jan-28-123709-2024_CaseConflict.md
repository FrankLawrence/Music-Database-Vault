---
tags: Song ⭐⭐⭐⭐⭐ 💛
banner: "![[Puppy (2001).jpg]]"
---
[Time:: 4:34]
[Artist:: [[Fluke]] ]
[Genre:: Soundtrack]
[Played:: 67]
[Album:: [[Puppy (2001)]]]
[Year:: 2001]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[Another kind of Blues]]
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
		intensity: page["Another_kind_of_Blues"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
