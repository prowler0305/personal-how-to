# Stashing/Shelving Changes

A commit saves your changes permanently in the repository. However in your day to day work there are a lot of scenarios in which you only want to save your local changes temporarily.

For example, say your in the middle of changes related to a feature when an severe bug is reported. You obviously don't want to include your feature related changes along with the bugfix you're going to make. You want to get rid of those changes temporarily, make the bug fix, and then continue them later.

This kind of scenario happens all the time, you have local changes in your working copy that you can't commit at the moment and you want or need to start working on something else. So a way to get your working directory clean is to do a **Stash** or **Shelve** of the changes.

There is not a major difference between **stash** and **shelve**, functionally **shelving** is the term used within an IDE like IntelliJ which operates almost exactly like git **stashing**

To shelve changes in IntelliJ see their [documentation](https://www.jetbrains.com/help/idea/shelving-and-unshelving-changes.html)