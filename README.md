# Dalle2-webapp

![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54)
![Dependabot](https://img.shields.io/badge/dependabot-025E8C?style=for-the-badge&logo=dependabot&logoColor=white)

## Sample Image of this Application
![image](https://user-images.githubusercontent.com/95544839/220708010-2a64b06f-530b-46ad-b41c-020e5d2a5522.png)


## Step-by-step Guide (Run Locally)
### Install Python Module
- Install all the modules (using pip)
```bash
  pip install -r requirements.txt
```

---
### auth.py file
- Open the ```auth.py``` file and add: 
```bash
  auth_token = "YOUR_AUTH_TOKEN"
```
Create, Copy & Replace the API Key from OpenAI website under 'User the Setting > View API Keys'. The 'auth.py' file would look like this: `auth_token = "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"`

- RUN APP FUNCTION
```bash
app.mainloop()
```

---
### Run The App
- From the root directory of 'app.py', run in terminal" 
```bash
  python app.py
```
or
```bash
  python3 app.py
```
