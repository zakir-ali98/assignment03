If you know you need to install a bunch of OS packages in your image (which is typically one of the slower parts of building an image) put your package installation
instructions toward the top of the Dockerfile. That way you only need to sit through the installation process for those packages once as you go through the code/build/test/repeat
cycle for your image.
