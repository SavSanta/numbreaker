# numbreaker

## Synopsis
A Cobalt Strike Aggressor Script to assist an operators in conversions of common numerical types into human understandable types.
Supports converting from:
    - User Account Control values that are associated to an accounts in Active Directory.
    - Common Microsoft timestamps. ie Active Directory (e.g. accountExpires, LastLogon, LastLogonTimestamp, and LastPwdSet) or Windows Filetime/Systemtime values.
    
## Usage

1) Install the Aggressor Script into your Cobalt Strike Client.
2) Inside a beacon window type `numbreaker`
3) Enter in a numerical value in the new pop-up window
4) Selecte what type of conversion is necessary from the radial buttons.

## Caveats

The radial option for berval is currently NOT IMPLEMENTED. It's a placeholder until one day I drum up one more numerical option that can be converted clientside for operators.

## Screenshots



