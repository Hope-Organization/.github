This document defines the checklists for creating and reviewing various types of pull-request (PR).

Also refer to Development, design, and review processes.

Backend pull request checklist
Do the changes meet the intended purpose described in the feature or story?
Do the tests reflect the change in behaviour?
Do the tests describe scenarios that are described in the story or feature?
Do the tests describe common failure or validation scenarios?
Has the API changed? (If yes, refer to the interface change checklist.)
Is the change compatibility breaking? (link to guidance) If yes, refer to the breaking interface change checklist.
Does the change alter or remove existing requests to other modules, or introduce new requests? (If yes, refer to external requests / dependencies checklist.)
Do the automated checks pass (e.g. tests, sonar, lint)?
Does each PR title reference a Jira issue for the correct project (at the beginning of the title)?
Does that issue have a “Fix Version”?
Should the implementation version change (link to guidance)?
Are any of the library dependencies a snapshot or pre-release version?
