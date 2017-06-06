# MEAN JS Server Config (Ubuntu/Trusty64)

###### Step 1
Open config_vars.yml in playbooks/roles/common/files. Enter your server `hostname` and `username`.

###### Step 2
Run mean_stack.yml to setup MongoDB and NodeJS on your server

###### Step 3
Run test_project.yml to see if your set up is working. Once successful, you can visit `http://[servername-or-IP]:3000` to see the test project.
