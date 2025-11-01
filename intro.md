# GitHub actions:

Event Triggers causes a GitHub Action to run

The "on" attribute specifies the event trigger to be used: 
Example:
 

```yml
# test.yml
name: Example workflow
on:[push]
jobs: 
...
```
Github Actions have 35+ triggers

Examples of common Github Actions that could be triggered:
- Pushes: Trigger an action on any push to the repository
- Pull Requests: Run actions when pull requests are opened, updated or merged.
- Issues: Execute actions based on issue activities, like creation or labeling.
- Scheduled Events: Schedule actions to run at specific times. 
- Manual Triggers: Allow manual triggering of actions through the GitHub UI.



