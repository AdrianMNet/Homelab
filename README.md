# Adrian Moreno - History, Homelab, Projects
Documenting my tech journey, starting with projects for Virtualization, Active Directory, and related concepts!

# **Active Directory and Virtualization**
 - When starting my homelab, the main skills that I wanted to learn and build upon were understanding how virtualization worked and how Active Directory would function in a enterprise setting. To get started, I spun up two virtual machines, a client and a server, to mimic an environment that would be found within a standard business. When creating the virtual machines, it taught me how the basics of virtualization work and how to properly manage them within your host device.
 For Active Directory, I started by creating a client VM and joining it to my domain that I had created on the Windows Server (homelab.local)
- ![Creation of the VM and joining to the domain](/docs/assets/Homelab1.png)

- I then created OUs to separate the "departments" within my domain, and created users to add to their respective departments. I edited their privileges, assigned passwords, and managed the Group Policy Objects for each department
- ![Managing user vwembanyama](/docs/assets/Homelab2.png)

- I also ensured that certain departments had access to the necessary files within the company's file server.
- ![Description of the image](/docs/assets/Homelab2.png)

- There are still many concepts and skills that I want to practice and learn but I believe this was a great entry point into understanding the foundations of Active Directory and Virtualization!
