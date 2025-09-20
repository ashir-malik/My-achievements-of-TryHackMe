# Room: DNS in Detail
**Platform:** TryHackMe  
**Difficulty:** Beginner  
**Date Completed:** 20th September 2025  

---

## 🗒️ Room Summary
This TryHackMe room explained how the Domain Name System (DNS) works in detail. I learnt how DNS is used because of the difficulty that we face in remembering IP addresses of certain websites.
## 🔑 Key Takeaways
- DNS works like the “phonebook” of the internet. It takes names like `google.com` and resolves them to IP addresses.  
- There are different types of DNS records:
  - **A Record**: Points a domain to an IPv4 address.  
  - **AAAA Record**: Points a domain to an IPv6 address.  
  - **CNAME**: Points one domain name to another domain name.  
  - **MX Record**: Used for mail servers.  
- Recursive DNS servers and authoritative DNS servers both play a big role in resolving queries.  

## 🖥️ Practical Learning
I used the TryHackMe environment to perform DNS lookups and experimented with tools like `nslookup`.   
For example, I queried an A record to see how a domain translates into an IP address. I also checked MX records to see which server was handling emails for a domain.  

## 📸 Some Screenshots
- Example of an A record lookup:  
![A-Record](/images/dns1.png)  

- Checking MX records with `nslookup`:  
![MX-Record](/images/dns2.png)  

- Practicing with CNAME records:  
![CNAME-Record](/images/dns3.png)  

## 🌍 Why DNS Matters
DNS is the foundation of the internet. Without it, we would have to memorize IP addresses instead of domain names.
