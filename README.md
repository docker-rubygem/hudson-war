[![Docker pulls](https://img.shields.io/docker/pulls/rubygem/hudson-war.svg)](https://hub.docker.com/r/rubygem/hudson-war/)
[![Docker Build](https://img.shields.io/docker/automated/rubygem/hudson-war.svg)](https://hub.docker.com/r/rubygem/hudson-war/)
[![Latest Tag](https://img.shields.io/github/tag/docker-rubygem/hudson-war.svg)](https://hub.docker.com/r/rubygem/hudson-war/)
[![Gem Downloads](https://img.shields.io/gem/dt/hudson-war.svg)](https://rubygems.org/gems/hudson-war/)
# hudson-war

Auto-Generated Docker image for hudson-war to allow simple usage without installation.
It is in sync with the original gem.

This allows to use a specific version of your favorite gem and ensures that this image will be supported in future.
The image is generated automatically from a github repository by Docker Hub.
This ensures that you exactly know what is in the image and what not.

It lets you use Ruby Tools without the need to install ruby on your machine.

## Usage

Usage via file system:

`docker run -v $(pwd):/work -ti docker-gems/hudson-war`

Usage via Pipe:

`echo "test" | docker run -ti docker-gems/hudson-war`

It depends on your specific use case how your want to use it.

### Add Customization

For extension, it could be used as base image.

So instead of struggeling with the installation of a gem, just write

`FROM docker-gems/hudson-war`

Then add the customization.

## References

 - [Overview over other rubygem docker images](https://github.com/thinkbot/docker-rubygem)
 - [Gem](https://rubygems.org/gems/hudson-war/)
