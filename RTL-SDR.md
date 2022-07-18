# RTL-SDR
---
><b>Setup</b>
`sudo apt-get install -y gqrx-sdr`

### rtl_test
To test if the connection is established or not
### rtl_tcp
To get the ip address.
Use the same ip for the gqrx
### gqrx
open the application and paste the ip address.
For radio application chose WFM
### rtl_adsb
This is used for flight navigation. 
#### Dump1080
> <b>Setup</b>
`sudo apt install dump1090-mutability`

* `dump1090-mutability --interactive`
Interactive mode refreshing data on screen.
* `dump1090-mutability --interactive-rtl1090`
Display flight table in RTL1090 format
