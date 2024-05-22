# usingshellscriptrepoinfo
# through shell script getting the list of repo users(integrating ec2instence to github using api through http protocal)
# 1st launch the ec2 instance with amazon linux kernal, withoutkeypair,securitygroup,volume
# install git (using yum install git -y) check version git --version
# clone the script from github or u can create scripting file in ur terminal only
# if cloning script from git the command is git clone url of the repo(git clone https://github.com/practicedevopsprojects/usingshellscriptrepoinfo.git)
# after go to ur script path then export the username and token from your github acoount here we give token only instead of password of ur account because we use apis thats the reason we use tokens
# run the script(./filename along with commandline arguments) ./listrepousers practicedevopsprojects usingshellscriptrepoinfo
# 
