Terdapat tiga arsitektur sistem, yaitu Tersentralisasi, Terdesentralisasi, dan Terdistribusi


Kubernetes (κυβερνήτες / kubernḗtēs) is ancient greek for
- Pilot (the person who operates the flying controls of an aircraft.)
- Helmsman (the person who stir a ship or boat, root of the word "Governor")
- Governor (a person who is the official head of a country or region)

------------------------------------------------------------------------------------------------------------------------------------------

Book: Kubernetes in Action

Google developed an internal system called Borg (and later a new
system called Omega), that helped both application developers and system administrators manage those thousands of applications and services.

After having kept Borg and Omega secret for a whole decade, in 2014 Google
introduced Kubernetes

------------------------------------------------------------------------------------------------------------------------------------------

Book: Kubernetes Up and Running (2019)

Kubernetes is an open source orchestrator for deploying containerized applications. It was originally developed by Google, inspired by a decade of experience deploying scalable, reliable systems in containers via application-oriented APIs.

Since its introduction in 2014, Kubernetes has grown to be one of the largest and most popular open source projects in the world. It has become the standard API for building cloud-native applications, present in nearly every public cloud. Kubernetes is a proven infrastructure for distributed systems that is suitable for cloud-native developers of all scales, from a cluster of Raspberry Pi computers to a warehouse full of the latest machines. It provides the software necessary to successfully build and deploy reliable, scalable distributed systems.

------------------------------------------------------------------------------------------------------------------------------------------
Book: Cloud Native Devops with Kubernetes full book

Kubernetes
Google was running containers at scale for production workloads long before anyone
else. Nearly all of Google’s services run in containers: Gmail, Google Search, Google
Maps, Google App Engine, and so on. Because no suitable container orchestration
system existed at the time, Google was compelled to invent one.


From Borg to Kubernetes

To solve the problem of running a large number of services at global scale on millions of servers, Google developed a private, internal container orchestration system it called Borg. Borg is essentially a centralized management system that allocates and schedules con‐
tainers to run on a pool of servers. While very powerful, Borg is tightly coupled to
Google’s own internal and proprietary technologies, difficult to extend, and impossi‐
ble to release to the public.
In 2014, Google founded an open source project named Kubernetes (from the Greek
word κυβερνήτης, meaning “helmsman, pilot”) that would develop a container
orchestrator that everyone could use, based on the lessons learned from Borg and its
successor, Omega.
Kubernetes’s rise was meteoric. While other container orchestration systems existed
before Kubernetes, they were commercial products tied to a vendor, and that was
always a barrier to their widespread adoption. With the advent of a truly free and
open source container orchestrator, adoption of both containers and Kubernetes grew
at a phenomenal rate.
By late 2017, the orchestration wars were over, and Kubernetes had won. While other
systems are still in use, from now on companies looking to move their infrastructure
to containers only need to target one platform: Kubernetes.

https://blog.risingstack.com/the-history-of-kubernetes/#:~:text=Google%20introduced%20the%20Borg%20System%20around%202003%2D2004.&text=Borg%20was%20a%20large%2Dscale,tens%20of%20thousands%20of%20machines.

------------------------------------------------------------------------------------------------------------------------------------------


