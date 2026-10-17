# networkwalks-B083-wireshark

<h1>Wireshark Exercise b</h1>

#Step 1
dnsflush, but this assignment was done in kali linux not windows so the command may differ
in Kali linux we enter similar command "sudo systemctl restart NetworkManager" this does thesame as dnsflush in windows command prompt.

<img width="683" height="483" alt="Screenshot 2026-10-17 011216" src="https://github.com/user-attachments/assets/83a13e11-ff9e-4558-82aa-4dc09e534050" />

#Step 2
Open the wireshark and select your interface to start capturing.

#Step 3
Open a new incognito tab and search for https://networkwalks.com 
<img width="1358" height="634" alt="Screenshot 2026-10-17 011908" src="https://github.com/user-attachments/assets/23b1743a-3c48-45b1-a9b0-57ad0dd56edf" />

#Step 4
<p>After capturing the packets you might want to search/filter some specific packets by entering some specific command in the filter bar, in this case is dns.qry.name == "networkwalks.com"</p>


<img width="1364" height="566" alt="Screenshot 2026-10-17 012503" src="https://github.com/user-attachments/assets/03ec684b-9a97-4f55-a19a-742dfa27e1e5" />

<p>Answer 1. The laptop ip address is = 192.168.239.132</p>
<p>Answer 2. The DNS ip address is = 192.168.239.2</p>
<p>Answer 3. The Website ip address is = 192.232.216.135</p>

#Step 5
<p>Use this filter tls.handshake.type == 1</p>

<img width="1344" height="565" alt="Screenshot 2026-10-17 012745" src="https://github.com/user-attachments/assets/43742863-1511-4a1f-a3b8-fb79cb64c53b" />

<p>Server name is networkwalks.com

and the server port number is 443</p>

#Step 6
<p>use tls.handshake.type == 2 filter</p>

<img width="1363" height="561" alt="Screenshot 2026-10-17 013126" src="https://github.com/user-attachments/assets/f12a4a90-39db-42f8-9e38-eef462f803b4" />

<p>Answer the TLS version is TLSv1.3</p>


<h1>Wireshark Exercise c</h1>

<h3>Step 1</h3>
<p>open the .pcap file</p>

<img width="1365" height="597" alt="image" src="https://github.com/user-attachments/assets/54b34291-46bb-47f6-b2f0-0dd6fc8ddc6d" />

<h3>Step 2</h3>
<p>enter dns.qry.name == "microsoft.com" in the filter bar</p>

<p>The laptop ip is 192.168.0.105 DNS server ip is 8.8.8.8</p>

<h3>Step 3</h3>
<p>Click the standard query </p>
<img width="1365" height="578" alt="image" src="https://github.com/user-attachments/assets/bb57a8be-f865-4524-91a3-b4b883f5dfad" />

<h3>Step 4</h3>
<p>Use this filter tls.handshake.type == 1</p>
<img width="1360" height="557" alt="image" src="https://github.com/user-attachments/assets/4bdcdf13-d7d9-4818-a768-48379a08e936" />

<p>The server name is microsoft.com the port no is 443</p>

<h3>Step 5</h3>
<p>The Tls version is TLSv1.3</p>
<img width="1365" height="561" alt="image" src="https://github.com/user-attachments/assets/c699654f-ef8f-47ae-9755-70b854591063" />







