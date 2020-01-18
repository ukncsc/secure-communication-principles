# 2. Protect network nodes with access to sensitive data

## Are network nodes with access to un-encrypted data protected appropriately?

Communications will typically transit a network, and in doing so they will pass through various servers and routers. Any of these network nodes with access to un-encrypted data may be able to access **all** communications between **all** users.

Network nodes that have access to un-encrypted data should be appropriately protected, at a level considerate of the impact of any compromise of communications. If the appropriate level of protection required for network nodes cannot be met, you should consider using a service that supports end to end encryption. 

## Are network nodes that manage cryptographic key material protected appropriately?

Communications normally rely on cryptography for security, with trust in the security relying on cryptographic keys. If someone gained access to the key management functionality in a service, then they could abuse this trust (for example to spoof any user, or potentially access their communications data).

As cryptographic key material often acts as the root of trust in a secure communications service, any part of the service involved in key management should be appropriately protected at a level considerate of the impact of compromise.
