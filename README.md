## Repo for CapRover One Click Apps by SelfHosted.club

If you'd like this to work under your Caprover setup, go to Apps, scroll all the way down and add https://caprover.selfhosted.club under "3rd party repositories:"; click "Connect new repository".

You're done.

---------

## Build your own one-click app repository
You may want to build your own private repository. CapRover supports having multiple repositories. You can add new repository URLs to the one click app page. The official one, this one, is available as `https://oneclickapps.caprover.com`.

To create your own repository:
- Fork this repository
- Delete all existing apps (to avoid duplicate apps), and add your own apps.
- Run `npm i`
- Run `npm run validate_apps`
- Run `npm run formatter-write`
- Run `npm run build`
- Now you can host the static content placed in `./dist` directory anywhere you want, the official repo uses github pages to publish the content. Make sure to update [CNAME](https://github.com/caprover/one-click-apps/blob/master/public/CNAME) to your own URL if you decide to do so.

### Third party One Click Apps

In order to add a third party repository:
-   Login to your CapRover dashboard
-   Go to **apps** and click on **One-Click Apps/Databases** and scrolldown to the bottom
-   Under **3rd party repositories:** copy  the URL, (for example: `https://Awes0meHub.github.io/caprover-one-click-apps`) and paste it in to the text box
-   Click the **_Connect New Repository_** button

#### 3rd party repositorie
-   Awes0meHub: [Github](https://github.com/Awes0meHub/caprover-one-click-apps) repository: `https://Awes0meHub.github.io/caprover-one-click-apps`
-   Jordan-hall: [Github](https://github.com/Jordan-Hall/caprover-one-click-apps) repository: `https://oneclickapps.libertyware.io`
