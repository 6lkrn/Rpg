 ```dataviewjs 
const calendarData = { 
color: "githubGreen", 
entries: [], // <- your entries 
} 

renderHeatmapCalendar(this.container, 
calendarData) 
```

```dataviewjs

dv.span("**🏋️ Exercise 🏋️**")

const calendarData = {
    colors: {
        red: ["#ff9e82","#ff7b55","#ff4d1a","#e73400","#bd2a00",]
    },
    entries: []
}

for(let page of dv.pages('"daily notes"').where(p=>p.exercise)){
    calendarData.entries.push({
        date: page.file.name,
        intensity: page.exercise,
        content: await dv.span(`[](${page.file.name})`), //for hover preview
    })
       
}

renderHeatmapCalendar(this.container, calendarData)

```

```dataviewjs
dv.span("**💸 Money Spent 💸**")

const calendarData = {
    entries: [],
}

for(let page of dv.pages('"daily notes"').where(p=>p.moneySpent)){

    calendarData.entries.push({
        date: page.file.name,
        intensity: page.moneySpent,
        content: await dv.span(`[](${page.file.name})`), //for hover preview
    })  
}

renderHeatmapCalendar(this.container, calendarData)

```


```data
```

```dataviewjs

dv.span("**🔗 Writing **- Dont break the chain! 🔗🔗🔗🔗")

const calendarData = {
    colors: {
        white: ["#fff","#fff","#fff","#fff","#fff"],
    },
    entries: []
}

for(let page of dv.pages('"daily notes"').where(p=>p.writing)){
	 
    calendarData.entries.push({
        date: page.file.name,
        content: await dv.span(`[🔗](${page.file.name})`), //for hover preview
    }) 
}

//console.log(calendarData)
	
renderHeatmapCalendar(this.container, calendarData)

```

```dataviewjs
//
// Using multiple colors for different variations of entry
//

dv.span("**👫 Social tracker 🧑‍🤝‍🧑**")

const calendarData = {
    colors: {
        blue: ["#8cb9ff","#69a3ff","#428bff","#1872ff","#0058e2"],
        pink: ["#ff96cb","#ff70b8","#ff3a9d","#ee0077","#c30062"],
    },
    entries: []
}

for(let page of dv.pages('"daily notes"').where(p=>p.social)){
    let color = ""
    if(page.social.greg.initiative == "incoming"){color="pink"}
    
    calendarData.entries.push({
        date: page.file.name,
        intensity: page.social.greg.time,
        color: color,
        content: await dv.span(`[](${page.file.name})`), //for hover preview
    })
       
}

renderHeatmapCalendar(this.container, calendarData)

```

```dataviewjs

dv.span("** 😊 Mood  😥**")

const hue1 = 13 //red
const hue2 = 132 //green

const calendarData = { 
    intensityScaleStart: 1,
    intensityScaleEnd: 9,
    colors: {
        red2green: [
            `hsl(${hue1}, 100%, 37%)`,     // 1 - darkest red
            `hsl(${hue1}, 100%, 50%)`,     // 2 - 
            `hsl(${hue1}, 100%, 60%)`,     // 3 - 
            `hsl(${hue1}, 100%, 77%)`,     // 4 - lightest red
            `hsl(0, 0%, 80%)`,             // 5 - neutral gray
            `hsl(${hue2*0.7}, 70%, 72%)`,  // 6 - lightest green
            `hsl(${hue2*0.85}, 43%, 56%)`, // 7 - 
            `hsl(${hue2}, 49%, 36%)`,      // 8 - 
            `hsl(${hue2}, 59%, 24%)`,      // 9 - darkest green
        ],
    },
    entries: []
}

for(let page of dv.pages('"daily notes"').where(p=>p.mood)){ 

    calendarData.entries.push({
        date: page.file.name, 
        intensity: page.mood,
        content: await dv.span(`[](${page.file.name})`), //for hover preview
    })
      
}

renderHeatmapCalendar(this.container, calendarData)

```
```dataviewjs

dv.span("**🏋️ Exercise 🏋️**")

const calendarData = {
    year: 2022,
    colors: {
        red: ["#ff9e82","#ff7b55","#ff4d1a","#e73400","#bd2a00",]
    },
    entries: []
}

for(let page of dv.pages('"daily notes"').where(p=>p.exercise)){
    calendarData.entries.push({
        date: page.file.name,
        intensity: page.exercise
    })
       
}

renderHeatmapCalendar(this.container, calendarData)

```
