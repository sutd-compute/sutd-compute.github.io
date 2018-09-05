# Supercomputing @ SUTD
Supercomputing resources at SUTD - [Main Website](https://computing.sutd.edu.sg/)

## User Guides

**GPU Compute**

1. [Artemis/Apollo](devbox.md)
2. [Athena](athena.md)

**Using Docker**

1. [Basic Docker Guide](dockerguide.md)
2. [Advanced Docker Guide](advdockerguide.md)


## Frequently Asked Questions

### Athena

1. Can I `sudo apt-get`?

You are allowed to `sudo apt-get` if you are within your **own** container. Please
do not use the `sudo` command outside of your **own** container.

2. I can't find my container? Did someone remove it?

Please be advised that when launching your container from an image the first
time, please name your container, e.g. `user_pycuda` so you are able to find
your containers easily using the `nvidia-docker ps -a | grep user`.

### Apollo/Artemis

1. What is the difference between Athena and Apollo/Artemis

On Apollo/Artemis you get a user-friendly interface to spawn Jupyter Notebook for you to run iterative experiments on consumer-grade GPUs. This is recommended for beginners.

On Athena (DGX-1) you can run heavier workloads, but you need to be comfortable with the command line and Docker.

2. Who is Jovyan??

[Official answer](https://en.wikipedia.org/wiki/Jovian_(fiction))

### Network Access

You need to be connected to the SUTD network to access any compute resources. If you are outside school, you may use the official school VPN.

To be able to use VPN, download the VPN from [SUTD Downloads](https://downloads.sutd.edu.sg/cgi-bin/). Install then sign in to SecurePulse to get connected to VPN.