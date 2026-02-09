Intelligence Briefing

I’ve recently observed a new type of malware that we have named ‘TRANSPORTER’ which uses DNS tunneling to provide a command-and-control channel across the internet, allowing an attacker to send commands to infected systems. As DNS traffic is extremely common in environments this traffic blends in and does not immediately look suspicious. DNS packets contain many fields and headers in which data can be concealed.

At the time , I have only observed one domain name that is being used to send and receive C2 traffic, Speaking with one victim I observed that their SIEM did not detect this activity as they were not monitoring for excessive DNS queries to domains.
