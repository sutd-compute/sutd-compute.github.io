# SUTD DevBox (Apollo/Artemis)

## User Guide

For now, please refer to the briefing slides:

[Link to briefing slides](https://docs.google.com/presentation/d/15b_r9AnETZ2Odiwv6FiapjR7DOePb3nIDLEFtr1kaRs/edit?usp=sharing)

Special notes regarding resource allocation:

* Server QoS is `Burstable`, meaning your notebook server will be allowed to exceed RAM allocation if the system allows. However, if there is a lack of extra RAM, your notebook server will be killed
* GPU will never be shared between notebook servers

## Quick Links (School Network Only)

* Artemis: [JupyterHub](http://10.12.97.79:30001/hub/login)
* Apollo: [JupyterHub](http://10.12.97.79:30002/hub/login)

If you are unable to spin up a server on one of the nodes, please use the other. You may check usage on the dashboard to see if one node has less users.

* [Usage Dashboard](http://10.12.97.79:30009/d/BbkYN82mz/devbox-dashboard)

## Additional Information

**Software stack**

* [Kubernetes](https://kubernetes.io/)
* [Kubeflow](https://www.kubeflow.org/)
* [JupyterHub](https://github.com/jupyterhub/jupyterhub) - Multi-user Jupyter Notebook server

Hardware: [NVIDIA DIGITS DevBox](https://developer.nvidia.com/devbox)