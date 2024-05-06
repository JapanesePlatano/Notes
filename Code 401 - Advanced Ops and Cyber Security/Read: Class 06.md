# Data file encryption

You have been made responsible for the company’s file server. How would you preserve the three elements of the CIA triad?

For confidentiality, I would use strong encryption methods for data both at rest and in transit, and employ secure protocols such as HTTPS or SFTP for transferring data. For integrity, I would utilize hashing and digital signatures to verify file authenticity during transfers and maintain a log of all file modifications. For availability, I would establish redundant systems and backups to guarantee data access, even during unforeseen downtimes or cyber-attacks.

Explain how hashing verifies data integrity using non-technical terms.

Using a blender that makes a unique smoothie based on the exact ingredients and amounts you put in. If you change even a small part of the recipe, swap an apple for an orange, the resulting smoothie changes. Hashing is like using this blender on digital data. When data is "blended" through a hashing process, it produces a unique digital "smoothie" or hash value. If the data changes slightly, the new hash will be vastly different, just like the smoothie. This makes it easy to check if data has been altered, just by comparing the "flavor" of the hash values.

How is hashing and encryption different?

Hashing and encryption are both ways to process data but serve different goals. Hashing converts data into a fixed, unique string of characters, which cannot be turned back into the original data. It’s used to check if data has been changed or to quickly look up data. Encryption also changes data’s format but it can be reversed if you have the right key, making it ideal for keeping data private. Hashing is for ensuring data hasn’t been altered, while encryption is for keeping data confidential.

## Things I want to know more about

N/A

### Source

https://www.jscape.com/blog/implementing-the-cia-triad-when-transferring-files-through-the-internet

https://www.howtogeek.com/67241/htg-explains-what-are-md5-sha-1-hashes-and-how-do-i-check-them/