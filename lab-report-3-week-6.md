# Lab report 3

* ## Streamlining ssh configuration

    ###  Thess are the screenshots about `.ssh/config` file

    ![.ssh](lab_report3_1_2.png) 
    
    ![.ssh](lab_report3_1_1.png)

    ###  Use `ssh` command logging into my account

    ![.ssh](lab_report3_1_3.png) 

    ###  Use `scp` command copying a file to my account using alias I choose

    ![.ssh](lab_report3_1_4.png)

---

* ## Setup github access from ieng6

    ###  Location of public key on Github and public key and private key in my user account

    ![.ssh](lab_report3_1_1.png)

    ###  Run `git` command to commit and push a change to Github while logged into ieng6 account

    ![.ssh](lab_report3_2_1.png)

    ![.ssh](lab_report3_2_2.png)

    [link to the commit](https://github.com/FatCaToops/test/commit/4aed2ba23a972867131515d9fa633f68a575ce10)

---

* ## Copy whole directories with `scp -r`

    ###  Copy markdown-parse directory to ieng6 account

    ![3](lab_report3_3_1.png)

    ###  Run the test

    ![3](lab_report3_3_2.png)

    ###  Use only one command to do `scp`, `ssh`, and runing the tests command

    If I get `error: cannot find symbol Path.of()` in the terminal, I have to remove `*.class` file in the folders and replace `javac` with `/software/CSE/oracle-java-17/jdk-17.0.1/bin/javac` and `java` with `/software/CSE/oracle-java-17/jdk-17.0.1/bin/java` 

    ![3](lab_report3_3_3.png)

    ![3](lab_report3_3_4.png)
