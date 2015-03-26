# robot-testrail
A python script for parsing robot test result and update the test result of TestRail

In robot-framework test case, you have to add CID:n in the Tags field where the n is the CID in testrail.

Example:
The max query count is 100
    [Documentation]    This test case is ....
    [Tags]    CID:1

# Requirement
https://github.com/gurock/testrail-api/tree/master/python/2.x

# Usage
python robot-testrail.py --pid TESTRAIL_PROJECT_ ID--xml ROBOT_RESULT.XML --user ADMIN --pwd ADMIN --testrail http://YOURIP/testrail