# New Feature: Claims History

## Requirements

Design a *Claims History* feature for the app.  Design it according to the
following requirements:

1.  All operations on the Claims table will be recorded in the Claims History.

1.  Users will be able to review their Claims History.

1.  A daily cron job will trim the Claims History table: operations older than
    _D_ days will be deleted, unless they are within the _N_ most recent
    operations.  _D_ and _N_ will be configurabe by Admin users; the defaults
    will be _D_ = 90 and _N_ = 1000.

1.  In a later phase, the Claims History will be used by Users to undo their
    operations, but that is out of scope for now.

1.  The User Guide and developer documentation should be updated to document
    this feature.

## Deliverables

The deliverable for this task is:

1.  **An Implementation Document**  
    This implementation document should be suitable for other AI agents to
    follow.  It should have well-defined, clear steps that the agents should
    mark as complete once they have implemented that step.

