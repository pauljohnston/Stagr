Softlabs Vagrant
=====

###Local development server setup (based on fortrabbit).

Forked from [Stagr](https://github.com/gmanricks/Stagr) and modified to work as a local fortrabbit environment.

------------------------------------

### Installation

**Step 1: Install VirtualBox**<br>
*[https://www.virtualbox.org/wiki/Downloads](https://www.virtualbox.org/wiki/Downloads)*

**Step 2: Install Vagrant**<br>
*[http://www.vagrantup.com/downloads.html](http://www.vagrantup.com/downloads.html)*

**Step 3: Install Pow**<br>
*curl get.pow.cx | sh*

**Step 4: Clone Repo**<br>
*git clone https://github.com/pauljohnston/Stagr.git*

**Step 5: Enter the Directory**<br>
*cd Stagr*

**Step 6: Copy and rename synclist**<br>
*Copy and rename 'Vagrant_synclist(example).yml' to 'Vagrant_synclist.yml'*

**Step 7: Run Vagrant**<br>
*vagrant up*


### Adding a site

**Step 1: Add your site to Vagrant_synclist.yml**<br>
*see example in YAML file* **(Ensure spaces are used and not tabs)**

**Step 2: forward app traffic to vagrant**<br>
*echo 8080 > ~/.pow/example*

**Step 3: Reload Vagrant**<br>
*vagrant reload*

**Step 4: Login to the VM**<br>
*vagrant ssh*

**Step 5: Run Stagr**<br>
*sudo stagr*

**Step 6: Follow the Prompts**

