# Assigning a User to a Workstation

<h2>Description</h2>

This SOP will describe the process of signing into an Active Directory server with an already joined workstation and newly created user

<h2>Utilities Used</h2

-<b> Microsoft Azure</b>
-<b> Microsoft Windows 11 Pro Edition</b>
-<b> Remina(RDP client)</b>
-<b> Microsoft Server 2025</b>
-<b> Active Directory</b>

<h2>Key Steps:</h2>

**1. Validate Newly Created User**

-<b> On Windows Server, open Active Directory Users and Computers</b>
-<b> Verify User is created and enabled</b>

**2. Setup User on Workstation**

-<b> Login with the default admin account in Azure</b>
-<b> Right click on Windows icon and select computer management</b>
-<b> Under local users and groups, select groups and click on Remote Desktop Users</b>
-<b> Type in the name of the new user.  Use users credentials when prompted</b>
-<b> User will show up as added.  Click okay and logout of Admin account</b>

**3. Login with User Credentials**

-<b> Open RDP client (Remina)</b>
-<b> Replace default Admin credentials with the new user
-<b> Save and connect</b>
-<b> User's name will appear while workstation is opening</b>

**4. Verify User is logged into domain**

-<b> Open the command line by typing cmd into the search bar</b>
-<b> Run whoami and ipconfig /all commands
-<b> Verify IP address, user name, and domain are correct</b>
