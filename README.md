# Elevate-Labs-Task 8 :VPN Privacy and Security Task Report

## Objective  
To evaluate the role of VPNs in enhancing user privacy and securing network communication through practical testing.

## Tools Used  
- VPN Service: X-VPN (Free version)  
- IP Verification: whatismyipaddress.com  
- Speed Testing: speedtest.net  
- Browser: Google Chrome  
- Operating System: Windows 10  

## Steps Performed

1. Launched X-VPN and connected to a free server.
2. Verified the public IP address change using whatismyipaddress.com.
3. Visited HTTPS-enabled websites to confirm encrypted traffic.
4. Measured and compared network performance with and without the VPN using speedtest.net.
5. Documented encryption standards and privacy features of VPN technology.
6. Analyzed the impact on speed and latency when VPN is active.
7. Summarized key benefits and limitations of VPN usage.

## Speed Test Results

### Without VPN
- **Download Speed**: 357.82 Mbps  
- **Upload Speed**: 245.89 Mbps  
- **Idle Ping**: 10 ms  
- **Download Ping**: 49 ms  
- **Upload Ping**: 107 ms  

### With VPN (X-VPN Connected)
- **Download Speed**: 12.1 Mbps  
- **Upload Speed**: 39.6 Mbps  
- **Idle Ping**: 305 ms  
- **Download Ping**: 300 ms  
- **Upload Ping**: 512 ms  

## Observations

- The VPN significantly reduced both download and upload speeds, indicating typical overhead caused by encryption and rerouting.
- Latency increased substantially while connected to the VPN, which could affect real-time activities such as video conferencing or gaming.
- HTTPS padlock icon was present in all browser sessions, confirming encrypted traffic during VPN usage.

## VPN Encryption and Privacy Features

- Utilizes AES-256 encryption for secure data tunneling.
- Supports tunneling protocols such as OpenVPN or proprietary variants.
- Provides IP masking to anonymize user location.
- Offers features like kill switch and DNS leak protection.
- Claims no-log policy for user data privacy (subject to provider transparency).

## Summary: Benefits and Limitations

### Benefits
- Protects user data on unsecured networks such as public Wi-Fi.
- Masks real IP addresses, enhancing privacy and bypassing geo-restrictions.
- Encrypts all internet traffic, mitigating risks of packet sniffing or surveillance.

### Limitations
- Noticeable reduction in connection speed and increased latency.
- VPN provider must be trusted not to log or misuse traffic data.
- Some websites and services may block VPN connections.
- VPNs do not prevent phishing, malware, or tracking through cookies.

## Conclusion

VPNs provide a reliable layer of privacy and data protection when configured and used properly. However, users must be aware of performance trade-offs and the importance of selecting reputable providers. Regular testing and understanding of VPN capabilities are essential for effective use in both personal and enterprise environments.
