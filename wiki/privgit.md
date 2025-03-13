# adding private github repos through github desktop and cpanel gitversion control

(This is mostly for myself, but I suppose it could be helpful to someone else too!)

(Also note to myself: more copy-and-paste-able version can be found in my Notes.)

<hr />

Github Desktop:

	1. In repository (header) > Repository > Repository Settings
	2. Remote > Primary Remote Repository (origin) URL
	3. Make sure that repository URL is HTTPS://

cPanel version control:

	1. Open cPanel
	2. Open Terminal
	3. Commands:
		a. ssh-keygen -t rsa -f ~/.ssh/KEYFILENAME -b 4096 -C “USER@HOSTDOMAIN”
		b. touch ~/.ssh/config@HOSTDOMAIN”
		c. chmod 0600 ~/.ssh/config@HOSTDOMAIN”
		d. chown USER:USER ~/.ssh/config@HOSTDOMAIN”
	4. SSH Access > Manage SSH Keys
		a. Key > Manage > Authorize
		b. Key > View/Download > Copy key
	5. Github > Repository > Settings
		a. Deploy Keys > Add deploy key
		b. Title: anything
		c. Key: paste from earlier (“copy key”)
			i. Allow write access
	6. New tab > File Manager
		a. .ssh (folder) > config (file)
		b. Add to file:
			i. Host GITHUBREPOSITORYNAME.github.com
   			ii. User git
			iii. Hostname github.com
			iv. IdentityFile ~/.ssh/KEYFILENAME
    			A. IdentitiesOnly yes
		c. Save and close
	7. Back in Terminal
		a. Test if it works with ssh -Tv git@GITHUBREPOSITORYNAME.github.com
	8. GitVersion Control
		a. Create
		b. For the repository URL, make sure the format is:
			i. ssh://GITHUBREPOSITORYNAME.github.com/GITHUBUSERNAME/GITHUBREPOSITORYNAME

Profit !!
