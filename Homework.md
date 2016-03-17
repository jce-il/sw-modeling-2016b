##General
Generally, work in this course is done in pairs and submitted through github, you must switch team for every assignment.

If you prefer that your solution will not be publicly visible [request private repositories][private-repos].


##Submissions Instructions
1. To start, [**fork** the excercise repository][forking].
1. [**Clone**][ref-clone] the repository to your computer (for later updates: first add a [remote][config-remote] to the upstream repo and [sync][sync-remote] with a [pull][ref-pull]:  ```git pull upstream master```).
1. Modify/add files (in the hw directory) and [**commit**][ref-commit] changes to complete your solution.
1. [**Push**][ref-push]/sync the changes up to GitHub.
1. [Create a **pull request**][pull-request] on the original repository to turn in the assignment.

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
1. OCL: One diagram with constrains (see CAR example in lecture slides)

The models should be simple but not too simplistic! Using some non trivial UML constructs.

- Format: Each part has a separte markdown page including XMI files and image files

- Submission by a pull request, please add your mates in the PR comments
- **Submission dates**: 3 parts, each successive weeks, by pull request

## Homework3 DDD/CQRS/EventSourcing Workshop (maybe)    
1. Fork the workshop repository https://github.com/jce-il/mixter
1. Clone to your machine
1. Follow the workshop instuctions according to the Readme and included [slides](https://github.com/jce-il/mixter/blob/Slide/slide.pdf), at least the 3 first steps
1. Don't forget to commit (with a meaningful message) and tag each sub-step in a similiar manner to the existing tagging system, e.g., 
    - ```git commit -a -m "messageDeleted event published"```
    - ```git tag csharp-my-solution-1.1```
1. If needed you can also reset to a beginning of another stage, e.g., ```git checkout -b origin\csharp-workshop-step-2 csharp-workshop-step-2```
1. Push your results, incl. tags, e.g., ```git push origin csharp-solution; git push origin --tags```
1. Submit by opening a pull request for the working branch (& also mention your peer)

**Submission date**: Last lecture

## Final Project (draft)

Grades are according to how much your work is: deep, relevant (to the course), presented well (written and oral), on time

### Stage 1
- Select a known open source project (git is already captured for class demo)
  - Here are some sources for ideas: [leading github projects](https://github.com/showcases), Book: [The Architecture of Open Source Applications](http://www.aosabook.org/en/index.html), [Hasadna](http://www.hasadna.org.il/projects/) (The Public Knowledge Workshop),...
  - Cloud related ideas and papers from the source course we use: https://courses.engr.illinois.edu/cs525/sp2015/sched.htm 
- selcet a criteria for project fit (from the list discussed at class)
- Review resources (repos, papers, posts, issues/bugs)
- Open a repo for your project and link from the [project](Projects.md) list on the course wiki (by PR of course)
- (the lecturer will discuss the suggestion with you)

**Submission date**: ~~14/5~~

### Stage 2
- Describe the main requirements/features of the product
- Describe the given documentation and/or source code
- Describe the major or important designs with UML diagrams and or other modeling means
- Describe a few challenges for this project (e.g., a missing feature, known bugs)
- Register to talk about it at class (again by setting a date on the project list)

You can submit this stage as a presentation or draft paper

**Submission date**: ~~28/5~~

### Stage 3
- Add your presentation to the projects page 
- Present!

### Stage 4

- Summarise the project in a class book chapter, in particular a section about how modeling contributed to your work (or how it got in the way..)
**Submission date**: ~~Last day of semester~~ but drafts needed in advance


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
