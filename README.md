Azeem khan
Student At Aligarh Muslim University
 HEAD
git remote set-url origin https://Azeem-khan0786:<your-token>@github.com/Azeem-khan0786/MyRepository.git

From August 13, 2021, GitHub is no longer accepting account passwords when authenticating Git operations. You need to add a PAT (Personal Access Token) instead, and you can follow the below method to add a PAT on your system.
// Error During push code in remote

git push origin main Username for 'https://github.com': Azeem-khan0786 Password for 'https://Azeem-khan0786@github.com':  remote: Support for password authentication was removed on August 13, 2021. remote: Please see https://docs.github.com/get-started/getting-started-with-git/about-remote-repositories#cloning-with-https-urls for information on currently recommended modes of authentication. fatal: Authentication failed for 'https://github.com/Azeem-khan0786/MyRepository.git/'

Create Personal Access Token on GitHub
From your GitHub account, go to Settings => Developer Settings => Personal Access Token => Generate New Token (Give your password) => Fillup the form => click Generate token => Copy the generated Token, it will be something like ghp_sFhFsSHhTzMDreGRLjmks4Tzuzgthdvfsrta

 git remote set-url origin https://Azeem-khan0786:<your-token>@github.com/Azeem-khan0786/MyRepository.git
 c2a5758244ddc2cb8f1187bb3794d508f33e25f9
