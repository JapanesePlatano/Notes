# Pass the Hash with Mimikatz

Name the six credential-gathering techniques which Mimikatz is able to perform and explain how two of them work.

Mimikatz can perform six credential-gathering techniques: Pass-the-hash, Pass-the-ticket, Overpass-the-hash (pass-the-key), Kerberoast golden tickets, Kerberoast silver tickets, and Pass-the-cache. The "Pass-the-hash" technique allows attackers to use a hashed version of a password to authenticate without needing the actual password. The "Pass-the-ticket" method involves using a Kerberos ticket to authenticate on other computers without needing the user’s password.

What are four ways we can defend against Mimikatz attacks. Explain how two of the mitigations can stop Mimikatz.

To defend against Mimikatz attacks, some effective methods include restricting admin privileges and disabling password caching. Restricting admin privileges limits who can access sensitive parts of the system, reducing the risk of Mimikatz being used effectively. Disabling password caching prevents passwords from being stored in a recoverable format on the system, which reduces the chances of Mimikatz recovering them.

## Things I want to know more about

N/A