# 100Mbit communication test
## setup
```mermaid
graph LR
    PC -- usb --> b051
    b051 --> b016
    b016 --> b099
    b099 --> b010
    b010 --ethernet --> internet
```
## results
The PC was able to communicate with the internet through the chain.
