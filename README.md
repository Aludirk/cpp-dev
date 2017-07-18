# C++ Development Docker Image

This is the Git repo of the Docker image for C++ development.  See the [Docker Hub page](https://hub.docker.com/r/aludirk/cpp-dev) for more details.

It uses [GCC](https://hub.docker.com/_/gcc/) as base image, and contains:
- [GDB](https://www.gnu.org/software/gdb/)
- [Cppcheck](https://github.com/danmar/cppcheck)
- [CppUnit](https://www.freedesktop.org/wiki/Software/cppunit/)

## Tags

- `4` ([4/Dockerfile](4/Dockerfile))
- `5` ([5/Dockerfile](5/Dockerfile))
- `6` ([6/Dockerfile](6/Dockerfile))
- `7`, `latest` ([7/Dockerfile](7/Dockerfile))

## GDB

To run GDB within a docker container, you need to add `--security-opt seccomp=unconfined` to the `docker run`.  See [Stack Overflow](https://stackoverflow.com/questions/35860527/warning-error-disabling-address-space-randomization-operation-not-permitted#comment62818827_35860527)

## License

This software is licensed under the [GNU GPL v3 license](https://www.gnu.org/copyleft/gpl.html). © 2017 Aludirk Wong
