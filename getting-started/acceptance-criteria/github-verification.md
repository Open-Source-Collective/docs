# GitHub Verification

## What is Github Stars Verification?

Open Source Collective offers the option to verify your Collective by showing that it has at least 100 Github stars. Meeting this requirement can expedite the approval of your Collective.

### What if I can't verify with Github stars?

If your project is not centred on a Github repository, or you can't get the automated verification system to work for you even if you have 100 stars, please request [manual verification](manual-verification.md) instead.

## Github Verification Troubleshooting

### I can't find my repository or my organization's repository.

There are a few possible causes for that:

**#1: You may be using the wrong GitHub account in the authorization process**

If you believe that you may have linked the wrong GitHub account to your Open Collective account, you will need to manually revoke access from the current linked GitHub profile. You can do that by either accessing [https://github.com/settings/applications](https://github.com/settings/applications) or following our guide:

**1.** On GitHub, go to **Settings**.

![](../../.gitbook/assets/gh1-fiscal-host\_open-source-collective\_github-dropdown-menu\_2019-10-28.png)

**2.** On the Settings menu, click on **Applications**.

![](../../.gitbook/assets/gh2-fiscal-host\_open-source-collective\_github-settings-interface\_2019-10-28.png)

**3.** On the **Applications** page, open the **Authorized OAuth Apps** tab and look for Open Collective.

![](../../.gitbook/assets/gh3-fiscal-host\_open-source-collective\_github-list-oauth-apps\_2019-10-28.png)

**4.** Click on the three dots on the right labeled "Show me more options" to revoke the authorization.

![](../../.gitbook/assets/gh4-fiscal-host\_open-source-collective\_github-list-oauth-revoke\_2019-10-28.png)

**#2: You used the right account, but you didn't grant access to organization repositories**

During the authorization process, GitHub lists the organizations in which you are a member. Depending on [the permission level](https://help.github.com/en/github/setting-up-and-managing-organizations-and-teams/permission-levels-for-an-organization) you have at each one of them and their [third party access policy](https://help.github.com/en/github/setting-up-and-managing-organizations-and-teams/enabling-oauth-app-access-restrictions-for-your-organization), you may have to either grant permission on that page or request it.

![](../../.gitbook/assets/gh5-fiscal-host\_open-source-collective-github-authorize-open-collective\_2019-10-28.png)

### My repository is listed but I can't create a **C**ollective (Error: We could not verify you are the admin of the GitHub organization).

Depending on [the permission level](https://help.github.com/en/github/setting-up-and-managing-organizations-and-teams/permission-levels-for-an-organization) you have at an organization, you may not be authorized to perform that action. Contact other members of your organization to discuss that process.

### There are too many repositories listed on my page. How can I find the right repository?

Use the search bar to filter repositories by name:

![](../../.gitbook/assets/gh6-fiscal-hosts\_open-source-collective\_search-bar-pick-a-repo\_2019-10-28.gif)

### The permissions you ask for are overly generous and my organization doesn't want to grant them.

We agree the permissions are overly generous. Unfortunately, there's not much we can do at the moment since this is the only scope we can use to read the info we need. We've discussed this at length on issues [#355](https://github.com/opencollective/opencollective/issues/355), [#1034](https://github.com/opencollective/opencollective/issues/1034) and [#2333](https://github.com/opencollective/opencollective/issues/2333).

If you have any suggestions on how to handle this better, feel free to join the discussions, start a new one, or send us an email [support@opencollective.com](mailto:support@opencollective.com).
