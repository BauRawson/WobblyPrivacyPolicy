# Wobbly Games privacy policies

A tiny static site for hosting game privacy policies with GitHub Pages.

## Publish it

1. Create a GitHub repository named `WobblyPrivacyPolicy` under the `baurawson` account and push these files to its default branch.
2. In the repository, open **Settings → Pages**.
3. Under **Build and deployment**, select **Deploy from a branch**, then select the default branch and the `/ (root)` folder. Save.

GitHub will publish POP POP!'s policy at:

`https://baurawson.github.io/WobblyPrivacyPolicy/poppop/`

SleepyKnight's policy will be at:

`https://baurawson.github.io/WobblyPrivacyPolicy/sleepyknight/`

GitHub Pages commonly preserves the repository name's capitalization in the URL. The lowercase form in the requested example may also resolve, but use the URL GitHub displays in **Settings → Pages** as the canonical link.

## Add another game

Copy `poppop/index.html` to a new lowercase, hyphenated folder such as `my-new-game/index.html`, update its contents, and add a link to it in the root `index.html`. Its URL will be `/WobblyPrivacyPolicy/my-new-game/`.
