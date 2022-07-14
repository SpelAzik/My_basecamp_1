# README

Here simple authentication project. 
For instance, Log in, Log out, Sign up, Forgot your password and also CRUD(create, read, update, delete).
If you want to get some experience you need to follow description as shown below.

Note: this description for windows users.

* Text editor (VSCode)
    You can download and install with this URL: https://code.visualstudio.com/

* Install Ruby
    First of all check your computer, you have already install or not.

        ruby -v

    If get some red color's error it means you need to install Ruby
        
    ![alt text](https://img-c.udemycdn.com/redactor/raw/2020-02-19_08-50-19-ed6e2eb5ee8c77bdc12d0e4284a4bd91.png)

    URL: https://rubyinstaller.org/


* Install (or check installation of) NodeJS and Yarn

    NodeJS

    To see if you have node already installed, pull up a PowerShell window and type in node --version followed by enter.

    URL: https://nodejs.org/en/

     ![alt text](https://img-c.udemycdn.com/redactor/raw/2020-02-19_09-17-29-43996a8c160e2be3f99fc8dc523969c6.png)

    Yarn

    To install yarn for Windows, head over to the yarn (classic) installation URL: https://classic.yarnpkg.com/en/docs/install#windows-stable

     ![alt text](https://img-c.udemycdn.com/redactor/raw/2020-02-19_09-25-00-542b1985987a57af775bd0c0af19eafc.png)

* Install and setup Git for version control

    You can check if you already have git installed pulling up a PowerShell window and typing in

        git --version 

    You can download git from downloads page: https://git-scm.com/downloads and select Windows from the options.

    Once installed, you can re-start the PowerShell window and check for git --version or git config --list and you should get an output similar to the one below.

    ![alt text](https://img-c.udemycdn.com/redactor/raw/2020-02-19_09-48-19-aa34c4cb49ef6f2dc7b3fff0e9c83b8e.png)

    First time setup only, you'll need to add two additional variables which are user.name and user.email.

    ![alt text](https://img-c.udemycdn.com/redactor/raw/2020-02-19_09-57-26-19a97907ec6375debac943fbe15850f3.png)

* Install Ruby on Rails 6

        gem list bundler

    It should result in the output below:

    ![alt text](https://img-c.udemycdn.com/redactor/raw/2020-02-19_10-44-45-1d0cda6665349560afcbf621c23bb6a3.png)

    Alternatively, you can install bundler (if you don't already have it) by using gem install bundler command as shown below:    

        gem install bundler

    Now that we know about gems, let's download and install the sqlite3 gem. Sqlite is a lightweight database which Rails applications use by default during development. The ruby packaged version of this is called the sqlite3 gem. You can download this gem by using the command (gem install sqlite3) as shown below.

        gem install sqlite3

     Install the webpacker gem. The webpacker gem makes webpack available for use for our Rails applications.

        gem install webpacker

    Using the process we practiced above, let's use the gem install command to install the latest version of Rails as shown below followed by enter.

        gem install rails

* Download all files 

    ![alt text](https://sites.northwestern.edu/researchcomputing/files/2021/05/github.png)

    Enter directory where you downloaded and do unzip.

        cd directory_name

    Now run the server with default ip

        rails server -p 8080

    And you get page looks like shown on below picture

    ![alt text](https://img-c.udemycdn.com/redactor/raw/2020-02-19_11-10-15-94bdaa3b025a04bfa23f24c9a1acbc6f.png)