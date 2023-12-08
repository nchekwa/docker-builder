# docker-builder
Docker Builder Script which allows quick build of docker-container

```bash
wget https://raw.githubusercontent.com/nchekwa/docker-builder/main/docker-builder
```
<br>

```bash
***
*** Built docker container based on Docerfile and predefined variables
***
*** Syntax: ./docker-builder  [-f] [-s] [-d] [-l] [-h|-v] 
    options:
      -f     Force build without prompting, even if an identical image already exists in the repository.
      -s     Save the image to tar.gz file.
      -d     If the file './docker-compose.yml' exists - try to restart service 'net-ez'
      -v     Print software version and exit.
      -l     Disable cache and log all output to the docker-builder.log file
      -h     Print this Help.
```
