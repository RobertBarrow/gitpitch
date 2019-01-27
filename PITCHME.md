# Let's Get Started

---
@title[Introducing Rob]
## Introducing Rob

![](assets/images/myAvatar.png)

---
@title[Biggest challenges in Software Development]
@snap[north-west]
### Biggest challenges in software development
@snapend

@snap[west span-55]
@ul[spaced text]
- Time to market
- Competition (global)
- Return on investment
- Risk mitigation
- Predictability
@ulend
@snapend

---
@title[Agile Metrics]
@snap[north-west]
# Agile Metrics
@snapend

@snap[west span-55]
@ul[spaced text]
- Burndown ~ measuring progress
- Velocity ~ measuring predictablity
- *Cumulative flow* ~ increasing predictability
@ulend
@snapend

---
@title[Agile Metrics]
# Burndown charts

---
@title[Sprint Burndown chart]
## Sprint Burndown chart

<canvas data-chart="line">
<!-- 
{
 "data": {
  "labels": ["Day 1","Day 2","Day 3","Day 4","Day 5","Day 6","Day 7","Day 8","Day 9","Day 10"],
  "datasets": [
   {
    "data":[60,53,47,39,33,27,22,15,9,2],
    "label":"Story points remaining","backgroundColor":"rgba(20,120,120,.8)",
    "fill": true
   }
  ]
 }, 
 "options": { "responsive": "true" }
}
-->
</canvas>

---
@title[Epic Burndown chart]
## Epic Burndown chart

<canvas data-chart="line">
<!-- 
{
 "data": {
  "labels": ["Sprint 1","Sprint 2","Sprint 3","Sprint 4","Sprint 5","Sprint 6","Sprint 7","Sprint 8","Sprint 9","Sprint 10"],
  "datasets": [
   {
    "data":[307,247,194,147,108,75,48,26,11,2],
    "label":"Story points remaining","backgroundColor":"rgba(20,220,220,.8)",
    "fill": true
   }
  ]
 }, 
 "options": { "responsive": "true" }
}
-->
</canvas>

---
@title[Effort based velocity]
## Velocity 

---
@title[Story Points Delivered]
### Story points delivered
<canvas data-chart="line">
<!-- 
{
 "data": {
  "labels": ["Sprint 0","Sprint 1"," Sprint 2","Sprint 3","Sprint 4","Sprint 5","Sprint 6","Sprint 7","Sprint 8","Sprint 9","Sprint 10"],
  "datasets": [
   {
    "data":[0,59,61,60,61,58,59,60,58,60,59],
    "label":"Story points","backgroundColor":"rgba(20,220,220,.8)",
    "fill": true
   }
  ]
 }, 
 "options": { "responsive": "true" }
}
-->
</canvas>

---
@title[Average Velocity]
### Average Velocity
<canvas data-chart="line">
<!-- 
{
 "data": {
  "labels": ["Sprint 0","Sprint 1"," Sprint 2","Sprint 3","Sprint 4","Sprint 5","Sprint 6","Sprint 7","Sprint 8","Sprint 9","Sprint 10"],
  "datasets": [
   {
    "data":[0,29.5,40,45,48.2,49.83,51.14,52.25,52.88,53.6,54.09],
    "label":"Average Velocity","backgroundColor":"rgba(220,120,120,.8)",
    "fill": false
   },
   {
    "data":[0,59,61,60,61,58,59,60,58,60,59],
    "label":"Story points","backgroundColor":"rgba(20,220,220,.8)",
    "fill": true
   }
  ]
 }, 
 "options": { "responsive": "true" }
}
-->
</canvas>

---
@title[Rolling Average]
### Rolling Average
<canvas data-chart="line">
<!-- 
{
 "data": {
  "labels": ["Sprint 0","Sprint 1"," Sprint 2","Sprint 3","Sprint 4","Sprint 5","Sprint 6","Sprint 7","Sprint 8","Sprint 9","Sprint 10"],
  "datasets": [
   {
    "data":[0,59,60,60,60.25,59.8,59.67,59.83,59.33,59.33,59],
    "label":"Rolling Average","backgroundColor":"rgba(120,120,120,.8)",
    "fill": false
   },
   {
    "data":[0,59,61,60,61,58,59,60,58,60,59],
    "label":"Story points","backgroundColor":"rgba(20,220,220,.8)",
    "fill": true
   }
  ]
 }, 
 "options": { "responsive": "true" }
}
-->
</canvas>

---
@title[Cone of Uncertainty]
### Cone of Uncertainty
<canvas data-chart="line">
<!-- 
{
 "data": {
  "labels": ["Sprint 1"," Sprint 2","Sprint 3","Sprint 4","Sprint 5","Sprint 6","Sprint 7","Sprint 8","Sprint 9","Sprint 10"],
  "datasets": [
   {
    "data":[2,4,6,8,10,12,14,16,18,20],
    "label":"High watermark","backgroundColor":"rgba(80,200,120,0.8)",
    "fill": false
   },
   {
    "data":[0,0,0,0,0,0,0,0,0,0,0],
    "label":"Average","backgroundColor":"rgba(120,120,120,0.8)",
    "fill": false
   },
   {
    "data":[-1,-2,-3,-4,-5,-6,-7,-8,-9,-10],
    "label":"Low watermark","backgroundColor":"rgba(255,36,0,0.8)",
    "fill": true
   }
  ]
 }, 
 "options": { "responsive": "true" }
}
-->
</canvas>


---
@title[Epic Burndown chart]
## Epic Burndown chart

<canvas data-chart="line">
<!-- 
{
 "data": {
  "labels": ["Sprint 1","Sprint 2","Sprint 3","Sprint 4","Sprint 5","Sprint 6","Sprint 7","Sprint 8","Sprint 9","Sprint 10"],
  "datasets": [
   {
    "data":[307,247,194,147,108,75,48,26,11,2],
    "label":"Story points remaining","backgroundColor":"rgba(20,220,220,.8)",
    "fill": true
   }
  ]
 }, 
 "options": { "responsive": "true" }
}
-->
</canvas>

---
@title[Value based velocity]
### Value based velocity
<canvas data-chart="line">
<!-- 
{
 "data": {
  "labels": ["Sprint 0","Sprint 1"," Sprint 2","Sprint 3","Sprint 4","Sprint 5","Sprint 6","Sprint 7","Sprint 8","Sprint 9","Sprint 10"],
  "datasets": [
   {
    "data":[0,8,58,60,61,56,47,30,20,10,5],
    "label":"Epic A","backgroundColor":"rgba(220,120,120,.8)"
   }
  ]
 }, 
 "options": { "responsive": "true" }
}
-->
</canvas>

---
@title[The "iceberg" effect]
### The "iceberg effect"
<canvas data-chart="line">
<!-- 
{
 "data": {
  "labels": ["Sprint 0","Sprint 1"," Sprint 2","Sprint 3","Sprint 4","Sprint 5","Sprint 6","Sprint 7","Sprint 8","Sprint 9","Sprint 10"],
  "datasets": [
   {
    "data":[0, 8,58,60,61,56,47,30,20,10, 5],
    "label":"Epic A","backgroundColor":"rgba(220,120,120,.8)"
   },
   {
    "data":[0,59,61,60,61,58,59,60,58,60,59],
    "label":"Story points","backgroundColor":"rgba(20,220,220,.8)"
   }
  ]
 }, 
 "options": { "responsive": "true" }
}
-->
</canvas>

---
@title[Rolling Epics]
### Rolling Epics
<canvas data-chart="line">
<!-- 
{
 "data": {
  "labels": ["Sprint 0","Sprint 1"," Sprint 2","Sprint 3","Sprint 4","Sprint 5","Sprint 6","Sprint 7","Sprint 8","Sprint 9","Sprint 10"],
  "datasets": [
   {
    "data":[0, 0, 0, 0, 0, 0, 8,57,58,60,59],
    "label":"Epic B","backgroundColor":"rgba(220,120,120,.8)"
   },
   {
    "data":[0, 8,58,60,61,56,47, 3, 0, 0, 0],
    "label":"Epic A","backgroundColor":"rgba(120,120,120,.8)"
   },
   {
    "data":[0,59,61,60,61,58,59,60,58,60,59],
    "label":"Story points","backgroundColor":"rgba(20,220,220,.8)"
   }
  ]
 }, 
 "options": { "responsive": "true" }
}
-->
</canvas>

---
@title[Scrum Events]
@snap[north-west]
## Scrum Events
@snapend

@snap[west span-55]
@ul[spaced text]
- Sprint Planning
- Daily Stand-up
- Sprint Review
- Retrospective
- *Backlog Refinement*
@ulend
@snapend

---
@title[Scrum Event Schedule]
@snap[north-west span-120]
<table>
  <tr>
    <th>Event</th>
    <th>Occurs</th>
    <th>Duration</th>
  </tr>
  <tr>
    <td>Sprint Planning</td>
    <td>At the start of a Sprint</td>
    <td>2-4 hours *</td>
  </tr>
  <tr class="fragment">
    <td>Daily Stand-up</td>
    <td>Every day</td>
    <td>15 minutes</td>
  </tr>
  <tr class="fragment">
    <td>Sprint Review</td>
    <td>At the end of each Sprint</td>
    <td>1-2 hours *</td>
  </tr>
  <tr class="fragment">
    <td>Team Retrospective</td>
    <td>At the end of each Sprint *</td>
    <td>1-2 hours *</td>
  </tr>
</table>
@snapend

@snap[south span-100 fragment]
@size[0.5em](* Based on a two-week Sprint. Note: your mileage may vary!)
@snapend

---
@title[Sprint Planning event]
@snap[north-west span-120]
<table>
  <tr>
    <th>Event</th>
    <th>Occurs</th>
    <th>Duration</th>
  </tr>
  <tr>
    <td>Sprint Planning</td>
    <td>At the start of a Sprint</td>
    <td>2-4 hours *</td>
  </tr>
 </table>

@snap[west span-55]
Attendees
@ul[spaced text]
- Product Owner
- Scrum Master
- Scrum Team
@ulend
@snapend

---
@title[Daily Stand-up event]
@snap[north-west span-120]
<table>
  <tr>
    <th>Event</th>
    <th>Occurs</th>
    <th>Duration</th>
  </tr>
  <tr>
    <td>Daily Stand-up</td>
    <td>Every day</td>
    <td>15 minutes *</td>
  </tr>
 </table>

@snap[west span-55]
Attendees
@ul[spaced text]
- Scrum Team
- *Scrum Master (optional)*
@ulend
@snapend

---
@title[Sprint Review event]
@snap[north-west span-120]
<table>
  <tr>
    <th>Event</th>
    <th>Occurs</th>
    <th>Duration</th>
  </tr>
  <tr>
    <td>Sprint Review</td>
    <td>At the end of the Sprint</td>
    <td>1-2 hours</td>
  </tr>
 </table>

@snap[west span-55]
Attendees
@ul[spaced text]
- Stakeholders
- Product Owner
- Scrum Team
- Scrum Master
@ulend
@snapend

---
@title[Team Retrospective event]
@snap[north-west span-120]
<table>
  <tr>
    <th>Event</th>
    <th>Occurs</th>
    <th>Duration</th>
  </tr>
  <tr>
    <td>Team Retrospective</td>
    <td>At the end of the Sprint</td>
    <td>1-2 hours</td>
  </tr>
 </table>

@snap[west span-55]
Attendees
@ul[spaced text]
- Scrum Team
- Scrum Master
@ulend
@snapend

---
@title[Backlog Refinement event]
@snap[north-west span-120]
<table>
  <tr>
    <th>Event</th>
    <th>Occurs</th>
    <th>Duration</th>
  </tr>
  <tr>
    <td>Backlog Refinement</td>
    <td>As required</td>
    <td>As required</td>
  </tr>
 </table>

@snap[west span-55]
Attendees
@ul[spaced text]
- Product Owner
- Scrum Master
- Scrum Team representative(s)
- *Whole Scrum Team (optional)*
@ulend
@snapend
