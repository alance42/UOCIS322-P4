# UOCIS322 - Project 4 #

Project: An ACP Brevet Randonneurs control brevets calculator implemented with Flask and AJAX

Author: Avi Lance

Contact: alance@uoregon.edu

# Users #

If the Control Distance is greater than the Brevet Distance, it will return the given starting date with no change in the open and close time column.

If the Control Distance is negative or greater than 1000, it will return the given starting date with no change in the open and close time column.

If the Control Distance is equal to 0, then the opening time will remain unchanged, while the closing time will be 1 hour past the starting time as per the non-French algorithm.

# Developers #

In order to run tests, execute run_tests.sh. If you would like to add tests place a new python file starting with the name "test" in the tests folder.

You can create a new credentials.ini from the credentials-skel.ini. This will allow you to manipulate the port and debug features used by flask_brevets.py.

