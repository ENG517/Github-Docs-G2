---
title: Viewing the branch history in GitHub Desktop
intro: 'You can see details about any commit in {% data variables.product.prodname_desktop %}, including a diff of the changes the commit introduced.'
redirect_from:
  - /desktop/contributing-to-projects/viewing-the-branch-history
  - /desktop/contributing-and-collaborating-using-github-desktop/viewing-the-branch-history
  - /desktop/contributing-and-collaborating-using-github-desktop/making-changes-in-a-branch/viewing-the-branch-history
  - /desktop/contributing-and-collaborating-using-github-desktop/making-changes-in-a-branch/viewing-the-branch-history-in-github-desktop
versions:
  feature: desktop
shortTitle: View branch history
---
Each commit provides the following details:

* Commit message
* The time the commit was made
* The committer's username and profile photo (if available)
* The commit's SHA-1 hash (the unique ID)

{% data reusables.desktop.history-tab %}
1. Navigate to the **History** tab, and select the commit you want to review.

   {% mac %}

   Use <kbd>Command</kbd> or <kbd>Shift</kbd> to select multiple consecutive commits. 

   {% endmac %}

   {% windows %}

   Use <kbd>Ctrl</kbd> or <kbd>Shift</kbd>to select multiple consecutive commits

   {% endwindows %}

   ![Screenshot of a list of commits in the "History" tab. Three consecutive selected commits are highlighted in blue and outlined in orange.](/assets/images/help/desktop/branch-history-commit.png)

2. If a commit or a range of commits contains multiple files, click on an individual file to view the changes made to that file.

   ![Screenshot of a commit view. To the right of the "History" tab, in a list of files, the "hello.txt" file is selected and highlighted with an orange outline.](/assets/images/help/desktop/branch-history-file.png)

## Further reading

* "[AUTOTITLE](/desktop/working-with-your-remote-repository-on-github-or-github-enterprise/syncing-your-branch-in-github-desktop)"
