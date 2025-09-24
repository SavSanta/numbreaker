# numbreaker

### Overview
A Cobalt Strike Aggressor Script to assist an operators in conversions of common numerical, alphanumerical, or similar data types into human readable data.
Supports converting from:  

   - SAMAccount type values that are typically found listed for accounts in Active Directory.  
   - User Account Control values that are associated to an accounts in Active Directory.  
   - Common Microsoft timestamps. ie Active Directory (e.g. accountExpires, LastLogon, LastLogonTimestamp, and LastPwdSet) or Windows Filetime/Systemtime values.
   - CIDR Range start and end calculation
    
### Usage

1) Install the Aggressor Script into your Cobalt Strike Client.
2) In a beacon window type `numbreaker`
3) Enter in a value in the new pop-up window
4) Select the type of conversion that is desired by clicking on the appropriate radial dial buttons.

Alternatively, once can install as a right-click pop-up in your Cobalt Strike default.cna. Reference the [manual](https://hstechdocs.helpsystems.com/manuals/cobaltstrike/current/userguide/content/topics_aggressor-scripts/as_cobalt-strike.htm) for more info.

## Screenshots

![NTDATE EX](screenshots/sshot-samacct.png)

SAM Account Type

![NTDATE EX](screenshots/sshot-ntdate.png)

MSAD/LDAP/NT Datetime

![UAC EX](screenshots/sshot-uac.png)

User Account Control

![UAC EX](screenshots/sshot-cidr.png)

CIDR Range Calc


## TODO
- UI Readibilty Changes/Theme Switcher (ADA assist for us blindies)
