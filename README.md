# README SSDOP

SecureDockerDevOpsPipeline (SSDOP) is a series of demos/walkthroughs how to configure tesing and usage of Docker in an automated environment. 

Docker these days is everywhere. From single Rasberry PIs, to Pods in Kubernetes Clusters in large corporate clouds. The amount of malware/vulernability discovered with Docker also keeps on increasing at an alarming rate, with the latest Docker hitting the news earlier this week. 

Usually we see Docker on Linux distributions, but in this demo we are using a plain windows10 VM with Docker with the OpenSource Clair Vulnerability Scanner for CoreOS to scan Docker images for well known vulneabilties. We then scan a few well known images for vulnerabilities, including the latest NextCloud Docker image. We start from a plain Windows VM, and we see how can get quickly off the ground with just a few lines of Powershell. We launch CommandoVM framework from FireEye which includes Docker and various attacking tools are ported to run on Docker/Windows. It even includes a full Kali install !

As attackers/red teams are starting to beef up their game on Docker, it is even more important for Blue teams to start making sure that their Docker Images are free of malcious code.

## SSDOP Demo 1: Install Docker and various SecurityTools onto Windows

- Time to run: Approx 20min
- [Instructions](./docs/sddop_demo1_winconfig.md)

## SSDOP Demo 2: Running Clair VM inside Docker container to Scan other Docker images

- Time to run: Approx 10min
- [Instructions](./docs/sddop_demo2_clair.md)

### Docker Headlines

- ![Headlines](./docs/jpg/docker_headlines.jpg)

### References

- [BoxStarter](https://boxstarter.org)
- [Chocolatey](https://chocolatey.org/docs/installation)
- [Windows Docker Machine](https://github.com/StefanScherer/windows-docker-machine)
- [CommandoVM](https://github.com/fireeye/commando-vm)
- [SecureDockerDevOpsPipeline (SDDOP)](https://github.com/stefanwinkel/sddop)