---
title: Meeting the Mentor
date: 2022-01-29
---
> This is the part where the hero meets the mentor. Meeting the mentor realizes one’s dreams, where the protagonist might receive an object of great importance, some advice, training, or motivation from his mentor.

## Got done during milestone
- Management and documentation
  - 🐝 Milestones and issues are now on project level, so they are no longer that tied to a specific repo
  - 🐝 Added all the retros that we have done in the past 3 weeks to our Hugo pages
  - 🐝 Added a new label to gitlab: "Abandoned"
- Frontend
  - 🐝 Users can register and login and their session will be remembered by the browser
  - 🐝 Added some of our beautiful designs to frontend, mostly with mock data
  - 🐝 The view that shows a users groups uses actual data from the backend
  - 🐝 Some minor bugfixes
- Backend
  - 🐞 There is a POST endpoint for creating / registering a group (with optional gitlab group id)
  - 🐞 There is a GET endpoint for getting a specific users groups
  - 🐞 Some minor bugfixes

## Chat with Ago 🐢
- Ago seemed to like our progress so far
- Suggestions for UI
  - Collapsable/Expandable views in listing repos
  - Relative comparison with other repos
  - Configurable grading
  - View to get non-active students
  - _Stretch goal: Advanced search filter with custom queries_
    - Alternately we can make an Elasticsearch wizard
- Convinced us to take on a third dev
  - Raud 🐒 joined the team
  - Reluctantly.
- Urged us to follow best practices when writing and documenting code

## Planned for next milestone
- Management and documentation
  - 🐝🐞 Make project plan and submit to Moodle
  - 🐝 Rebrand our project to "Cognate"
- Frontend
  - 🐝 Look at the [D3](https://d3js.org) JavaScript library
  - 🐝 Dockerize
  - 🐝 Allow group owner to define grading criteria for groups
  - 🐝 Some minor bugfixes
- Backend
  - 🐞 Add CI/CD process
  - 🐞 Check what info is needed for [automatic project management analysis](https://gitlab.cs.ttu.ee/gitlab-hub/gitlab-hub/-/issues/39)
  - 🐞 Update data model to support that (should be a part of the grading system in some way)
  - 🐞 Make scripts for getting that info from gitlab
  - 🐞 Make endpoints for getting grading criteria from frontend
  - 🐞 Make endpoints for giving analyzed data back to frontend
  - 🐞 Some minor bugfixes

## Difficulties
- 🐝 [D3](https://d3js.org) turned out to be more difficult to learn than expected
- 🐞 The data model that was created turned out to need more additional improvements than initially planned

![](/retro4/mentor.webp)
