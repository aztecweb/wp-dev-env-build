# Docker wp-dev-env build

A Docker image to build a wp-dev-env project.

To run the build, execute the following command in the project root

	$ docker run -it -v $(pwd):/data aztecweb/wp-dev-env-build

The build files will be generated in the `build` directory.

