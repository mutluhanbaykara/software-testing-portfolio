## Login Test Cases

### Positive Login 1
- Valid username entered
- Valid password entered
- Login button clicked

Expected:
- User logs in successfully
- User is redirected to dashboard

### Positive Login 2
- Click on Login with Google

Expected:
- User is authenticated via Google
- User is redirected to main page

### Negative Login 1
- Invalid username entered
- Valid password entered

Expected:
- Login fails
- Generic error message displayed
- User stays on login page

### Negative Login 2
- Valid username entered
- Invalid password entered

Expected:
- Login fails
- User is not redirected

### Edge Case
- Valid credentials entered
- Internet connection disabled
- Login button clicked

Expected:
- Login fails
- Network error message displayed
