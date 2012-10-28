salt-top
========

Salt Top is a top-style program designed for salted environments. It requires 
Salt to be installed, is designed to run on the salt-master.

At the moment, it is very much in development mode. The following keys are
supported; whether they work is a different story:

code ::

    <space> - Refresh the data
    m       - Display minion-based report
    j       - Display job-based report
    q       - Quit

The short-term plan is to allow users to write their own minion-based reports,
to be included in an /etc/salt/top config file.

