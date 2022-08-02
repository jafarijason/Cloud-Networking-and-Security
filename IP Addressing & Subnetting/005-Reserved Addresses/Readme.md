# Reserved Addresses

| Reserved Addresses            |                                         |
| ----------------------------- | --------------------------------------- |
| Class D 224.x.x.x - 239.x.x.x | Reserved for multicasting               |
| Class E 240.x.x.x - 255.x.x.x | Reserved for R&D                        |
| Network ID and BroadcastId    |                                         |
| 0.x.x.x not valid             |                                         |
| 127.x.x.x                     | for loopback addresses (testing TCP/IP) |



## 127.x.x.x loopback addresses

<ul>
    <li>
        Loopback address used for testing local TCP/IP protocols
    </li>
    <li>
        Used to let a system send a message to itself to make sure that TCP/IP stack is installed correctly on the machine
    </li>
    <li>
        Typically 127.0.0.1 is used as the local loopback address.
    </li>
</ul>