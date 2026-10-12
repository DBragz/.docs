# GitHub

Contains documentation steps for setting up GitHub access.

## Generate Access Token

1. Sign in to your GitHub account at [github.com](https://github.com).

2. Click on your profile picture in the upper right corner, and select **"Settings."**

3. In the left sidebar, click on **"Developer settings."**

4. Under **"Developer settings,"** select **"Personal access tokens."**

5. Click on **"Tokens (classic)"** if you want to generate a classic token.

6. Click the **"Generate new token"** button.

7. In the form that appears, give your token a descriptive name and select the scopes or permissions you'd like to grant this token. For basic access, you might select:

    - `repo` (to access your private repositories),
    - `workflow` (to access GitHub Actions workflows),
    - any other necessary scopes based on your needs.

8. After configuring the permissions, click **"Generate token."**

9. Copy the generated token and store it securely. You will not be able to see it again once you navigate away from the page.

Make sure you keep your token secure, as it provides access to your GitHub account based on the scopes you selected. Use this token as a password when prompted during Git operations.

## Authors

- [Daniel Ribeirinha-Braga](https://github.com/DBragz)
