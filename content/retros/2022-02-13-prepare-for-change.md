---
title: Prepare for Change
date: 2022-02-13
---
> This is the part where the hero is confronted with challenges by his enemies. This is a time of trial and tribulations. The hero must decide who to trust in the wake of great obstacles and threats, testing his abilities to the bitter end. 

## Got done during milestone
- Stats
  - 16 issues done
  - 40 hours time spent
- Refactored the grading system to something workable
  - 🐞 3 different grade categories
  - 🐞 Endpoint for setting grades
  - 🐞 User grades are added whenever...
    - 🐞 a category is added to grading system
    - 🐞 a new project is added
  - 🐞 When updating a grade, it's parents are also updated if they are dependent on children
- 🐞 Started getting data from gitlab
- 🐝 Button for adding new group
- 🐝 Grading radar view
- 🐝 Learnt about vue
- 🐝 Grading system tree
- Bugfixes
  - 🐞 CI runs migrate command
  - 🐞 CI no longer destroys database
  - 🐞 API endpoints consistently end in slashes
  - 🐞 Registration endpoint checks if passwords match
  - 🐝 Auto refresh jwt token when expired
  - 🐝 nginx no longer gives 404 on page refresh


## Chat with Ago 🐢
- Ago "munes" and was late to the meeting
- Ago suggested to do a standup on friday to discuss our Task Setting paper, which is due in the next monday
- Ago was not that amused with the graphs and trees as Mart 🐝 would have hoped 
- He wants to have a view where he sees stats on every student
  - I am thinking of a table where, depending of the column you select, a graph changes
- Tests
  - No need to test front yay
  - Maybe test the data agregators in the back
- Ago want something clickable and he wants it fast


## Planned for next milestone
### Thursday deadline
- [ ] Mentors should be able to grade
  - [ ] Kristjan needs to finish getting data from gitlab
  - [ ] Kristjan needs to add some new grade category types
  - [ ] Mart needs to make tree view editable
- [ ] Bugfixes / misc
  - [ ] Loading projects shouldn't create duplicates
  - [ ] System for matching milestones
- [ ] Stretch goals
  - [ ] Dedicated milestone grading view in front
  - [ ] Custom endpoint for dedicated milestone grading view

### Post thursday
- [ ] Project plan or something

## Difficulties
- 🐝 D3 is still hard, unlike some other things
- 🐝🐞 Time pressure is real
- 🐞 Data model is starting to get complex and often takes some time to think about the correct way of doing things

![](/retro6/radarview.gif)
![](/retro6/GradeTree.gif)