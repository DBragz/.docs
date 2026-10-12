# Replit

Contains documentation steps for setting up development via Replit.

## Add Secret to Workspace

1. Open the **Tools** pane and select **Secrets**.

2. Click + **New Secret**.

3. Use the same key name as your Account Secret.

4. Copy the value from your Account Secret and paste it into the Value field.

5. Click **Add Secret**.

## Use GitHub Access Token as Secret

1. Open the **Shell** tool from the Tools pane in Replit.

2. **Configure Git** (if you haven’t already):

    - Set your username and email:

    ```shell
    git config --global user.name "Your Name"
    git config --global user.email "your.email@example.com"
    ```

3. Add your remote repository:

- Use your GitHub access token from the secret you created. Replace `your-username` with your GitHub username, `your-repo` with your repository name, and `YOUR_SECRET_NAME` with the name of your secret:

    ```shell
    git remote add origin https://your-username:$(echo $YOUR_SECRET_NAME)@github.com/your-username/your-repo.git
    ```

## Authors

- [Daniel Ribeirinha-Braga](https://github.com/DBragz)
