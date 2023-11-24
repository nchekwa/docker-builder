# docker-builder
Docker Builder Script which allows quick build of docker-container

```bash
***
*** Built docker container based on Docerfile and predefined variables
***
*** Syntax: ./docker-builder  [-f] [-s] [-d] [-h|-v]
    options:
      -f     Force build without prompting, even if an identical image already exists in the repository.
      -s     Save the image to tar.gz file.
      -d     If the file './docker-compose.yml' exist - try to restart service 'net-collector-ez'
      -v     Print software version and exit.
      -h     Print this Help.
```
