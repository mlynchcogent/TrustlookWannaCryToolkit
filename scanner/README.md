# Trustlook WannaCry Ransomware Scanner

The Wannacry Scanner to help system admin to scan your network for vulnerable windows systems. 

## Install

This tool need to python to run, and install the related package with:
```
pip install -r requirements.txt
```

## Usage

```
Usage: wannacry_tlscan.py host/network
Example:
    wannacry_tlscan.py 192.168.0.100
    wannacry_tlscan.py 192.168.0.0/24
```

### Single host scan
`wannacry_tlscan.py 192.168.0.100`

### Single a network
`wannacry_tlscan.py 192.168.0.0/24`

## Tech details and update
Please check out Trustlook blog at [https://blog.trustlook.com/](https://blog.trustlook.com/)


## Install SEcurity Path From Microsoft

### For general windows system, download at:
[https://technet.microsoft.com/en-us/library/security/ms17-010.aspx](https://technet.microsoft.com/en-us/library/security/ms17-010.aspx)

### For Windows XP, 2003, Vista and Windows 8 system, download at:
[http://www.catalog.update.microsoft.com/Search.aspx?q=KB4012598](http://www.catalog.update.microsoft.com/Search.aspx?q=KB4012598)