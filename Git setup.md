These are the steps to reproduce a obsidian vault with git external repo
1. Install Termux and Obsidian
2. In Obsidian, 
	A. create a vault using local, not app, storage
3. In Termux, 
	A. Run termux-setup-storage and give app permission
	B. Install Git
		I. Setup global variables using git config  --global
	C. (Optional) Create a soft link to the obsidian repo to a local termux storage location
	D. 
