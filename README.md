# Supercomputing @ SUTD
Supercomputing resources at SUTD - [**computing.sutd.edu.sg**](https://computing.sutd.edu.sg/)

**JupyterHub** - User Friendly GPU Compute

* JupyterHub nodes: [Apollo](http://10.12.97.79:30002/hub/login) and [Artemis](http://10.12.97.79:30001/hub/login)
* JupyterHub [Usage Dashboard](http://10.12.97.79:30009/d/BbkYN82mz/devbox-dashboard)
* [User Guide](devbox.md)
* [Jupyter Notebook User Guide](jupyter.md)

**Hermes** - HPC Cloud Service

* [Hermes User Guide](https://computing.sutd.edu.sg/resources/hermes/hermes-user-guide/)
* [CloudStack Login](https://hermes.sutd.edu.sg/client/)

## User Guides

**GPU Compute**

1. [Artemis/Apollo](devbox.md)
2. [Athena](athena.md)

**Using Docker**

1. [Basic Docker Guide](dockerguide.md)
2. [Advanced Docker Guide](advdockerguide.md)


## Frequently Asked Questions

### Apollo/Artemis

1. What is the difference between Athena and Apollo/Artemis

On Apollo/Artemis you get a user-friendly interface to spawn Jupyter Notebook for you to run iterative experiments on consumer-grade GPUs. This is recommended for beginners.

On Athena (DGX-1) you can run heavier workloads, but you need to be comfortable with the command line and Docker.

2. Who is Jovyan??

[Official answer](https://en.wikipedia.org/wiki/Jovian_(fiction))

### Athena

1. Can I `sudo apt-get`?

You are allowed to `sudo apt-get` if you are within your **own** container. Please
do not use the `sudo` command outside of your **own** container.

2. I can't find my container? Did someone remove it?

Please be advised that when launching your container from an image the first
time, please name your container, e.g. `user_pycuda` so you are able to find
your containers easily using the `nvidia-docker ps -a | grep user`.

### Network Access

You need to be connected to the SUTD network to access any compute resources. If you are outside school, you may use the official school VPN.

To be able to use VPN, download the VPN from [SUTD Downloads](https://downloads.sutd.edu.sg/cgi-bin/). Install then sign in to SecurePulse to get connected to VPN.