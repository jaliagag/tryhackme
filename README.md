# TryHackMe

Content Management Systems (such as Wordpress, FuelCMS, Ghost, etc)

- (ExploitDB)[https://www.exploit-db.com/]
- (NVD)[https://nvd.nist.gov/vuln/search]
- (CVE Mitre)[https://cve.mitre.org/]

If you're inclined towards the CLI on Linux, Kali comes pre-installed with a tool called "searchsploit" which allows you to search ExploitDB from your own machine. This is offline, and works using a downloaded version of the database, meaning that you already have all of the exploits already on your Kali Linux!

`searchsploit fuel cms`

shiba1:shiba1
shiba2:pinguftw
shiba3:happynootnoises
shiba4:test1234

- <https://tryhackme.com/room/bpsplunk>
- <https://tryhackme.com/room/bpvolatility>

| layer| OSI | Description |
| ---- | ----| ----- |
| 7 | application | networking options to programs - interface for apps to use in order to transmit data - data is passed down to the presentation layer |
| 6 | presentation | translates the data into a standardised format - handles encryption, compression or other transformations data is passed to the session layer|
| 5 | session | it looks to see if it can set up a connection with the other computer across the network - this layer maintains the session - cooperate with the session layer of the remote computer in order to synchronise communications. the session is unique to the communication in question|
| 4 | transport | choose the prototol over which the data is to be transmitted, most commonly TCP (connection based, a connection between the computers is established and maintained for the duration of the request - ensures that _all_ the packets get to the right place - any data loss is re-sent) or UDP (speed). with a protocol selected, the transport layer then divides the transmission up into bite-sized pieces (in TCP called _segments_, over UCP _datagrams_) which makes it easier to transmit the message successfully |
| 3 | network | responsible for locating the destination of your request - this layer takes the IP address and figures out the best route to take|
| 2 | data link |
| 1 | physical|

