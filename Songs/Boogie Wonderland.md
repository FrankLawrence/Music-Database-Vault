---
tags: Song ⭐⭐⭐⭐⭐ 
banner: "![[I Am (1979).jpg]]"
---
[Time:: 4:48]
[Artist:: [[Earth, Wind & Fire]] ]
[Genre:: Disco]
[Played:: 25]
[Album:: [[I Am (1979)]]]
[Year:: 1979]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[Boogie Wonderland]]
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
		intensity: page["Boogie_Wonderland"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
