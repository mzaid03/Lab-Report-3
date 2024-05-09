Part 1 - Bugs

A failure-inducing input for the buggy program, as a JUnit test and any associated code (write it as a code block in Markdown).
![Image](labreport3.1.png)

Associated code

![Image](labreport3.2.png)

2. An input that doesn't induce a failure, as a JUnit test and any associated code (write it as a code block in Markdown).

![image](labreport3.4.png)


3. The symptom, as the output of running the two tests above (provide it as a screenshot -- one test should pass, one test should fail).

![Image](labreport3.3.png)

4. The bug, as the before-and-after code change required to fix it (as two code blocks in Markdown).

Before fix

![image](labreport3.2.png)

After fix

![Image](labreport3.5.png)

5. Briefly describe (2-3 sentences) why the fix addresses the issue.
The issue occured due to an incorrect loop condition. The condition `start <= end` was causing an extra iteration, which is not necessary for reversing the array. The corrected version uses `start < end` as the condition, ensuring the loop stops when the start index crosses the end index. This adjustment successfully reverses the array elements.


Part 2 - Researching Commands

1.

![Image](labreport3.11.png)

![Image](labreport3.12.png)

2.

![Image](labreport3.13.png)

![Image](labreport3.14.png)

3.

![Image](labreport3.15.png)

![Image](labreport3.16.png)
4.

![Image](labreport3.17.png)

![Image](labreport3.18.png)
