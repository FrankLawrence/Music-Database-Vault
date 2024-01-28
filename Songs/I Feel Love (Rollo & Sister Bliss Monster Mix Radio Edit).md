---
tags: Song ⭐⭐ 
banner: "![[Pure Disco (1995).jpg]]"
---
[Time:: 3:55]
[Artist:: [[Donna Summer]] ]
[Genre:: Pop]
[Played:: ]
[Album:: [[Pure Disco (1995)]]]
[Year:: 1995]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[I Feel Love (Rollo & Sister Bliss Monster Mix Radio Edit)]]
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
		intensity: page["I_Feel_Love_(Rollo_Eyes_Without_A_Face_Sister_Bliss_Monster_Mix_Radio_Edit)"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
