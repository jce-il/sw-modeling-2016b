##General
Generally, work in this course is done in pairs and submitted through github, (we ask to switch team for every assignment).

If you prefer that your solution will not be publicly visible [request private repositories][private-repos].


##Submissions Instructions
1. To start, [**fork**][forking] the rellevant excercise repository (not this one).
1. [**Clone**][ref-clone] the repository to your computer (for later updates: first add a [remote][config-remote] to the upstream repo and [sync][sync-remote] with a [pull][ref-pull]:  ```git pull upstream master```).
1. Modify/add files and [**commit**][ref-commit] changes to complete your solution.
1. [**Push**][ref-push]/sync the changes up to GitHub.
1. [Create a **pull request**][pull-request] on the original repository to turn in the assignment.
  - Add your excercise mates ass collaborators and also tag them in the PR message so they can participate in the discussion.

Pull request screencast [demo](http://screencast-o-matic.com/watch/coe3IEeMDa)

## Homework1: [Git immersion](https://github.com/jce-il/git-immersion)
To complete building our git mental **model** in the course, we will complete the git-immerssion workshop by [Jim Weirich](https://github.com/jimweirich). 

**Important**: this time it is a personal submission.

**Submission date**: 3 weeks

## Homework2 [UML/OCL](https://github.com/jce-il/sw-modeling-2016b-uml)

Modeling an online store (Amazon like), through:

1. Usecase analysis, with: 
  - Actors and stakeholder table
  - One use-case diagram
  - One detailed written use case
1. Four diagrams: Sequence, Class, Activity, Component|Deployment
  - Each diagram should be accompanied by a section discussing the design and especially the **unique** design considerations embodied in the diagram.
1. OCL: One diagram with constrains (see CAR example in lecture slides)

The models should be simple but not too simplistic! Using some non trivial UML constructs.

- Format: Each part has a separte markdown page including XMI files and image files

- Submission by a pull request, please add your mates in the PR comments
- **Submission dates**: 3 parts, each successive weeks, by pull request

## Homework3 Architecture Views & Prespetive (TBD)    

Possible alternative: right a review for a project stage of another project team.

**Submission date**: TBD

## Final Project - Class Project: Azrieli Students On Software Modeling and Arcchitecture - ASOSMA Book (draft)

We will develop the book in agile iterations of an about 2-week sprints (you can suggest your own schedule). In each iteration you will continue developing sections of a book chapter describing the modling of an open source project you selected.

Each iteration will be submitted by a pull request to the book repository and evaluated and graded. Discuss progress and issues alreaady during class time or on chat.

Grades are according to how much your work is: relevant (to the course), interesting & deep, presented well (written and oral), on time, etc. Might add individual grade variation according to activity and final presentation.

### Stage 0 - Project Selection and Introduction
- Form into a team of ~4 students (choose wisely)
- Select a known open source project
  - The project should be: interesting to you, big & complex enough, actively developed (>50 PRs in last year), has an automated test suite (use of engineering practices), used by someone (something on stake), and seem to miss documenation.
  - Here are some sources for ideas and inspiration: [leading github projects](https://github.com/showcases), Book: [The Architecture of Open Source Applications](http://www.aosabook.org/en/index.html), Local: [Hasadna](http://www.hasadna.org.il/projects/) (The Public Knowledge Workshop), [Last year's projects][last-year-proejcts], Below a starting list of suggestions.
- Fork the book repo and add a markdown page for your chapter (decides whether to collaborate through a shared (private?) team repository or by PRs), add:
  - Project name, repository and your team members (send a PR for that ASAP to reserve your subject)
  - Issue tracking system to coordinate your work and report effort and progress
- See a similiar book project example [here][Desosa-book].

### Stage 1 - Introducion
- Start your  introduction section, including
  - General details about the project (homepage, repository, team, communications)
  - project fit for our book (why it was chosen)
  - Describe the model of the development process
  - Review resources, especially concerning modeling and architecture  (repos, papers, posts, issues/bugs)
  - Add a few images or diagrams to support the above

### Stage 2 - Views and Prespectives
- Fork the project's repository and consider adding a documentation folder
- Describe the given documentation and/or source code
- Analyze and describe the main requirements/features of the product (stakeholder view)
- Analyze and describe the major or important designs with UML diagrams and or other modeling means (e.g. sketeches (Calico), views, C4)
- Describe a few challenges for this project (e.g., a missing feature, known bugs)
- Try to validate your analysis with the project team

### Stage 3 - Metrics, Variability and Quality Measures
- Describe how the project is copying with the pace of change commonly expected from software, e.g. testing, maintianability, and other means.
- Describe the applicability of a design metric tool (e.g. code climate) to the project code.
- Describe how at least 2 qualities are handled, especially, avalability and security (if not a service define other)

### Stage 4 - Presentation, Feedback and Finizlize
- Team presentation of your work in one of the 2 last lectures (~15 min. +10 min. Q&A), if you prepare slides or clips add them to the documentation or book.
- You are encourage to contribute back the modeling documentation or other help.
- Describe your interacion and contribution to the project (documentation, fixing or reporting bugs/ open issues, improve process etc.)
- Finish your book chapter, including a summary section discussing what you've learned from the course and the book project, how modeling contributed to your work (or how it got in the way..) and how you spent your time (an important hab)

The book will be avaialbe on github with a common creative with attribution license.

### Project Suggestion
| # | Project | Domain  | Remarks|
|---|---------|---------|--------|
|   | [Jasmine] | Testing | [JasminePRs] | 
|   | | | | |


<!-- Links -->
[private-repos]: /guide/private_repos
[help-add-to-team]: https://help.github.com/articles/adding-organization-members-to-a-team
[forking]: https://guides.github.com/activities/forking/
[ref-clone]: http://gitref.org/creating/#clone
[ref-commit]: http://gitref.org/basic/#commit
[ref-push]: http://gitref.org/remotes/#push
[ref-pull]: http://gitref.org/remotes/#pull
[pull-request]: https://help.github.com/articles/creating-a-pull-request
[config-remote]: https://help.github.com/articles/configuring-a-remote-for-a-fork/
[sync-remote]: https://help.github.com/articles/syncing-a-fork/

[Desosa-book]: http://delftswa.github.io/
[last-year-proejcts]: https://github.com/jce-il/sw-modeling-class/blob/master/Projects.md
[Jasmine]: http://jasmine.github.io/
[Jasmine-PRs]: https://github.com/jasmine/jasmine/pulls?utf8=%E2%9C%93&q=is%3Apr+created%3A%3E2015-04-01+