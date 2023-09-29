## Contributing
* use 2 character indents where the language standards don't dictate anything
* Follow conventions for the given language you're writing in. For example, PEP for python, which mean (but not limited to):
  * 4 space indents (IDEs can usually be configured to make tabs use spaces)
  * global variables and constants in all capitals
  * global variables and constants declared at the beginning of the file wherever possible
  * local variables in all lowercase
  * variable and function naming to use snake_case
* make use of functional style of programming unless there is a strong reason not to, and if there is a good reason, it must be documented along with the code
* hard-coded values should be avoided unless there is a good reason (I.e. for security)
* tests should be in a directory named `tests`
* install a suitable IDE formatting plugin and run it before pushing changes. I.e. On Jetbrains IDEs
 there is Shell Script Formatter which should have be ran (with CTRL+ALT+L or CMD+OPT+L) on each
 script
* PR Authors needs to ensure the reviewer has everything needed to review. I.e.
  * description of the changes
  * in-line comments of complex algorithms
  * description of how to test
    * strategic testing documented on README or wiki
    * tactical testing documented on PR
  * Don't submit huge PRs. Break it up, if necessary. If large changes need to merge to a release branch together, create a new temporary base branch first and create small PRs into that one first
  * Don't submit PRs with large format changes (i.e. automated corrections by an IDE) along with functional changes because it makes the PR diff hard to understand. Submit the formatting on a separate PR.
* Reviewers should be
  * checking IDE plugin validations
  * asking in-line questions
  * flagging convoluted code without descriptions or in-line comments
 
Feel free to ask any questions in issues or email [support@mesoform.com](mailto:support@mesoform.com).

### Code of Conduct

Mesoform officially incorporates the [Mozilla Community Participation Guidelines](https://www.mozilla.org/en-US/about/governance/policies/participation/) as its Code of Conduct with the exception that the reporting email address is changed to [support@mesoform.com](mailto:support@mesoform.com).
