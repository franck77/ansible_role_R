#I2T_SOCLE_R

Description
=========

Install Microsoft-R on a server

Requirements
------------

Get library R and Microsoft-R Binarie and create symbolic link for the library R and the microsoft-r binarie :

`
cd I2T_SOCLE_R/files ;
ln -s <library_r_directory> library ;
ln -s <microsoft_r_engine> rengine
`

Get specific packages as "sparkling-water" or "teradata", create a directory "packages" in files and put the tar.gz in  :

`
mkdir files/packages ;
cp sparkling-water.tar.gz files/packages/ ;
cp teradata.tar.gz files/packages/ ;
`

Role Variables
--------------

You need to init this variables :

`
server_repo_url, server_mirror_repo_url, java_path_server, r_java_home
`


Dependencies
------------

You have to get the role to manage fs/lv.

Example Playbook
----------------


Author
------------------

Franck VIEIRA

