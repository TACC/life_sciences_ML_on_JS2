Introduction to Jetstream2
==========================


Note: This page was generated from a PowerPoint file. Formatting has been simplified.


Introduction to Jetstream2
--------------------------


- Introduction to Jetstream2
- Any opinions, findings, conclusions, or recommendations expressed in this material are those of the author(s) and do not necessarily reflect the views of the University of Hawaiʻi.
.. image:: images/jetstream2_intro/slide1_img1.png
   :align: center
   :width: 800px


Before We Begin
---------------


- Before We Begin
- Those who wish to participate in the tutorial - If you have not done so already:
- Create your ACCESS ID and share it in the chat.

Agenda
------


- Agenda
- Introduction to Jetstream2
- What is Jetstream2?
- Features
- Use Cases
- Interfaces
- Limitations
- ACCESS Allocations
- Logging into Exosphere
- Demo
- Tutorial
- Using Exosphere
  - Creating and accessing your instance
  - Software
  - Volume/storage management
  - Transferring data to and from your instance
  - Saving and sharing images
  - Instance management best practices

What is Jetstream2?
-------------------


- What is Jetstream2?
- Jetstream2 is a high-performance cloud computing environment which provides resources to researchers and educators across the US through the National Science Foundation (NSF)-funded Advanced Cyberinfrastructure Coordination Ecosystem: Services & Support (ACCESS) program. Jetstream2 is designed to be user-friendly and accessible to both advanced users and those who have had little to no experience with high-performance computing (HPC) resources. Jetstream2 is run by the Pervasive Technology Institute at Indiana University.
.. image:: images/jetstream2_intro/slide4_img1.png
   :align: center
   :width: 800px

.. image:: images/jetstream2_intro/slide4_img2.png
   :align: center
   :width: 800px

.. image:: images/jetstream2_intro/slide4_img3.png
   :align: center
   :width: 800px


Regional Partners
-----------------


- Regional Partners
.. image:: images/jetstream2_intro/slide5_img1.png
   :align: center
   :width: 800px


Features
--------


- Features
- Create and administer your own virtual machines
  - Install and configure software
  - Control via web shell, virtual desktop, or through SSH
- On-demand resources, no queues or runtime limits
- Internet access with persistent IPs, ideal for web hosting or gateways
- Resources are available at no cost to end users thanks to support from the NSF

Specifications
--------------


- Specifications
- 8 petaFLOPS cloud computing system, 17.2 petabytes of storage
- Compute: 384 nodes AMD EPYC CPUs with 128 cores + 512gb RAM
- GPU:
  - 90 nodes, 4 NVIDIA A100 40gb
  - *24 nodes 2 NVIDIA H100 80GB
  - *8 nodes 4 NVIDIA L40S 48GB
- Large Memory: 32 nodes, up to 1TB of RAM
- NVMe default VM root disks and storage
- CEPH storage for additional storage volumes that can be mounted on a VM
- *require request or special allocations

Jetstream2 Resource Types
-------------------------


- Jetstream2 Resource Types
- CPU: 1 CPU core, 3 GB RAM up to 64 CPU cores, 250 GB RAM*
- Large Memory: Up to 128 CPU cores, 1000 GB RAM
  - Double the RAM of equivalent CPU instances
- GPU: From 8 GB VRAM, 3 CPU cores, 15 GB RAM partial GPU up to a fullNVIDIA GPU, 32 CPU cores, 125 GB RAM
- Storage: 1 TB default for volumes, more on request
- * Default CPU instances capped at 64 CPU cores. 128 CPU cores,500 GB available by request and with proper justification.

Use Cases
---------


- Use Cases
- Teaching a course
  - Give students access to powerful computing for high-performance analysis
  - Individual virtual machines for practicing network security and reproducible development environments
- Working with code
  - Write, debug, and execute with interactive GUI applications
  - Use GPUs to train and refine ML/LLMs
- Long running services
  - Databases
  - Web applications - science gateway
  - Inference services
- Sharing with lab, students and colleagues
  - Host a file server or database
  - Receive, store, and serve data
  - Shared Environment (all dependencies etc)

Use Case: Hawaiʻi Climate Data Portal (HCDP)
--------------------------------------------


- Use Case: Hawaiʻi Climate Data Portal (HCDP)
- HCDP Allows users to visualize and download decades’ worth of climate data
.. image:: images/jetstream2_intro/slide10_img1.png
   :align: center
   :width: 800px


Jetstream2 Interfaces: Exosphere
--------------------------------


- Jetstream2 Interfaces: Exosphere
- Primary interface, most user-friendly
- Accessible via Guacamole web shell, graphical virtual desktop (optional), SSH
- Most limited
- Focus of tutorial
.. image:: images/jetstream2_intro/slide11_img1.png
   :align: center
   :width: 800px

- Exosphere Web App

Jetstream2 Interfaces: Horizon
------------------------------


- Jetstream2 Interfaces: Horizon
- For advanced users, more tools, default OpenStack dashboard
- Most complete UI, but not as user-friendly
- Supports almost all functionality of the OpenStack API as the command line interface
.. image:: images/jetstream2_intro/slide12_img1.png
   :align: center
   :width: 800px

- Horizon Login

Jetstream2 Interfaces: CACAO
----------------------------


- Jetstream2 Interfaces: CACAO
- For advanced users, useful for building clusters or JupyterHub
- In Alpha
.. image:: images/jetstream2_intro/slide13_img1.png
   :align: center
   :width: 800px

- CACAO Login

Limitations, Caveats, and Responsibilities
------------------------------------------


- Limitations, Caveats, and Responsibilities
- Research or education use only
  - No hosting personal or commercial websites
- Jetstream2 is not primarily a storage/archival service
  - Do you have a plan for your data if your allocation does not get renewed?
- Data protected by HIPAA, FERPA, ITAR and other federal or security or privacy laws, as well as classified information, is not currently permitted to be stored on Jetstream2.
- Users are responsible for administrating their own VMs
  - Jetstream2 Security FAQ
- Windows images are not officially supported

Appendix D: Acronyms
--------------------


- Appendix D: Acronyms
- NSF - National Science Foundation
- ACCESS - Advanced Cyberinfrastructure Coordination Ecosystem: Services & Support
- NAIRR Pilot - National Artificial Intelligence Research Resource Pilot
- HPC - High-Performance Computing
- VM - Virtual Machine
- EPSCoR - Established Program to Stimulate Competitive Research
- LLM - Large Language Model
- HIPAA - Health Insurance Portability and Accountability Act
- FERPA - Family Educational Rights and Privacy Act
- ITAR - International Traffic Arms and Regulations Act
- IU - Indiana University
