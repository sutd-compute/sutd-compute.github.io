# Supercomputing @ SUTD
Supercomputing resources at SUTD - [Main Website](https://computing.sutd.edu.sg/)

## User Guides

**GPU Compute**

1. [Athena](athena.md)
2. [Artemis/Apollo](devbox.md)

**Using Docker

1. [Basic Docker Guide](dockerguide.md)
2. [Advanced Docker Guide](advdockerguide.md)


## Frequently Asked Questions

### Usage

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