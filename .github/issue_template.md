Here you will describe the issue/feature you want to get fixed/implemented with as much detail as possible. Include screenshots, designs, links or anything that will make the ticket more understandable.

## Notes (optional)

Here you can list any extra information about the ticket, like implementation recomendations for example.

## Tasks

The **Tasks** section contains a achecklist stating what needs to be completed in order to finish the ticket, consider tasks to be as smaller tickets that once solved, will solve the bigger ticket. 

Every ticket should provide an initial tasks list, but developers can modify these if they think something is missing.

Tasks should be agnostic of the developer is working on the ticket, they should provide a clear path for developers to follow, and managers an estimate of completion percentage of the task. Tasks are not a personal To Do list, don't use it this way.

Here's an example:

- [ ] Create initial repository with eslint and pretiter configuration
- [ ] Add deployment script
- [ ] Setup CI integration

## Acceptance criteria

Acceptance criteria is a list stating the definition of ready of the ticket. It should be used by developers and managers to verify if the ticket was implemented correctly and is ready to be closed.

This section is not meant to be edited by anyone excepts managers.

Here's an example:

- When clicking the **Save** button, the UI should look with showing a spinner until the save completes.
- If the **Save** timeouts, we will show an error alert with the text **We couldn't save your record, please try again**.