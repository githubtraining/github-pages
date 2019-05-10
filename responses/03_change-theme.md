## Step 4: Customize Site Details

Great work! You can see your selected theme in action [here](https://{{ user.username }}.github.io/{{ repo }}). If you don't see your changes right away, refresh the page.

### Getting your page blog ready

GitHub added the theme you selected to your `_config.yml` file. Jekyll uses the `_config.yml` file to store  settings for your site, like your theme, as well as reusable content like your site title and GitHub handle.

You can check out the `_config.yml` file on the **Code** tab of your repository.

### :keyboard: Activity: Modify the config file

Let's change the `_config.yml` so it's a perfect fit for your new blog. First, we need to use a blog-ready theme. For this activity, we will use a theme named `jekyll-theme-minimal`.

1. Navigate to the **Code** tab of this repository, and browse to the `_config.yml` file, or click this link [here]({{ repoUrl }}/blob/master/_config.yml).
2. In the upper right corner, click :pencil2: to open the file editor.
3. Change `theme:` to **jekyll-theme-minimal** so it shows in the `_config.yml` file as below:
    ```
    theme: jekyll-theme-minimal
    ```
4. Modify the other configuration variables such as `title:`, `author:`, and `description:` to customize your site.
5. Click **Create a new branch for this commit and start a pull request**.
6. Open a pull request.

<hr>
<h3 align="center">Look for my next response in your pull request.</h3>
