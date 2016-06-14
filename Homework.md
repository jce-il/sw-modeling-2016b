##General
Generally, work in this course is done in pairs and submitted through github, (we ask to switch team for every assignment).

If you prefer that your solution will not be publicly visible [request private repositories][private-repos].


##Submissions Instructions
1. To start, [**fork**][forking] the rellevant excercise repository (not this one), add your team as collabotators (so they get notified for repository activity).
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

Possible alternative/addition: write a review for a project stage of another project team.

**Submission date**: TBD

## Final Class Project
### Azrieli Students On Software Modeling and Architecture - [ASOSMA] Book ([Deployed version]) (draft)

We will develop the book in agile iterations of an about 2-week sprints (Default schedule appears on course main README page). In each iteration the team will continue developing sections of a book chapter describing the modling of an open source project you selected.

Each iteration will be submitted by a pull request to the book repository and then evaluated and graded. It is recommended to discuss progress and issues alreaady during class time or on chat.

Grades are according to how much your work is: relevant (to the course), interesting & deep, presented well (written and oral), on time, etc. We might add an individual grade variation according to activity and final presentation.

### Stage 0 - Project Selection and Introduction
- Form into a team of ~4 students (choose wisely)
- Select a known open source project
  - Constrains: the project should be: interesting to you, big & complex enough, actively developed on github (>100 PRs in last year), has an automated test suite (use of updated engineering practices), used by someone (something on stake), a whole product might suit as better than a mere library, and seem to miss documenation.
  - Here are some sources for ideas and inspiration: [leading github projects](https://github.com/showcases), Book: [The Architecture of Open Source Applications](http://www.aosabook.org/en/index.html), Local: [Hasadna](http://www.hasadna.org.il/projects/) (The Public Knowledge Workshop), [Last year's projects][last-year-proejcts], Below a starting list of [suggestions](./#project-suggestions).
- Fork the [ASOSMA] book repo and add a folder with a README.md page for your chapter and link it also from the main book README page (decides whether to collaborate through a shared (private?) team repository or by PRs), add:
  - Project name, original project repository and your team members (linked usernames), send a PR for that ASAP to reserve your subject.
  - Setup an issue tracking system to coordinate your work and report effort and progress (repository settings -> mark the issues for operating it). It is required upon  closing an issue to add you actual effort).
        - Plan your overall project by adding dated milestones according to the course plan and your preferences.
        - Start planning next iteration work.
  - See also a similiar book project example [here][Desosa-book].

### Stage 1 - Introducion
- Start your introduction section, including:
  - General details about the project (homepage, repository, development team, communications)
  - project fit for our book (why it was chosen?).
  - Describe the model of the development process.
  - Review availaibe resources, especially concerning modeling and architecture  (repos, papers, posts, issues/bugs).
  - Add a few images or diagrams to support the above.

### Stage 2 - Views and Prespectives
- Fork the project's repository and add a documentation folder (consider developing it, e.g., according to this [branching model], or the one required by the projcet's development process).
  - add a link to your fork to the introduction section.
- Describe the given documentation and general source code structure.
- Analyze and describe the main requirements/features of the product (stakeholder view).
- Analyze and describe the major or important designs with UML diagrams and or other modeling means (e.g. sketeches (Calico), views, [C4][structurizr]).
- Describe a few challenges for this project (e.g., a missing important feature, known bugs).
- Try to validate your analysis with the project team and report about it.

### Stage 3 - Metrics, Variability and Quality Measures
- Describe how the project is coping with the pace of change commonly expected from software, e.g. testing, maintianability, and other means.
- Describe the applicability of a design metric tool (e.g. code climate) to the project code.
- Describe how at least 2 qualities are handled, especially, availability and security (if the product is not a service define others)

### Stage 4 - Presentation, Feedback and Finizlize
- Present your work in one of the 2 last lectures (~15 min. +10 min. Q&A), if you prepare slides or clips add them to the documentation and/or book.
- You are encourage to contribute back the modeling documentation or other help.
- Describe your interacion and contribution to the project (documentation, fixing or reporting bugs/ open issues, improve development process and even the chapter you wrote).
- Finish your book chapter, including a summary section discussing what you've learned from the course and the book project, how modeling contributed to your work (or how it got in the way..) and how you spent your time (an important habbit).

The book will be avaialbe on github with a common creative with attribution license.

### Project Suggestion
| # | Project | Domain  | Remarks|
|---|---------|---------|--------|
| 1 | [Jasmine] | Testing | [JasminePRs] | 
| 2 | [Anyway]  | Open Knowlwdge, Local| [AnywayPRS] |
| 3 | [libgdx]  | Java Game Engine | [libgdxPRs] |
| 4 | [bolt]    | CMS with PHP | [boltPRs] |



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

[ASOSMA]: https://github.com/jce-il/ASOSMA
[Deployed version]: http://jce-il.github.io/ASOSMA/README.html
[Desosa-book]: http://delftswa.github.io/
[branching model]: http://nvie.com/posts/a-successful-git-branching-model/
[last-year-proejcts]: https://github.com/jce-il/sw-modeling-class/blob/master/Projects.md
[structurizr]: https://structurizr.com/

[Jasmine]: https://github.com/jasmine/jasmine
[JasminePRs]: https://github.com/jasmine/jasmine/pulls?utf8=%E2%9C%93&q=is%3Apr+created%3A%3E2015-04-01+

[Anyway]: https://github.com/hasadna/anyway
[AnywayPRS]: https://github.com/hasadna/anyway/pulls?utf8=%E2%9C%93&q=is%3Apr+created%3A%3E2015-04-01+

[libgdx]: https://github.com/libgdx/libgdx
[libgdxPRs]: https://github.com/libgdx/libgdx/pulls?utf8=%E2%9C%93&q=is%3Apr+created%3A%3E2015-04-01+

[bolt]: https://github.com/bolt/bolt
[boltPRs]:https://github.com/bolt/bolt/pulls?utf8=%E2%9C%93&q=is%3Apr+created%3A%3E2015-04-01+
