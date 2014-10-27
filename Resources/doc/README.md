JobQueueWidgetBundle
=====================
This document contains information on how to download, install "JobQueueWidgetBundle" package.


Table of content
-----------------

- [Requirements](#requirements)
- [Installation](#installation)
- [Features](#features)

Requirements
------------

JobQueueWidgetBundle requires OroPlatform(BAP) and PHP 5.4.4 or above.

Installation
------------

Package is available through Oro Package Manager.
For development purposes it might be cloned from github repository directly.

```
git clone https://github.com/24198/JobQueueWidgetBundle.git
```

after installing the Package or cloning this into your development environment
you need to run the command 
```bash
    php app/console app/console oro:assets:install
```

this will install the appropriate images for displaying in the frontend.


Features
------------

This widget will display the jobqueue grid on a dashboard widget. The widget will
display a datagrid with the last 10 jobs in the queue. In this widget you will see:
  - The channel name;
  - The channel type;
  - The job state (i.e. running, pending etc..);
  - The creation date
