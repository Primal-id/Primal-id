### Hi there 👋

<!--
**Primal-id/UbuntuPatching_Splunk_Qemu** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->






 This script will check for updates, patch Ubuntu, install Qemu for Proxmox if necessary, install Splunk Universal Fowarder and basic configure
 
 
 Make sure you update the wget line for Splunk Universal forwarder to the needed version, edit the path to the download directory and add the IP address of your Splunk server(s). You will be prompted for username and password for the Splunk UF during the install.
 
 Run script as root 
 
 <strong><blockquote>chmod +x install.sh && ./install.sh</blockquote></strong>





