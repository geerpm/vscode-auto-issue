# vscode-auto-issue
(Idea) Auto create/update issues on a repositry(github), if you push code with comments TODO 


## Outline

1. Add comments with "TODO" (maybe magicwords is changable)

   ```js
   // TODO Improve conditions
   if (aaa == false) {
     /** 
      * TODO Add some error handling
      * 
      * ## Markdown
      * 
      * - available
      */
     throw new Error();
   }
   ```

1. Listed TODO in vscode subpane ("Problems" pane or some plugin's pane)
1. Click a "Add a issue" button in selected TODO line.
1. Auto-create a issue.
   - **The comments in source code are left.**
   - After create a issue, "TODO" words swap "ISSUE-{N}" (or append)
1. If the comments is updated, auto updating the issue.

