# Module 5 - Journal Your Learnings - Jeremy Nally

## Learning Style Reflection
* **Preferred Style:** Kinesthetic / Hands-on
* **Observation:** I find that I learn Git commands best by actually typing them into the terminal and seeing the result, rather than just reading about them. The practical exercises of creating conflicts and resolving them helped solidify the concepts of branching and merging more than the textbook descriptions.

## Chapter 10: Project Management with Issues
* **Key Concept:** Issues are not just for bugs; they are for planning.
* **Learnings:**
    * **Tracking:** Issues allow us to track tasks, enhancements, and bugs in one place.
    * **Labels:** Using labels (e.g., `bug`, `enhancement`, `wontfix`) helps filter and prioritize work.
    * **Milestones:** Grouping issues into milestones helps track progress toward a specific deadline or version release.
    * **Closing via Commit:** I learned that I can close an issue automatically by including keywords like `closes #1` in my commit message.

## Chapter 11: Branching Strategies
* **Key Concept:** Never work directly on `main` (or `master`).
* **Learnings:**
    * **Isolation:** Branches create a safe environment to experiment without breaking the production code.
    * **Commands:**
        * `git branch [name]`: Creates a new branch.
        * `git checkout [name]` (or `git switch`): Moves you to that branch.
        * `git branch -d [name]`: Deletes a branch after it is merged.
    * **Workflow:** The standard workflow is to create a branch for every single issue or feature, work on it, and then merge it back.

## Chapter 12: Pull Requests & Collaboration
* **Key Concept:** Code Review is essential for quality control.
* **Learnings:**
    * **The PR Process:** A Pull Request is essentially asking permission to merge your branch into the main codebase.
    * **Visual Diff:** GitHub provides a visual comparison (diff) of the changes, making it easier to spot errors than looking at raw code.
    * **Merge Conflicts:** These happen when two branches modify the same line of a file.  resolving them involves manually choosing which code to keep and removing the conflict markers (`<<<<`, `====`, `>>>>`).
    * **Collaboration:** PRs are where the team discusses the code, suggests changes, and approves the work before it becomes permanent.
