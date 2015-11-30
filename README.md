# build opensip with docker container

- docker build --rm -t rpmtoolchain:latest -f ./Dockerfile.rpm  .
- docker build --rm -t opensips-build:latest -f ./Dockerfile.dep  .

*tips: import your source dir with onbuild triger*
