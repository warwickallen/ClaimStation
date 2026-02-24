# "Claims History"  Requirements

A new feature is required for the app: *Claims History*.  It should met the
following requirements:

1.  All operations on the Claims table will be recorded in the Claims History.

2.  Users will be able to review their Claims History.

3.  A daily cron job will trim the Claims History table: operations older than
    _D_ days will be deleted, unless they are within the _N_ most recent
    operations.  _D_ and _N_ will be configurabe by Admin users; the defaults
    will be _D_ = 90 and _N_ = 1000.

4.  In a later phase, the Claims History will be used by Users to undo their
    operations, but that is out of scope for now.

5.  The User Guide and developer documentation should be updated to document
    this feature.
