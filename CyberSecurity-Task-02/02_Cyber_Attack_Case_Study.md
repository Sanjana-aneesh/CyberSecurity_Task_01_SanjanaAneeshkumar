# Part B: Real-World Case Study — WannaCry Ransomware

## What Happened?

In May 2017, the WannaCry ransomware attack spread rapidly across the world, infecting more than 200,000 computers in over 150 countries within just a few days. WannaCry exploited a vulnerability in older, unpatched versions of Microsoft Windows (known as "EternalBlue," originally developed as a tool by the NSA and later leaked online). Once it infected a machine, it encrypted the user's files and displayed a ransom note demanding payment in Bitcoin in exchange for the decryption key. It spread automatically across networks without requiring any user interaction, which is what made it so devastating and fast-moving. The UK's National Health Service (NHS) was among the most severely affected organizations, alongside companies like FedEx, Telefónica, and Renault.

## Which Part of the CIA Triad Was Affected?

**Availability** was the most directly affected — encrypted files and systems became completely inaccessible to legitimate users, including hospital staff who couldn't access patient records or scheduling systems. **Confidentiality** was less directly impacted since the attackers didn't appear to be stealing or exposing data, but rather locking it. **Integrity** was also affected in a sense, since encrypted files were effectively corrupted from the user's perspective until (or unless) decrypted.

## What Was the Impact?

- The NHS had to cancel thousands of appointments and surgeries, and some emergency services had to redirect patients to other facilities
- Estimated global damages ranged from hundreds of millions to billions of dollars
- Organizations across many industries — logistics, telecom, manufacturing — experienced significant operational disruption
- It exposed how dependent critical services like healthcare are on outdated, unpatched IT infrastructure

## How Could It Have Been Prevented?

- **Timely patching:** Microsoft had already released a patch for the exploited vulnerability two months before the attack; many affected systems simply hadn't applied it
- **Network segmentation:** Limiting how malware can spread laterally across a network would have reduced the scale of infection
- **Regular backups:** Maintaining offline, regularly tested backups would have allowed affected organizations to restore data without paying or losing it permanently
- **Retiring legacy systems:** Many NHS systems were still running unsupported Windows XP machines, which no longer received security updates
- **Endpoint protection and monitoring:** Modern antivirus/endpoint detection tools could have flagged and contained the ransomware behavior earlier
