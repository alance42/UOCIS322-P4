# UOCIS322 - Project 4 #

Project: An ACP Brevet Randonneurs control brevets calculator implemented with Flask and AJAX

Author: Avi Lance

Contact: alance@uoregon.edu

# Users #

If the Control Distance is greater than 120% of the Brevet Distance, it will return the given starting date with no change in the open and close time column.

If the Control Distance is greater than the Brevet Distance's i.e. (200, 300, 400, 600, 1000) and within 120% of the Brevet Distance, it will return the same starting and closing time you would have if you had a control distance equal to that competitions Brevet Distance.

If the Control Distance is negative, it will return the given starting date with no change in the open and close time column.

If the Control Distance is equal to 0, then the opening time will remain unchanged, while the closing time will be 1 hour past the starting time.

If the Control Distance is less than 60 and greater than 0, the closing time will use 20 km/hr with an additional hour added ontop of the calculation. 

If the Control Distance is equal to the Brevet Distance, the speed will be calculated based on the lower Control's speed.

# Developers #

In order to run tests, execute run_tests.sh. If you would like to add tests place a new python file starting with the name "test" in the tests folder.

You can create a new credentials.ini from the credentials-skel.ini. This will allow you to manipulate the port and debug features used by flask_brevets.py.

