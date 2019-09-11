# How to build and run an international open-data image repository

View online: https://downloads.openmicroscopy.org/presentations/2019/rseconuk2019-idr

Image Data Resource (IDR, https://idr.openmicroscopy.org) is a public data repository containing over 100TB of life sciences imaging data from published studies in a searchable and reusable format. It is built from existing open-source tools but significant work was required to deploy and keep it running as a production service. I will talk about the journey from our first ever use of cloud services to scaling up a single- server system into the reliable public resource that exists today, including design choices, the mistakes we made, and the challenges we still face.

I will introduce some of the tools we use including Ansible, OpenStack, and Docker, but with a focus on the benefits of reproducible deployments rather than going into too much technical detail of particular tools. All of our infrastructure is open source and I will explain why, and provide links for people interested in finding out more.

This talk will hopefully provide an insight into how a public data services like this could be set up by your institution, including many of the considerations you may not have thought of.
