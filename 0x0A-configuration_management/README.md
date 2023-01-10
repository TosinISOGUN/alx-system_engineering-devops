# Configuration Management
<p align="center">
<img src="https://s3.amazonaws.com/intranet-projects-files/holbertonschool-sysadmin_devops/292/4i8il3B.gif" width="" height="" />
</p>
  
## General Requirement & Environment
<img src="https://github.com/TosinISOGUN/TosinISOGUN/blob/main/ALX.jpeg?raw=true" width="300" height="100" />

- All files will be interpreted on `Ubuntu 20.04 LTS`
- All files should end with a new line.
- A `README.md` file at the root of the folder of the project is mandatory.
- Puppet manifests must pass `puppet-lint` version 2.1.1 without any errors.
- Puppet manifests first line must be a comment explaining what the Puppet manifest is about.
- Puppet manifests files must end with the extension `.pp`
- Puppet manifests must run without error.

## Table of Contents
### [**0-create_a_file.pp**](https://github.com/TosinISOGUN/alx-system_engineering-devops/blob/master/0x0A-configuration_management/0-create_a_file.pp)
Using Puppet, create a file in `/tmp`.
- Requirements:

  - File path is `/tmp/school`
  - File permission is `0744`
  - File owner is `www-data`
  - File group is `www-data`
  - File contains `I love Puppet`

### [**1-install_a_package.pp**](https://github.com/TosinISOGUN/alx-system_engineering-devops/blob/master/0x0A-configuration_management/1-install_a_package.pp)
Using Puppet, install flask from `pip3`
- Requirement
  
  - Install `flask`
  - Version must be `2.1.0`

### [**2-execute_a_command.pp**](https://github.com/TosinISOGUN/alx-system_engineering-devops/blob/master/0x0A-configuration_management/2-execute_a_command.pp)
Using Puppet, create a manifest that kills a process named `killmenow`
- Requirement
  
  - Must use the `exec` Puppet resource.
  - Must use `pkill`

## Authors
- Oluwatomisin Isogun
