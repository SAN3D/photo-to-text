# Setup Instructions

1. Install Git from https://git-scm.com/download/win

2. After installation, open a new Command Prompt and run:
```
git clone https://github.com/SAN3D/photo-to-text.git
cd photo-to-text
```

3. Extract all files from the zip into the photo-to-text folder

4. Then run these commands:
```
git add .
git commit -m "Initial commit: Photo to Text Converter"
git push origin main
```

When pushing, you'll need to authenticate:
- Username: your GitHub username
- Password: use your GitHub Personal Access Token (PAT)

To create a PAT:
1. Go to GitHub.com → Settings → Developer Settings → Personal Access Tokens → Tokens (classic)
2. Click "Generate new token"
3. Select scopes: 'repo' and 'workflow'
4. Copy and save the token - you'll need it when pushing