JobQueueWidgetBundle
=====================

Changelog:
------------

v0.1.0
------------
  - Added connection between Channels and JMS Jobs
  - Added the channel name to the grid;
  - Added the channel type to the grid;
  - Added the job state (i.e. running, pending etc..) to the grid;
  - Added the creation date to the grid

v0.1.1
------------
  - Fixed minor readability issue

v0.1.2
------------
  - Fixed error on dashboard for Oro version 1.3+;
  - Removed connection between Channels and JMS Jobs [See issue channels ](https://github.com/24198/JobQueueWidgetBundle/issues/2)
  - Added command as an column;
  - Added a view link for fast navigation;
  - Sort the state ASC so failed and canceled jobs will show first
