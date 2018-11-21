[![](https://dockerbuildbadges.quelltext.eu/status.svg?organization=fhuegli&repository=shellinabox)](https://hub.docker.com/r/fhuegli/shellinabox/builds/)

# docker-shellinabox
shellinabox for docker based on alpine linux https://hub.docker.com/r/fhuegli/shellinabox/

## Configuration
### Available Environment Variables

 - **SIAB_USERCSS**: String of configured and enabled css extensions. Defaults to system default list.
 - **SIAB_PORT** The port where shellinabox should listen to. Defaults to 4200.
 - **SIAB_ADDUSER** Whether to create a default user. Defaults to true.
 - **SIAB_USER** The name of the user. Defaults to guest.
 - **SIAB_USERID** The numeric ID of the user. Defaults to 1000.
 - **SIAB_GROUP** The primary group of the user. Defaults to guest.
 - **SIAB_GROUPID** The numeric ID of the primary group of the user. Defaults to 1000.
 - **SIAB_PASSWORD** The password of the user. Defaults to an autogenerated password, printed out on stdout.
 - **SIAB_SHELL** The shell of the user. Defaults to /bin/bash.
 - **SIAB_HOME** The home directory of the user. Defaults to /home/guest.
 - **SIAB_SUDO** Whether to allow user to sudo. Defaults to false.
 - **SIAB_SSL** Whether to enable ssl and create certificates on request. Defaults to true.
 - **SIAB_SERVICE** Service strings to use for shellinabox, separated by whitespace. Defaults to local logins */:LOGIN*.
 - **SIAB_PKGS** Packages to be installed before shellinabox starts. Defaults to none.
 - **SIAB_SCRIPT** Script to download and run before shellinabox start. SSL verification is disabled. Defaults to none.
