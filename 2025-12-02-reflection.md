# Daily Reflection — December 2, 2025

### What I Learned
Today I learned how to replace GitHub personal access tokens with a secure SSH authentication workflow. I generated an ED25519 SSH key pair, added the public key to my GitHub account, and successfully authenticated from my Windows machine.

### Hands-on Practice
- Generated SSH keys using `ssh-keygen`
- Copied the public key and added it to GitHub
- Verified authentication with `ssh -T git@github.com`
- Learned why SSH is more secure and convenient than classic tokens

### Key Insight
Secure authentication is easier and safer when it removes friction. SSH eliminates token expiration problems and makes daily Git operations smoother.

### Next Step
Tomorrow I will switch my existing local repositories from HTTPS to SSH and test pushing through VS Code.
