# Lab 5 - Starter

**Jiawei Huang** <br>
**Joseph Jun**

## Link to the GitHub page site:
[explore.html](https://j2jun.github.io/Lab5_Starter/explore.html/)
[expose.html](https://j2jun.github.io/Lab5_Starter/expose.html/)

## Pt 3. Unit Testing with Jest

<ol>
    <li>Would you use a unit test to test the “message” feature of a messaging application? Why or why not? For this question, assume the “message” feature allows a user to write and send a message to another user.</li>
        <ul>
            <li>No, I would not use a unit test to test the "message" feature of a messaging application. Unit tests are primarily used to test small test units of code that tests functions or methods. The "message" feature will require to test user interface interactions, network communications, and other multiple, complex components. Therefore, unit tests are not a good choice to test the "message" feature of a messaging application.</li>
        </ul>
    <li>Would you use a unit test to test the “max message length” feature of a messaging application? Why or why not? For this question, assume the “max message length” feature prevents the user from typing more than 80 characters.</li>
        <ul>
            <li>Yes, I would use a unit test to test the "max message length" feature of a messaging application. This feature can be easily be tested without invovling multiple, complex components. For example, you can create unit tests to verify that attempting to send a message longer than 100 characters is properly handled by the application.</li>
        </ul>
</ol>
