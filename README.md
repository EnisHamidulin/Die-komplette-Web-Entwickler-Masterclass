## README.md

**What are readme files and why do I need them?**

A readme file usually contains **important information** about the respective system, project or software. To ensure users can find the file straight away, it should ideally be placed in the top directory level.
The file also fulfills different purposes for different users:
* **For end users**, a readme file answers questions about installing, updating or using the software.
* **For your own development work**, a readme file provides two advantages. On the one hand, a readme file written prior to the start of development provides a guideline for implementing the project. On the other hand, it lets you resume work quickly if a project was previously set aside for a prolonged period of time.
*  **For other developers**,  a readme file clarifies the codex and provides key information for further development or use of a system, software or an open-source project. 

**What should a readme file contain?**
Depending on the purpose of a readme file, the following content in particular may be relevant:

* A general description of the system or project
* The project status is important if the project is still in development. Use the file to mention planned changes and the development direction or indicate the completion date of the project.
* The requirements on the development environment for integration
* A guide to installation and use
* A list of technology used and any links to further information related to this technology
* Open-source projects that the developers independently modify or expand should be contained in a section on “desired collaboration” in the readme.md file. How should problems be handled? How should developers advance the changes?
* Known bugs and any bug fixes
* FAQ section with all previously asked questions
* Copyright and licensing information

It’s important to write the readme file so that it is always aimed at the end user. This will resolve most of the questions that potentially arise.

**README.md format and language**
* README.**md** and in **english**

**Examples**
```
# Project name
***
Short description of the project.
```

**Headline**
```
# Headline H1
## Headline H2
### Headline H3
#### Headline H4 
##### Headline H5
###### Headline H6
```
**Table of Contents**
```
## Table of Contents
1. [General Info](#general-info)
2. [Technologies](#technologies)
3. [Installation](#installation)
4. [Collaboration](#collaboration)
5. [FAQs](#faqs)
## CHANGELOG.md
```

**ScreenShots**
```
## General Info
***
Write down general information about your project. It is a good idea to always put a project status in the readme file. This is where you can add it. 
### Screenshot
![Image text](/path/to/the/screenshot.png)
```
**Links**

```
## Technologies
***
A list of technologies used within the project:
* [Technology name](https://example.com): Version 12.3 
* [Technology name](https://example.com): Version 2.34
* [Library name](https://example.com): Version 1234
```

**Code**
```
## Installation
***
A little intro about the installation. 

$ git clone https://example.com
$ cd ../path/to/the/file
$ npm install
$ npm start

Note: To use the application in a special environment use ```lorem ipsum``` to start.
```
**Quote**
```
## Collaboration
***
Provide instructions on how to collaborate with your project.
> Maybe you want to write a quote in this part. 
> Should it encompass several lines?
> This is how you do it.
```




## CHANGELOG.md

Changelog is a file that logs all the changes made to a specific software program. The reason for creating and keeping a changelog is; when a contributor or end-user wants to see if any changes have been made to a software program.
It will show what, and when, any changes were made between the different versions or releases of the particular software.

**Changelogs are Vital for Debugging Software and Error Control**

For every type of software project, there will be the initial release (version) and, subsequently, newer and better releases that work smoother because they have been de-bugged.
Changelogs keep track of these changes. They also help to control errors because they document if, and when, those errors were corrected.
The reasoning behind this is simple; when multiple people are working on a software project, the chance that they are aware of any changes becomes slimmer. With a well-written changelog in place, however, anyone who's working on the software can see what changes have been made (or not) so they can move forward from there.

**What Steps Should Be Followed to Create a Well Made Changelog?**

* Changelogs are made to be read by humans, making legibility vitally important
* It should be easy to link any section and any entry for every software version
* Each version should have 1 subsection only
* All changes that are the same should be grouped together
* Releases / new versions should be listed with newest on top (reverse chronological order)
* Each new version should have its release date displayed
* These dates should follow the ISO standard format YYYY-MM-DD / 2022-01-01
* Always mention whether or not Semantic Versioning has been used.

**What Types of Changes Should be Noted and How to Note Them?**

* Added - For any new features that have been added since the last version was released
* Changed - To note any changes to the software's existing functionality
* Deprecated - To note any features that were once stable but are no longer and have thus been removed
* Fixed - Any bugs or errors that have been fixed should be so noted
* Removed - This notes any features that have been deleted and removed from the software
* Security - This acts as an invitation to users who want to upgrade and avoid any software vulnerabilities

**How should a Changelog File be Named?**

- CHANGELOG.md

**Should a Changelog Ever be Rewritten?**

Yes, when necessary. If, for example, a change, fix, deprecation or addition was missed then, by all means, rewrite the changelog to show these changes. The whole purpose of a changelog is to note all of the most important software changes. A missing change would thus make the changelog less valuable.

**Should Yanked Releases Be Included in the Changelog?**

Yes, definitely. Since yanked releases are versions of the software with significant bug and error issues they should always be noted. Although again not standardized this is a good example of how to display a yanked version. ## 0.0.5 - 2014-12-13 [YANKED]
