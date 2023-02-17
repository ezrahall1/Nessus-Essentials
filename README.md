<h1>Nessus Essentials</h1>

<h2>Description</h2>
Nessus is a remote security scanning tool, which scans a computer and raises an alert if it discovers any vulnerabilities that malicious hackers could use to gain access to any computer you have connected to a network. It does this by running over 1200 checks on a given computer, testing to see if any of these attacks could be used to break into the computer or otherwise harm it.

This project will demonstrate how to run a credential scan using Nessus Essentials and showcase what to do with the vulnerabilities found in order to make your system secure.
<br />


<h2>Services Used</h2>

- <b>Nessus Essentials</b> 

<h2>Environments Used </h2>

- <b>VMware Workstation</b>
- <b>Windows 10</b>

<h2>Program walk-through:</h2>
<H3>Step 1 - Configuring the credential scan</H3>

Once you have logged in to your VMware Workstation and Nessus Essentials. You would need to click on more>configure>credentials then enter your username and password of your VMware Workstation. Leave the options in the global credentail settings as default, clicak save.

<img src="https://i.imgur.com/h8FA0iq.png" height="80%" width="80%" alt="Image 1"/>

The next step is to click on the launch button in order to start the scan. To find out what vulnerability there are on the VMware Workstation.

<img src="https://i.imgur.com/fylrxW3.png" width="80%" alt="Image 2"/>


<H3>Step 2 - Analyzing credential scan results</H3>
These are my results from the credential scan. 
<img src="https://i.imgur.com/JTxjJSZ.png" height="80%" width="80%" alt="Image 3"/>

As you can see from the vulnerabilities tab, the results are broken down into various sections such as critical, mixed, medium and info. 

<img src="https://i.imgur.com/2fKrUaL.png" height="80%" width="80%" alt="Image 4"/>

The remediations tab provides advise on the vulnerabilities.
<img src="https://i.imgur.com/724N5JQ.png" height="80%" width="80%" alt="Image 5"/>


VPR Top Threats shows all the critical vulnerabilities
<img src="https://i.imgur.com/d6laIs9.png" height="80%" width="80%" alt="Image 6"/>


<H3>Step 3 - Remediation</H3>
Remediation is the patching or fixing of cybersecurity weaknesses that are detected in enterprise assets, networks and applications.
In this section I will explain how I fixed all the vulnerabilities found in the credential scan.
The first thing I did was remove the old version of Mozilla Firefox.
<img src="https://i.imgur.com/6qytSpg.png" height="80%" width="80%" alt="Image 7"/>


Next I ran the Windows update, to install the important updates.
<img src="https://i.imgur.com/PCnaPTP.png" height="80%" width="80%" alt="Image 8"/>


Final step is to run another credential scan to see whether those previous vulnerabilities have been fixed.
<img src="https://i.imgur.com/sjFaJ0d.png" height="80%" width="80%" alt="Image 9"/>


As you can see the vulnerabilities are lower than the previous scan and there are no critical or VPR Top Threats which means removing the old version of Mozilla Firefox and updating Windows fixed the vulnerabilities.
<img src="https://i.imgur.com/BrhPYYJ.png" height="80%" width="80%" alt="Image 10"/>

<h2>Learning Outcome</h2>
From completing this project, I understood that vulnerability management consists of continuously assessing assets in discovering vulnerabilities remediating them to an acceptable risk and then starting the process over again making sure the risk is low or at least acceptable level.

Nessus Essentials allows you to scan your personal home network with the same high-speed, in-depth assessments and agentless scanning convenience that Nessus subscribe enjoy.


</p>
