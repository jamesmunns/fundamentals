# What is Version Control?

# Why is Version Control important?
Version Control is useful for (at least) the following reasons:

* Saving incremental progress
    * This allows you to continually make "save points", which can be critical when something suddenly stops working
* Allows for easier collaboration
    * Reduces the chances for developers to accidentally overwrite changes, or avoid making changes to stable
    * Developers can share changes and ideas much more freely, as compared to e-mailing around .zip files of changes.
* Enables more advanced techniques like peer review and continuous integration
    * ?
* Version Control is the first step towards Traceability, which is the ability to see who changes what, when they changed it, or why
    * Traceability will be mentioned in this book, but is a huge topic by itself.

# How much Version Control is necessary?
I suggest using version control for all projects, large and small. It is extrememly easy to set up a repository, and there is nearly no negative tradeoff. Even simple scripts and configuration files get updated over their lifetime, so they are great candidates for version control

Additionally, I would suggest using a defined workflow, such as the Feature Branch Workflow for everything except for the most basic projects. This is an easy habit to form, and will be useful if or when the project grows in size or in collaborators. Once there are multiple developers, or multiple tasks being worked on in parallel, a workflow like this will become extremely useful.
