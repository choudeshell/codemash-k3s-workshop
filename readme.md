# K3s - Half the Size, Twice as Awesome: Lightweight Kubernetes

## This workshop is **hands on**. Let's learn together!


Are you ready to conquer the Kubernetes learning curve without the pain?

Embarking on a Kubernetes journey can be intimidating. Many have endured the steep initial challenges only to find the eventual rewards. But what if we told you there's a way to make that initial climb smoother? What if you could dive in, gain hands-on experience, and build a production-ready Kubernetes environment without the typical complexity?

Introducing K3s – the lightweight Kubernetes distribution that's set to revolutionize your Kubernetes experience.

Join us in this immersive workshop, where we'll not only dip our toes into Kubernetes but also emerge with a fully-fledged, production-ready Kubernetes instance. It's time to unlock the power of Kubernetes without the usual hurdles. Let's make Kubernetes accessible and enjoyable for all. Don't miss out on this opportunity to revolutionize your Kubernetes journey with K3s!

## Level

This workshop is intended for beginner (introductory and overview) skill levels. This workshop will be slow paced to ensure that attendees are successful in:

- Creating their own production-ready Kubernetes instance
- Understanding basic of Kubernetes
- Kubernetes tooling, command line and debugging

**The primary goal of this workshop is to demonstrate that Kubernetes is approachable and is for all of us.**

 We will focus on using GUI tools to operate our single instance of Kubernetes. While we will dip into the command line, a majority of the workshop will focus on the GUI tooling.

 ## Schedule
**Session: Tuesday, Jan. 11, 1:00 PM - 5:00 PM**
- 50 minutes: Getting started and slides.
- 50 minutes: We do. Let's learn through examples.
- 50 minutes: We do. Let's learn through more examples.
- 50 minutes: You do. Learn through exercises.

## Prerequisites

### OS

This workshop will focus on using a distribution of Kubernetes called k3s. The prerequisites depend on what OS you are running. 

You can either run k3s in virtual machine running Linux or you can install Docker. In the case of Docker, we will be using K3d to handle creation of the environment. 

**Windows 11**
- WSL (Windows Subsystem for Linux) (https://learn.microsoft.com/en-us/windows/wsl/install)
- Or install Docker

**Intel Mac**
- Please create an Ubuntu 23.04 or Ubuntu 23.10 VM using either:
    - VMware Fusion (https://customerconnect.vmware.com/web/vmware/evalcenter?p=fusion-player-personal)
    - Parallels (https://www.parallels.com/)
    - VirtualBox (https://www.virtualbox.org/wiki/Downloads)
- Or install Docker

**M1 Mac**
- Please create an Ubuntu 23.04 or Ubuntu 23.10 VM using either:
    - VMware Fusion (https://customerconnect.vmware.com/web/vmware/evalcenter?p=fusion-player-personal)
    - Parallels (https://www.parallels.com/)
    - VirtualBox (https://www.virtualbox.org/wiki/Downloads)
- Or install Docker

**Cloud Providers**

If you are unable to meet the hardware requirements, you may sign-up for a cloud compute provider. 

- [Vultr](https://www.vultr.com/coupons/) Try Vultr for free with $250 free credit. New customers only. **CLOUD250FREE**
- [DigitalOcean](https://try.digitalocean.com/freetrialoffer/)


### Lens (Kubernetes IDE)

We will be exploring k3s/Kubernetes via an IDE called [OpenLens](https://github.com/MuhammedKalkan/OpenLens)

### HTTP Client

We will be issuing HTTP requests throughout the workshop. One of two HTTP clients should be installed. **Please note that Fiddler is not recommend. We will be modifying host headers. This is difficult and error prone with Fiddler**

* Postman - https://www.postman.com/downloads/ (Supported on Windows, Intel Mac, M1 Mac, Linux)

* Insomnia - https://insomnia.rest/products/insomnia (Supported on Windows, Intel Mac, M1 Mac, Linux)




