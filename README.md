# RFC NNNN AUTH48
This repository is for managing document updates for RFC NNNN during AUTH48. This is an [experiment of a GitHub-based process for AUTH48](https://www.rfc-editor.org/rpc/wiki/doku.php?id=github_auth48_experiments), and it emulates the [current AUTH48 procedure](https://www.rfc-editor.org/pubprocess/auth48/). 

Please see the [License](https://github.com/rfc-editor/rfcNNNN-AUTH48/blob/main/LICENSE.md). The [IETF Note Well](https://github.com/rfc-editor/rfcNNNN-AUTH48/blob/main/note-well.md) applies.

GitHub features that will be used:
* Issue tracking
* Pull requests
* @mentions

Authors, AD, WG chairs, and document shepherd, please ensure that your GitHub notification settings are set such that you can participate promptly in discussions of issues and pull requests. For more information, please see [Configuring notifications](https://docs.github.com/en/account-and-profile/managing-subscriptions-and-notifications-on-github/setting-up-notifications/configuring-notifications).

(Include the following if file is markdown:) This document is being edited in kramdown-rfc markdown.  Once the content is stable, the markdown will be converted to RFCXML and formatted as an RFC.  Your final approval means you approve both the content and format.

## Issue Tracking
(Include the following if file is markdown:) The initial version of draftstring.md is the same as what was approved for publication. Various [PRs](https://github.com/rfc-editor/repo/pulls) and [issues](https://github.com/rfc-editor/repo/issues) are being added to the repo. The RFC Production Center's additional suggested updates have been added as PRs. Open-ended questions and FYIs have been added as issues. Please approve the PRs or propose alternate updates. For the issues, provide your answers in the comments or add PRs to address them.  We will @ the authors as the issues and PRs are ready for review.

(Include the following if file is RFCXML:) Questions and FYIs from the RFC Editor that are usually sent as an email message at the beginning of the [current AUTH48 procedure](https://www.rfc-editor.org/pubprocess/auth48/) have been added instead as GitHub issues.

Please provide your answers in the comments and use a label to indicate issue status:
* rfced - initial label of RFC Editor questions and FYIs (keep this label if the issue is still active).
* follow-up question - a follow-up question has been added to the issue discussion. Use @mention to identify the participant who should answer. 
* AD approval required - the resolution of the issue requires the AD to review and approve the change.
* rfced-ready - the RFC Editor can update the document and/or close the issue based on the issue discussion.

Feel free to add new issues and PRs for new edits and questions. Use @mention to identify the participant who should answer.

If the RFC Editor creates the PR, the editor expects feedback from at least one reviewer before merging the PR. We expect the other relevant parties will speak up if they disagree with any update.

The RFC Editor will close the issue when it has been addressed either by accepting a pull request or simply closing the issue if no changes are needed.  

## Pull Requests
When AUTH48 starts, the XML file will already include RFC Editor edits. This emulates the starting state of the [current AUTH48 procedure](https://www.rfc-editor.org/pubprocess/auth48/). 

If you would like to submit changes, please create a pull request and identify one or more issues that the pull request closes in the comments. 

If the RFC Editor creates the PR in response to issue comments, the RPC Editor will assign a reviewer for the PR and will expect feedback from the reviewer before merging the PR. 

(Include the following if file is markdown:) Once the content of the .md file is stable, the RPC will create an XML file. The following files will be provided for your review at that time:

* [https://www.rfc-editor.org/authors/rfc9380.html](https://www.rfc-editor.org/authors/rfc9380.html)
* [https://www.rfc-editor.org/authors/rfc9380.pdf](https://www.rfc-editor.org/authors/rfc9380.pdf)
* [https://www.rfc-editor.org/authors/rfc9380.txt](https://www.rfc-editor.org/authors/rfc9380.txt)
* [https://www.rfc-editor.org/authors/rfc9380.xml](https://www.rfc-editor.org/authors/rfc9380.xml)
   
(Include the following if file is RFCXML:) ## Viewing XML Outputs
Output files may be viewed here:
* [https://www.rfc-editor.org/authors/rfcNNNN.txt](https://www.rfc-editor.org/authors/rfcNNNN.txt)
* [https://www.rfc-editor.org/authors/rfcNNNN.html](https://www.rfc-editor.org/authors/rfcNNNN.html)
* [https://www.rfc-editor.org/authors/rfcNNNN.pdf](https://www.rfc-editor.org/authors/rfcNNNN.txt)
   
To create your own output files, use the [IETF Author Tools webservice](https://author-tools.ietf.org/).

If you would like guidance on using xml2rfc locally, please ask the RFC Editor. 

## Viewing Diffs
Diffs via GitHub:
* [XML updates](https://github.com/rfc-editor/rfcNNNN-AUTH48/compare/2714c1c..4db1e9d)
* [All editing updates made before AUTH48](https://github.com/rfc-editor/rfcNNNN-AUTH48/commit/aaaaaaa#diff-bbbbbbb)

More information on using GitHub to view diffs can be found here: [Comparing commits](https://docs.github.com/en/github/committing-changes-to-your-project/viewing-and-comparing-commits/comparing-commits).

Once the XML and output files have been created, the following diff files are available via www.rfc-editor.org:
* [https://www.rfc-editor.org/authors/rfcNNNN-diff.html](https://www.rfc-editor.org/authors/rfcNNNN-diff.html) (all changes since the document entered the RFC Editor Queue)
* [https://www.rfc-editor.org/authors/rfcNNNN-rfcdiff.html](https://www.rfc-editor.org/authors/rfcNNNN-rfcdiff.html) (all changes since the document entered the RFC Editor Queue side by side)

## Approving the Document
(Include the following if file is markdown:) This document is being edited in kramdown-rfc markdown.  Once the content is stable, the markdown wi	ll be converted to RFCXML and formatted as an RFC.  Your final approval means you approve both the content and the format.

To approve your RFC for publication, **please reply to the AUTH48 email** stating that you approve this RFC for publication.  Please use **REPLY ALL**, as all the parties CC’ed on the message need to see your approval.

The details of the AUTH48 status of the document are here: [https://www.rfc-editor.org/auth48/rfcNNNN](https://www.rfc-editor.org/auth48/rfcNNNN)

## About This Repo
Note that this repo is available only during AUTH48. This repo will be archived after the RFC publication announcement is sent. 

## Contacting the RFC Editor
For any questions or concerns, please contact rfc-editor@rfc-editor.org. 
Note that push events will send notification messages to rfc-editor@rfc-editor.org. 

## Reverting to the Email-based AUTH48 Process
If for some reason a participant wants to stop using GitHub and wants to use the [current AUTH48 procedure](https://www.rfc-editor.org/pubprocess/auth48/), this can be accomodated. We have structured the repo and the experimental process to align with the current process and we can transition the AUTH48 from GitHub to email.  
