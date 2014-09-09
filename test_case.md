# Test Cases
#### Edward Misback and Robbie McKinstry

IDENTIFIER: FUN-JOB-CLASS 
TEST CASE: 1
PRECONDITIONS: Load the webpage http://www.thinkthroughmath.com/request-a-demo/.
INPUT VALUES: n/a
EXECUTION STEPS: 
  1. Locate the 'What best describes you?' dropdown.
  2. Select the dropdown.
  2. Assert that all options are job titles.
OUTPUT VALUES: n/a
POSTCONDITIONS: No assertion failed, and no errors were thrown during execution.

IDENTIFIER: FUN-EX-TEXT
TEST CASE: 2
PRECONDITIONS: Load the webpage http://www.thinkthroughmath.com/request-a-demo/.
INPUT VALUES: n/a
EXECUTION STEPS:
  1. Locate all input elements requiring regular expressions.
  2. Assert that all located input elements provide example content/hint text.
OUTPUT VALUES: n/a
POSTCONDITIONS: No assertion failed, and no errors were thrown during execution.

IDENTIFIER: FUN-COMM-FIELD 
TEST CASE: 3
PRECONDITIONS: Load the webpage http://www.thinkthroughmath.com/request-a-demo/.
INPUT VALUES: n/a
EXECUTION STEPS:
  1. Locate the comments field.
  2. Enter multiline text into the text area.
  3. Assert that the text was entered successfully.
OUTPUT VALUES: n/a
POSTCONDITIONS: No assertion failed, and no errors were thrown during execution.

IDENTIFIER: FUN-NAV-BAR
TEST CASE: 4
PRECONDITIONS: Load the webpage http://www.thinkthroughmath.com/request-a-demo/.
INPUT VALUES: n/a
EXECUTION STEPS:
  1. Locate the navigation bar.
  2. Assert that each link on the bar is valid (returns a 200 status) and 
     is internal to http://www.thinkthroughmath.com.
OUTPUT VALUES: n/a
POSTCONDITIONS: No assertion failed, and no errors were thrown during execution.

IDENTIFIER: FUN-NEC-FIELD
TEST CASE: 5
PRECONDITIONS:
INPUT VALUES:
EXECUTION STEPS:
OUTPUT VALUES:
POSTCONDITIONS: No assertion failed, and no errors were thrown during execution.

IDENTIFIER: NFUN-XSS
TEST CASE: 6
PRECONDITIONS: Load the webpage http://www.thinkthroughmath.com/request-a-demo/.
INPUT VALUES: N/A
EXECUTION STEPS:    
    1. Insert `<script>alert('Panic!')</script>` into a the email input field.
    2. Complete the rest of the form approperately.
    3. Submit the form.
    4. Assert no popup appears.
OUTPUT VALUES:
POSTCONDITIONS:
POSTCONDITIONS: No assertion failed, and no errors were thrown during execution.

IDENTIFIER: NFUN-LITTLE-BOBBY-TABLES
TEST CASE: 7
PRECONDITIONS: Load the webpage http://www.thinkthroughmath.com/request-a-demo/.
INPUT VALUES:
EXECUTION STEPS:
    1. Insert `"); DROP TABLE *;` into the email input field.
    2. Complete the rest of the form approperately.
    3. Submit the form.
    4. Assert the database did not conduct a transaction.
    5. Assert there is a visable UI change.
OUTPUT VALUES:
POSTCONDITIONS:
POSTCONDITIONS: No assertion failed, and no errors were thrown during execution.

IDENTIFIER: NFUN-IDEMPOTENT
TEST CASE:  8
PRECONDITIONS: Load the webpage http://www.thinkthroughmath.com/request-a-demo/.
INPUT VALUES:
EXECUTION STEPS:
    1. Complete the form with all approperate values.
    2. Press sumbit twice within quick succession, before the page reloads.
    3. Assert that there are not two identical records in the database with the information you provided.
OUTPUT VALUES:
POSTCONDITIONS: No assertion failed, and no errors were thrown during execution.

IDENTIFIER: NFUN-UI-AWARE
TEST CASE: 9
PRECONDITIONS: Load the webpage http://www.thinkthroughmath.com/request-a-demo/.
INPUT VALUES:
EXECUTION STEPS:
    1. Hire twenty people to test the software.
    2. Instruct them to enter invalid data (on separate machines).
    3. Instruct them to submit the form.
    3 1/2. Allow them to view the screen to their contentment and then turn off the monitor.
    4. Ask them if they noticed a change in the UI after submission.
OUTPUT VALUES:
POSTCONDITIONS: Statistical analysis shows that 95% of the users noticed a UI change.

IDENTIFIER:
TEST CASE:
PRECONDITIONS: Load the webpage http://www.thinkthroughmath.com/request-a-demo/.
PRECONDITIONS:
INPUT VALUES:
EXECUTION STEPS:
OUTPUT VALUES:
POSTCONDITIONS:
POSTCONDITIONS: No assertion failed, and no errors were thrown during execution.

