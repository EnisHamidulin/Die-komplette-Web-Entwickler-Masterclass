CHANGELOG.MD

Changelog is a file that logs all the changes made to a specific software program. The reason for creating and keeping a changelog is; when a contributor or end-user wants to see if any changes have been made to a software program.
It will show what, and when, any changes were made between the different versions or releases of the particular software.

Changelogs are Vital for Debugging Software and Error Control

For every type of software project, there will be the initial release (version) and, subsequently, newer and better releases that work smoother because they have been de-bugged.
Changelogs keep track of these changes. They also help to control errors because they document if, and when, those errors were corrected.
The reasoning behind this is simple; when multiple people are working on a software project, the chance that they are aware of any changes becomes slimmer. With a well-written changelog in place, however, anyone who's working on the software can see what changes have been made (or not) so they can move forward from there.

What Steps Should Be Followed to Create a Well Made Changelog?

-Changelogs are made to be read by humans, making legibility vitally important
-It should be easy to link any section and any entry for every software version
-Each version should have 1 subsection only
-All changes that are the same should be grouped together
-Releases / new versions should be listed with newest on top (reverse chronological order)
-Each new version should have its release date displayed
-These dates should follow the ISO standard format YYYY-MM-DD / 2022-01-01
-Always mention whether or not Semantic Versioning has been used.

What Types of Changes Should be Noted and How to Note Them?

-Added - For any new features that have been added since the last version was released
-Changed - To note any changes to the software's existing functionality
-Deprecated - To note any features that were once stable but are no longer and have thus been removed
-Fixed - Any bugs or errors that have been fixed should be so noted
-Removed - This notes any features that have been deleted and removed from the software
-Security - This acts as an invitation to users who want to upgrade and avoid any software vulnerabilities

How should a Changelog File be Named?

- CHANGELOG.md

Should a Changelog Ever be Rewritten?

Yes, when necessary. If, for example, a change, fix, deprecation or addition was missed then, by all means, rewrite the changelog to show these changes. The whole purpose of a changelog is to note all of the most important software changes. A missing change would thus make the changelog less valuable.

Should Yanked Releases Be Included in the Changelog?

Yes, definitely. Since yanked releases are versions of the software with significant bug and error issues they should always be noted. Although again not standardized this is a good example of how to display a yanked version. ## 0.0.5 - 2014-12-13 [YANKED]
