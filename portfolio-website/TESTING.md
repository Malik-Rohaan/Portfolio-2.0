# Testing Notes

## W3C validation (https://validator.w3.org/)
Use "Validate by File Upload" for index.html, information.html and registration.html. Screenshot each result into a `screenshots/` folder.

## Form validation tests (registration.html)
| Test | Expected result |
|------|-----------------|
| Submit with empty required fields | Browser blocks submission and highlights the first empty field |
| Enter email "abc" | Browser asks for a valid email address |
| Enter password "1234567" | Browser reports the password is too short |
| Enter age 10 or 120 | Browser reports the value is out of range |

## Browser comparison (fill in after testing)
| Feature | Chrome | Firefox | Differences |
|---------|--------|---------|-------------|
| Navigation links | | | |
| Image display | | | |
| Audio and video controls | | | |
| Form validation messages | | | |
| Date picker appearance | | | |
