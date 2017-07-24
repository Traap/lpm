# lpm - Lightweight Project Management

# Project Management
[Traap's](https://github.com/Traap) repositories use a lightweight project
management system provided by GitHub.

## Project Name and Project Board.
A project board is created with the following columns:
* **Backlog** - Issues that have not been started.
* **In Progress** - Issues that are being worked on. 
* **In Review** - Issues that have are part of a pull request or manual review
  process.
* **Done** - Issues that are done.
* **Pull Request** - Issues that are tagged as a pull request.

## What does Done mean?
lpm uses different done classifications as follows:
* **duplicate** - A reference to one or more duplicate is provided.
* **invalid** - An Issues has been determined to be invalid.  A rationale is given.
* **wontfix** - An Issues will not be fixed and a rationale is given.

## Milestones Equate to Sprints.
lpm uses GitHub milestones as a Sprint.  Projects uses 5-day sprints. Sprints
names use the following naming convention: 
Sprint vM.N.S, where
* **M** - the major Release number starting with 1.
* **N** - the minor Release number starting with 0.
* **S** - the Sprint number starting with 0.

As an example, three consecutive Sprints are declared as follows:
* **Sprint v1.0.0** - Started 2017.02.23 and ended 2017.02.24.
* **Sprint v1.0.1** - Started 2017.02.27 and ended 2017.03.03.
* **Sprint v1.0.2** - Started 2017.03.06 and ended 2017.03.10.

## Labels
lpm uses labels as follows:
* **bug** - is an Issues that did not meet the intent of the Story.
* **duplicate** - is an Issues that duplicates another issue regardless of the
  Issues label.  A rationale is given for duplicate Issues.
* **enhancement** - the Agile Story format
```
    As a <type of user> I want <some goal> so that <some reason>.
```
* **help wanted** - is most often used as a secondary tag to ask for help
  determining the direction an Issues should take.
* **invalid** - is an issue that is invalid.  A rationale is given for invalid
  Issues.
* **pull request** - is used to label a pull request.
* **question** - is most often used as a secondary tag to ask another person
  a question and to track the answer to closure.
* **wontfix** - this Issues will not be fixed.  A rationale is given for Issues
  that are not fixed.

## Releases
lpm consist of one or more milestones.  Release names use the following naming
convention: vM.N.P name, where
* **M** - the major Release number starting with 1.
* **N** - the minor Release number starting with 0.
* **P** - the patch Release number starting with 0.
* **name** - a descriptive name for the release.
