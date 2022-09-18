# 0x0A. Configuration management
## Tasks

### 0. Create a file
Using Puppet, create a file in  `/tmp`.
Requirements:
-   File path is  `/tmp/school`
-   File permission is  `0744`
-   File owner is  `www-data`
-   File group is  `www-data`
-   File contains  `I love Puppet`
-   File:  [`0-create_a_file.pp`](https://github.com/Peacebern/alx-system_engineering-devops/blob/main/0x0A-configuration_management/0-create_a_file.pp)

### 1. Install a package
Using Puppet, install  `flask`  from  `pip3`.
Requirements:
-   Install  `flask`
-   Version must be  `2.1.0`
-   File:  [`1-install_a_package.pp`](https://github.com/Peacebern/alx-system_engineering-devops/blob/main/0x0A-configuration_management/1-install_a_package.pp)

### 2. Execute a command

Using Puppet, create a manifest that kills a process named  [`killmenow`](https://github.com/Peacebern/alx-system_engineering-devops/blob/main/0x0A-configuration_management/killmenow)
Requirements:
-   Must use the  `exec`  Puppet resource
-   Must use  `pkill`
-   File:  [`2-execute_a_command.pp`](https://github.com/Peacebern/alx-system_engineering-devops/blob/main/0x0A-configuration_management/2-execute_a_command.pp)
