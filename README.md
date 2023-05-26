# openaiProject
This web app uses the OPEN AI API to take prompt from the user about the question category and its level to return the questions of mentioned category from Leetcode.
## Errors

1. Not completed the endpoint in fetch() of frontend,also ```proxy``` in package.json should have address of the backend.

2. Get Request - CORS error - just enable cors through the response.header that is passed from backend to frontend because browser follows same origin policy for safety.In case of this error dont disable cors in browser manually,rater control it via code.

3. Post Request - There wasn't any problem in code.The problem was virtual environment was not setup properly.In the ```requirements.txt``` there were many other packages that weren't needed for the project also faced issues during their installation.Just delete the venv and install it once again.Then check the ```requirements.txt``` if its correct and confirm.
 
 ## To run flask in backend
 
 First install virtual environment - ``` python -m venv env ```

Then run this -
```
env\scripts\activate
flask run
```

## For frontend

To install the react packages.

``` npx create-react-app ```

To run for development.

``` npm start ```

![output1](https://github.com/jesmigeorge/openaiProject/assets/98166252/515b14cb-a53a-476b-8c54-b50e3a4c1cd3)

![output](https://github.com/jesmigeorge/openaiProject/assets/98166252/c2626539-52e6-4131-af81-ffddec7a75df)
