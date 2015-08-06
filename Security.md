# Using GitHub

These are the requirements to join our GitHub organization. None are optional, and everyone on staff _must_ have a GitHub account.

## Creating and customizing an account 

If you haven't created a GitHub account yet, do so with your government email, which will assist with [records retention](http://ben.balter.com/open-source-for-government/#records).  

If you already have a GitHub account, simply [add your goverment email to your existing account](https://help.github.com/articles/adding-an-email-address-to-your-github-account/). Do not create a new account. You can also set up custom email routing through the [Notifications Center](https://github.com/settings/notifications). Make sure your commits are [associated with your government email address](https://help.github.com/articles/setting-your-email-in-git).

Note that associating commits with an email address is different from [setting notifications to go to one or another email address](https://help.github.com/articles/configuring-notification-emails-for-organizations/). You also have to change the official commit email address attached to each repo.

If you’re using your work computer for personal projects on GitHub and want your personal email tied to those commits, you can set your GSA email as part of the global `.gitconfig`, then [override on a repository level](http://git-scm.com/book/en/v2/Customizing-Git-Git-Configuration) with your personal email. If you have both emails [in your GitHub settings](https://github.com/settings/emails), though, they will both be tied to your GitHub account.

Make sure you have [notifications turned on](https://github.com/settings/notifications) and make sure your notifications are set up they way you'd like them.

### Setting up an account profile

#### [Activate 2-factor Authentication](https://github.com/blog/1614-two-factor-authentication)

Everyone is *required* to use 2-factor authentication (2FA) for their GitHub access. While you're at it, it's a *very, very* good idea to do this for your [email account](http://lifehacker.com/5932700/please-turn-on-two-factor-authentication/all) and [elsewhere](http://lifehacker.com/5938565/heres-everywhere-you-should-enable-two-factor-authentication-right-now/all). GitHub access _will not_ be provided if 2FA is turned off. Also be sure to [save your recovery codes](https://help.github.com/articles/downloading-your-two-factor-authentication-recovery-codes/) in case you lose access to 2FA.

#### [Add your information to your account](https://github.com/settings/profile)

This makes it easier for your team to know who you are, but most of all, it helps a lot with autocomplete!

A complete [public profile](https://github.com/settings/profile) includes:

- **Name:** Your first or first and last name.  
- **Company:** Your government agency.
- **Location:** Your primary work location (City, State).
- **Email:** A [verified government email address](https://help.github.com/articles/verifying-your-email-address/).

#### [Add a profile picture of yourself](https://help.github.com/articles/how-do-i-set-up-my-profile-picture/)

This is a courtesy that makes team projects all the more social and fun.  It only takes a second but your teammates will _really_ appreciate it. We don't require that it be an actual headshot, but please make it a unique avatar.

It only takes a moment to go to [your settings page](https://github.com/settings/profile) and upload a picture.  


#### Make your membership public

Go to the organization's [team page](https://github.com/orgs/18F/people) and click **Make Public**. 


## USCIS Pilot Organization Structure

-  One organization will contain all USCIS teams 
-  Users will only be able to get access to the organization by invite from a current administrator within the environment
-  There will be a total of 50 private repositories for the entire organization for the first month
-  Team and repo nomenclature – make repo and team names specific to their access and system i.e. USCIS-WriteTeam-Repo1 (System-Access-Repo)
-  Private repository access will be granted on a team by team basis subject to the Configuration Manager. 
A backup system will be put in place in case an emergency recovery is needed 


## Teams

Teams can give you [`administrative`, `write`, or `read` permissions](https://help.github.com/articles/permission-levels-for-an-organization-repository/). Even if you have `write` access into a repository, we _strongly_ encourage the submission of pull requests for improvements or fixes.

Contractors or external government collaborators should only be added to teams with scoped `write` permissions to the respositories they're working on. They should *never* have `administrative` level rights. In order to separate out these permissions, create a team in the format of `projectname-admins` for government staff if necessary.


## Team Structure 

-  There will be an Owners team which will govern the organization 
-  Each project will have its own team within the organization 
-  Teams will be comprised of selected and authorized users from within the USCIS 
-  Users will be added to teams by the designated administrators of those teams 
-  Users can be associated with multiple teams if necessary
-  Users will be documented by their knowledge and expertise 
-  Users will have a .gov email associated with their account  
-  Access permissions (Read/Write/Admin) will be set at the team level  
-  Designated team administrators will set rules and regulations for their team members


## Additional resources

* [The GitHub Government Community](https://github.com/government/welcome#readme)
