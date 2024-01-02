# Email-Validate
Email Validate using Regex

 **Email Validation with Regular Expressions in Python**

This code snippet demonstrates how to validate an email address using regular expressions in Python. It defines a regular expression pattern called `email_Condition` that matches valid email addresses. The pattern consists of the following components:

- `^[a-z]+[\._]?[a-z 0-9]+[@]\w+[.]\w{2,3}$`: This is the main regular expression pattern.
  - `^[a-z]+`: Matches one or more lowercase letters at the beginning of the string.
  - `[\._]?`: Matches an optional dot (.) or underscore (_) character.
  - `[a-z 0-9]+`: Matches one or more lowercase letters or digits after the optional dot or underscore.
  - `[@]\w+`: Matches an "@" symbol followed by one or more word characters.
  - `[.]\w{2,3}$`: Matches a dot (.) followed by two or three word characters at the end of the string.

The code then prompts the user to enter their email address and stores it in the `user_email` variable. It uses the `re.search()` function to check if the `user_email` matches the `email_Condition` pattern. If there is a match, it prints "Right Email"; otherwise, it prints "Wrong Email".

Here's a step-by-step explanation of the code:

1. Define the regular expression pattern `email_Condition` to match valid email addresses.
2. Prompt the user to enter their email address and store it in the `user_email` variable.
3. Use the `re.search()` function to check if the `user_email` matches the `email_Condition` pattern.
4. If there is a match, print "Right Email"; otherwise, print "Wrong Email".

This code provides a simple way to validate email addresses using regular expressions in Python. It can be easily integrated into larger applications or scripts that require email address validation.
