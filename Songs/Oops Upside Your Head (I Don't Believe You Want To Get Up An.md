---
tags: Song ⭐⭐⭐ 
banner: "![[Pure Disco (1979).jpg]]"
---
[Time:: 3:26]
[Artist:: [[The Gap Band]] ]
[Genre:: Pop]
[Played:: ]
[Album:: [[Pure Disco (1979)]]]
[Year:: 1979]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[Oops Upside Your Head (I Don't Believe You Want To Get Up An]]
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
		intensity: page["Oops_Upside_Your_Head_(I_Don't_Believe_You_Want_To_Get_Up_An"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
