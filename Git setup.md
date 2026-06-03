These are the steps to reproduce a obsidian vault with git external repo
1. Install Termux and Obsidian
2. In Obsidian, 
	1. create a vault using local, not app, storage.
3. In Termux, 
	 1. Run termux-setup-storage and give app permission.
	2. Install Git.
		1. Setup global variables using git config  --global
	3. (Optional) Create a soft link to the obsidian repo to a local termux storage location.
	4. Create the git in the obsidian folder. Make first commit.
	5. Start SSH. Create and add an SSH key.
4. In Github,
	1. Create a new repo
	2. Add the ssh key pub file
5. In Termux,
	1. Push the first commit to the github repo
