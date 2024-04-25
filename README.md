# Before you run docker compose

**IMPORTANT:** You will have to provide the installation binaries of Oracle Database (except for Oracle Database 18c XE, 21c XE and 23c FREE) and put them into the `oracledb-<version>` folder.
You only need to provide the binaries for the edition you are going to install. The binaries can be downloaded from the [Oracle Technology Network](http://www.oracle.com/technetwork/database/enterprise-edition/downloads/index.html), make sure you use the linux link: *Linux x86-64*. The needed file is named *linuxx64_\<version\>_database.zip*.

**Linux ARM64 Support:** Oracle Database 19c Enterprise Edition is now supported on ARM64 platforms. You will have to provide the installation binaries of [Oracle Database 19c](https://www.oracle.com/database/technologies/oracle19c-linux-arm64-downloads.html) and put them into the dockerfiles/19.3.0 folder. The needed file is named *LINUX.ARM64_1919000_db_home.zip*.
