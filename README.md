# DjangoCMS Container

Just a very opinionated Django CMS container base so I can have automated builds on Docker Hub.

The image is huge because Closure Compiler requires Java. I may remove that requirement later.

### URL
https://hub.docker.com/r/phistrom/djangocms/

### Pull
`docker pull phistrom/djangocms`

### Specific things
Check the requirements.txt file for all the packages this container will have.
Assumptions are made about what you will be using.
  - MySQL
  - Redis
  - Closure Compiler
  - Python 3.6
