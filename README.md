# initsng-web-automation

Tools Used

Selenium WebDriver
Java
Apache maven
Chrome Driver v88.0.4324.27
Chrome browser v88

Test(s) added in the framework are

1. VerifyServiceTest
2. VerifyContactUsTest
3. VerifyJoinTeamTest
4. VerifyAboutTest


Steps to setup and run project framework Note. This framework runs test(s) in parallel

Download and install Java

Download and install Apache Maven

Download Initsng project from https://github.com/edyusanga/initsng-web-automation.git
Unzip Initsng project
Open project with any IDE of your choice. preferably IntelliJ or Eclipse IDE

Import Maven Dependencies. Maven depency is already added to the POM file

Update sources and target in maven-compiler-pluggin in the POM file to the java version on your system

Run "chmod +x chromedriver" on CMD/Terminal to make chrome driver executable. Here is the path to run cammand /Users/PCname/Documents/initsng-task/src/main/resources

Run test using testng.xml file.
