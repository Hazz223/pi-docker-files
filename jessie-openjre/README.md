# Jessie-OpenJDK 8
Dockerfile for the Open JDK 8 on Raspberry Pi. This will get the latest version of JDK8 out of the repository.

## Issues
I've found this image to be MUCH slower than the Oracle one, especially when using Spring. A simple Springboot app will take 150s with
this Image, where as the Oracle image will take 18s.
