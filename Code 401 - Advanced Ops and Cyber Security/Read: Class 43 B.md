# Sniffing and Evasion

1. **Explain a Sniffing Attack Using Non-Technical Terms**:
   A sniffing attack is similar to eavesdropping on private conversations but occurs in the digital realm. In this context, the malicious individual uses special tools to secretly "listen" to the data being sent across a network. This can involve capturing sensitive information like passwords or manipulating the data to disrupt services or gain unauthorized access to systems.

2. **What are the Two Types of Sniffing Attacks and What are Some Pros and Cons of Each Approach?**:

   - **Passive Sniffing**: Where the attacker silently captures data without altering the network. The advantage of passive sniffing is that it’s harder to detect since it doesn’t interfere with normal network operations. However, it’s mostly effective on unsecured or non-switched networks.
   - **Active Sniffing**: This involves more aggressive techniques like ARP spoofing, where the attacker sends false ARP messages to manipulate network traffic. Active sniffing can be used even on modern, switched networks. While it allows for capturing more data, it’s more detectable and can disrupt network operations.

3. **How Does Encryption Protect Traffic Against Sniffing Attacks?**:
   Encryption secures data by transforming it into a coded form that can only be understood if decrypted with the correct key. During a sniffing attack, even if attackers capture encrypted data, they cannot derive any meaningful information from it without the encryption key. This security measure significantly reduces the risk of sensitive data being exposed or manipulated during transmission. Encryption is particularly crucial for protecting data in scenarios where sniffing attacks like capturing SSH packets are possible, as it ensures that captured data remains secure and unreadable without the correct decryption mechanisms.

## Things I want to know more about

N/A