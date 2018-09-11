# SUTD DevBox (Apollo/Artemis)

## User Guide

For now, please refer to the briefing slides:

[Link to briefing slides](https://docs.google.com/presentation/d/15b_r9AnETZ2Odiwv6FiapjR7DOePb3nIDLEFtr1kaRs/edit?usp=sharing)

[Jupyter Notebook User Guide](jupyter.md)

Special notes regarding resource allocation:

* Server QoS is `Burstable`, meaning your notebook server will be allowed to exceed RAM allocation if the system allows. However, if there is a lack of extra RAM, your notebook server will be killed
* GPU will never be shared between notebook servers

## Quick Links (School Network Only)

* Artemis: [JupyterHub](http://10.12.97.79:30001/hub/login)
* Apollo: [JupyterHub](http://10.12.97.79:30002/hub/login)

If you are unable to spin up a server on one of the nodes, please use the other. You may check usage on the dashboard to see if one node has less users.

* [Usage Dashboard](http://10.12.97.79:30009/d/BbkYN82mz/devbox-dashboard)

## Additional Information

**Network speed**

Network speed may be slower than you might expect. This is expected behavior on the school network.

**Storage**

We do not guarentee the long-term integrity of your files stored on Apollo and Artemis. As this project is still in pilot/POC phase, we plan to make major changes to the storage solution in the future. Where your files may be affected, we will aim to inform you in advance.

**Software stack**

* [Kubernetes](https://kubernetes.io/)
* [Kubeflow](https://www.kubeflow.org/)
* [JupyterHub](https://github.com/jupyterhub/jupyterhub) - Multi-user Jupyter Notebook server

Hardware: [NVIDIA DIGITS DevBox](https://developer.nvidia.com/devbox)