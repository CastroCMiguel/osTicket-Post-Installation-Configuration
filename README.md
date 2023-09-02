<p align="center">
<img src="https://i.imgur.com/SIOPg5j.png" alt="1"/>
</p>

<h1>osTicket - Post-Install Configurations</h1>

This lab illustrates the essential configurations I make to set up osTicket as a fully functional ticketing system.

<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop Connection
- osTicket 

<h2>Operating Systems Used </h2>

- Windows 10 Pro</b> (21H2)

<h2>Video Demonstration</h2>

- ### [YouTube: How To Configure osTicket, post-installation](https://www.youtube.com/watch?v=lWiNyIz2jj0)

<h2>Configuration Steps</h2>

<p align="center">
<img src="https://i.imgur.com/Hf4x7qv.png" alt="1"/>
</p>

<p align="center">
<img src="https://i.imgur.com/1gv3Nwf.png" alt="1"/>
</p>

After the installation of osTicket, it's time to implement configurations to transform it into an effective ticketing system. It's worth noting that I switch between the Admin and Agent panels as each panel has distinct configurations. To determine which panel is currently in use, simply check the top right corner of the osTicket screen. If it reads "Agent Panel," then the Admin panel is active, and vice versa.

The initial step is to create a new role named "Super Admin." It's important to note that, for the purposes of this lab, this role will be granted all possible permissions intentionally. To create this new role, follow these steps:

1. Open the Admin panel.
2. Navigate to the "Agents" menu.
3. Click on "Roles" within the menu.
4. Create the new role from this section.

<p align="center">
<img src="https://i.imgur.com/EOcbXBU.png" alt="1"/>
</p>

Next, you should create a new department specifically for System Administrators. To do this, follow these steps within the Admin panel:

1. Open the Admin panel.
2. Navigate to the "Agents" menu.
3. Click on "Departments" to create a new department within osTicket.

<p align="center">
<img src="https://i.imgur.com/K1PXMAm.png" alt="1"/>
</p>

To establish a new Level II Support Team to complement the existing Level I Support Team in osTicket, follow these steps within the Admin panel:

1. Access the Admin panel.
2. Navigate to the "Agents" menu.
3. Click on "Teams" to add any new teams that need to be created.

<p align="center">
<img src="https://i.imgur.com/fSVFBg6.png" alt="1"/>
</p>

<p align="center">
<img src="https://i.imgur.com/gLrSVYc.png" alt="1"/>
</p>

To add new agents who will handle tickets in the queue, follow these steps within the Admin panel:

1. Access the Admin panel.
2. Navigate to the "Agents" menu.
3. Click on "Add New Agent" to create the account credentials for each new agent. In this instance, you will create accounts for Jane and John Doe.

<p align="center">
<img src="https://i.imgur.com/2bNgHof.png" alt="1"/>
</p>

To add new users who can create tickets for the agents to receive and triage, follow these steps within the Agents panel:

4. Access the Agents panel.
2. Go to the "Users" menu.
3. Click on "Add User" to create the account credentials for each new user. In this case, you will create accounts for Karen and Ken.

<p align="center">
<img src="https://i.imgur.com/V47bwFa.png" alt="1"/>
</p>

To establish Service Level Agreements (SLAs) for categorizing tickets based on their impact level, follow these steps within the Admin panel:

1. Access the Admin panel.
2. Navigate to the "Manage" menu.
3. Click on "SLA" to create any required SLAs. In this case, SEV-A, SEV-B, and SEV-C have been created to categorize tickets that require resolution within 1 hour, 4 hours, and 8 hours, respectively.

<p align="center">
<img src="https://i.imgur.com/XV6JJAL.png" alt="1"/>
</p>

To create Help Topics that assist users in selecting an appropriate category to describe their problem when submitting tickets, follow these steps within the Admin panel:

1. Access the Admin panel.
2. Navigate to the "Manage" menu.
3. Click on "Help Topics" and then select "Add New Help Topic."
4. In this case, you can add topics like "Business Critical Outage," "Personal Computer Issues," "Equipment Request," and "Password Request." These topics will help streamline the ticket categorization process when creating new tickets for resolution.

Now that the configurations are in place, you can effectively utilize osTicket as a fully functional ticketing system. This enables you to create tickets and efficiently triage them as if you were operating in a real-world environment. It's a valuable tool for managing and resolving support requests and issues effectively.
