# portfolio

Alexandre Cruel's personal portfolio.

## Usage

This portfolio is accessible from this [domain](https://alexandre-cruel.github.io/portfolio/).
It has been developped using HTML5, CSS3 and JavaScript.
It is deployed using the free version of GitHub Pages.

## Install

- Use VSCode `Live Server` plugin for debugging
- To run the portfolio locally : right click / Open with Live Server.

## Resources

[Used this tutorial to get started](https://youtu.be/0YFrGy_mzjY)
[Used for background management](https://www.codeur.com/tuto/css/effet-parallaxe-css/#:~:text=L'effet%20de%20parallaxe%20en,'exploration%20de%20l'utilisateur.)
[Website for icons](https://fontawesome.com/icons)
[Link to website deployment](https://www.geeksforgeeks.org/how-to-create-and-deploy-your-portfolio-in-under-10-minutes/)

## Deployment

1. Create a New Tag Locally
   Choose a new tag version (e.g., v1.2.0):

```shell
git tag v2.0.1
git push origin v2.0.1
```

You can view existing tags with git tag.

2. Create a Release on GitHub

   - Go to your repo: https://github.com/alexandre-cruel/portfolio
   - Click on "Releases" (right sidebar or under "Code").
   - Click "Draft a new release".
   - In the "Tag version", select v2.0.1 (should be available after push).

Fill in:

- Release title (e.g., Portfolio Update - July 2025)
- Description (optional: list key changes or fixes).
- Click "Publish release".

3. Verify the Deployment
   If Using GitHub Pages:
   Navigate to your site URL: https://your-username.github.io/your-repo-name
   Refresh with Ctrl+Shift+R (force reload) to clear cache.

## Developer Notes

- Use `Prettier` plugin for readability of HTML
- Use `Command` + `MAJ` + `V` to view README in

- To format the code:

  1. CTRL + MAJ + P
  2. Type format
  3. Select "Format Document"

- [HTML Code Validator](https://validator.w3.org/):

  1. Go to this website
  2. Select "file upload"
  3. Runs verifications on your html

- [CSS Validator](https://jigsaw.w3.org/css-validator/)

- Pour ajouter des tags facilement:

  1. Select un bout de code à mettre dans des tags.
  2. View (Affichage) / Command Palette <SHIFT + POM + P>
  3. Search for "Wrap with Abreviation"
  4. Press Enter
  5. Type element you want to wrap your element with

- [Special characters in HTML](https://www.w3schools.com/html/html_entities.asp)

- Pour ouvrir un div class, commencer par tapper le nom de la class puis enter comme: `#about` + `ENTER` ou `.container` + `ENTER`.

- Si le `git push` se bloque, rouler `git config --global core.askpass "git-gui--askpass"`

- [Website used for pictures](https://unsplash.com/s/photos/portfolio)

## Diff from tutorial

- "grid-gap" is deprecated so I'm using "gap"
