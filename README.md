### Git Merge: Preserving History

* **The Action:** Fuses two branches together by creating a brand-new "merge commit."
* **The History:** Preserves the exact historical truth of your project, explicitly showing when a branch split off and when it returned.
* **The Layout:** Can result in a cluttered, multi-lined "spaghetti" commit graph if many developers are merging at once.

### Git Rebase: Cleaning the Timeline

* **The Action:** Lifts your branch and moves its starting point to the absolute tip of the target branch.
* **The History:** Rewrites the project history to make it look like your changes were written in a perfectly straight, sequential line.
* **The Layout:** Keeps the commit log clean and perfectly linear, though it can disrupt other developers if you rewrite history on a shared public branch.
