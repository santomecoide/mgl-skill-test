# Bugs, glitches, or areas for improvement

### Backend unit test
Should implement backend unit test

### Separate backend and frontend
Separate backend and frontend in different folders and projects. Avoid run scripts in this way
```bash
"client": "craco start",
"server": "cd backend & npm start",
```

### ESLint
ESLint to improve the reading of your code. Can use "eslint-config-airbnb-base" or some popular base config 

### Use secrets
Use some cloud secrets for read passwords and others sensitive information. Even in the env file
```bash
EMAIL_PWD=Password123#
```

### Use a global variable for set environments
Use some global variable like ENV or something for set the environment (dev, qa, prod). Avoid comment the code for change the environment
```bash
// export const SERVER_URL = "http://10.10.12.157:5000/api/"
```

### Check mail server
Consider using an email service for production. Only use Gmail SMTP for the development environment.
