#git-workflow
##tools to help test git workflows

git-workflow is a library of Bash functions, and a Bash script to create
template scripts. It is effectively a domain-specific language for
experimenting with Git repositories. I created it to help me answer a
StackOverflow question--it let me write a script that created a repository in a
certain state, and thus could recreate that state over and over for experiments
from there. It also provides a way to document a successful workflow.

Some examples of included functions follow:

* work: Creates multiple files with random names. Allows simulation of a user working in one line of bash.
* beBusy: Creates ten commits, each creating five files with work.
