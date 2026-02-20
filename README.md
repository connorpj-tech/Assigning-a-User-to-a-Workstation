# Assigning a User to a Workstation

<h2>Description</h2>

This SOP will describe the process of signing into an Active Directory server with an already joined workstation and newly created user

<h2>Utilities Used</h2

- <b> Microsoft Azure</b>
- <b> Microsoft Windows 11 Pro Edition</b>
- <b> Remina(RDP client)</b>
- <b> Microsoft Server 2025</b>
- <b> Active Directory</b>

<h2>Key Steps:</h2>

**1. Validate Newly Created User**

- <b> On Windows Server, open Active Directory Users and Computers</b>
- <b> Verify User is created and enabled</b>
<div align="left">
  <table>
    <tr>
      <td><img width="400" src="https://github.com/connorpj-tech/Assigning-a-User-to-a-Workstation/blob/main/Active%20Directory%20Users%20and%20Computers.png" /></td>
      <td><img width="400" src="https://github.com/connorpj-tech/Assigning-a-User-to-a-Workstation/blob/main/Users.png" /></td>
    </tr>
       <td align="center"><b>Active Directory Users and Computers</b></td>
       <td align="center"><b>Users</b></td>
       </tr>
  </table>
</div>

**2. Setup User on Workstation**

- <b> Login with the default admin account in Azure</b>
- <b> Right click on Windows icon and select computer management</b>
- <b> Under local users and groups, select groups and click on Remote Desktop Users</b>
- <b> Type in the name of the new user in the text box and click check names.  Use users credentials when prompted</b>
- <b> User will show up as added.  Click okay and logout of Admin account</b>
<div align="left">
  <table>
    <tr>
      <td><img width="400" src="https://github.com/connorpj-tech/Assigning-a-User-to-a-Workstation/blob/main/Remote%20Desktop%20Users.png" /></td>
      <td><img width="400" src="https://github.com/connorpj-tech/Assigning-a-User-to-a-Workstation/blob/main/Users.png" /></td>
      <td><img width="400" src="https://github.com/connorpj-tech/Assigning-a-User-to-a-Workstation/blob/main/User%20Credentials.png" /></td>
      <td><img width="400" src="https://github.com/connorpj-tech/Assigning-a-User-to-a-Workstation/blob/main/User%20Added.png" /></td>
    </tr>
       <td align="center"><b>Remote Desktop Users</b></td>
       <td align="center"><b>Users</b></td>
       <td align="center"><b>Adding User</b>
       <td align="center"><b>User Added</b>
       </tr>
  </table>
</div>

**3. Login with User Credentials**

- <b> Open RDP client (Remina)</b>
- <b> Replace default Admin credentials with the new user
- <b> Save and connect</b>
- <b> User's name will appear while workstation is opening</b>
<div align="left">
  <table>
    <tr>
      <td><img width="400" src="https://github.com/connorpj-tech/Assigning-a-User-to-a-Workstation/blob/main/Login%20as%20User.png" /></td>
      <td><img width="400" src="https://github.com/connorpj-tech/Assigning-a-User-to-a-Workstation/blob/main/Succesful%20Login.png" /></td>
    </tr>
       <td align="center"><b>Login as User</b></td>
       <td align="center"><b>Succesful Login</b></td>
       </tr>
  </table>
</div>

**4. Verify User is logged into domain**

- <b> Open the command line by typing cmd into the search bar</b>
- <b> Run whoami and ipconfig /all commands
- <b> Verify IP address, user name, and domain are correct</b>
<div align="left">
  <table>
    <tr>
      <td><img width="400" src="https://github.com/connorpj-tech/Assigning-a-User-to-a-Workstation/blob/main/Verify.png" /></td>
    </tr>
      <td align="center"><b>Verify Workstation</b>
      </tr>
  </table>
</div>
