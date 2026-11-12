# Hossana Villanueva — GitHub Pages Portfolio

A responsive, minimalist-light portfolio made with plain HTML and CSS for GitHub Pages.

## Target website

- GitHub account: `ylianne`
- Repository name: `ylianne.github.io`
- Expected website address after deployment: <https://ylianne.github.io>

The website is not published yet. You must create the repository and upload these files to your GitHub account.

## 1. Personalize the profile photo

The hero section currently uses `assets/profile-photo-placeholder.svg` as a temporary placeholder.

1. Choose a professional photo of yourself (portrait orientation works best; 4:5 is ideal).
2. Place the image inside the `assets` folder and name it `profile-photo.jpg`.
3. Open `index.html` and find:

   ```html
   <img src="assets/profile-photo-placeholder.svg" alt="Placeholder for Hossana Villanueva's professional profile photo">
   ```

4. Replace that line with:

   ```html
   <img src="assets/profile-photo.jpg" alt="Hossana Villanueva">
   ```

5. You can then delete `assets/profile-photo-placeholder.svg` if you no longer need it.

## 2. Review your career documents before publishing

The `documents` folder includes the resume and application letter you uploaded, in both PDF and Word formats.

Please check two things before making the site public:

- Your resume says your expected BSIT graduation is 2027, while the application letter describes you as a recent graduate. Update the letter so the education status is consistent before using it for an actual application.
- The downloadable documents contain your mobile number and email address. Anyone who can access the public website may download them. Remove or revise personal contact details if you do not want them publicly available.

The PDF application letter in this package has a minor layout-only adjustment (reduced margins and font size) so the closing and your name fit on one page. Its wording has not been changed. The included Word document is the original file you uploaded.

## 3. Create the GitHub repository

1. Sign in to <https://github.com> using the account with username `ylianne`.
2. Click the **+** menu in the upper-right corner and choose **New repository**.
3. Enter this exact repository name: `ylianne.github.io`.
4. Set the repository to **Public** if you are using GitHub Free. GitHub Pages on GitHub Free requires a public repository.
5. Check **Add a README file** (or leave it unchecked if you prefer to upload this package's README yourself).
6. Click **Create repository**.

## 4. Upload the website files

1. Unzip this portfolio package on your computer.
2. Open the new repository: <https://github.com/ylianne/ylianne.github.io>.
3. Select **Add file** → **Upload files**.
4. Upload the *contents* of the unzipped `ylianne-portfolio` folder. The `index.html` and `style.css` files must be at the repository's top level. Keep the `assets` and `documents` folders intact.
5. Scroll down and click **Commit changes**.

Your repository should look like this:

```text
ylianne.github.io/
├── index.html
├── style.css
├── README.md
├── assets/
│   ├── favicon.svg
│   ├── profile-photo-placeholder.svg  (replace with your photo)
│   └── profile-photo.jpg              (your own photo, after replacement)
└── documents/
    ├── Hossana_Villanueva_Resume-v2.pdf
    ├── Hossana_Villanueva_Resume-v2.docx
    ├── Hossana_Villanueva_Application_Letter.pdf
    └── Hossana_Villanueva_Application_Letter.docx
```

## 5. Turn on GitHub Pages

1. In your repository, open **Settings**.
2. In the sidebar, choose **Pages**.
3. Under **Build and deployment**, set **Source** to **Deploy from a branch**.
4. Under **Branch**, choose `main` and `/ (root)`.
5. Click **Save**.
6. Return to **Settings** → **Pages** and use **Visit site** once GitHub displays the published address.

Your portfolio address should be:

**<https://ylianne.github.io>**

The first deployment can take several minutes. If the site does not appear immediately, refresh the Pages settings later and check the deployment status.

## 6. Check the website before sending it to your professor

- Open the website on both a computer and a phone.
- Confirm your own profile photo appears (not the placeholder).
- Click each navigation link and test both document downloads.
- Open the downloaded PDFs to confirm they are readable.
- Confirm the public version contains only contact information you are comfortable sharing.
- Send your professor the published website address, not the repository ZIP file.

## Updating the portfolio later

To change text or colors, edit `index.html` or `style.css` in the repository and commit the change. To add screenshots, upload them into `assets/` and update the relevant project section in `index.html`.

This is a static website. It uses HTML and CSS only; GitHub Pages will not run an ASP.NET Core server or SQL Server database for your projects. You can link to public project repositories or demonstrations when you are ready to share them.
