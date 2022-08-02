# Ping Command

<br />
<img src="images/2022-08-01_11h14_14.png" />

<ul>
    <li>
        Simple way to test communication between 2 devices.
    </li>
    <li>
        Ping send very small packet to an ip host who will answer by sending packet back.
        <ul>
            <li>
                Called Echo_request and the packet send back Echo_response
            </li>
        </ul>
    </li>
</ul>


<br />
<img src="images/2022-08-01_11h12_57.png" />

## Ping - ICMP Error reporting message

<ul>
    <li>
        Sometimes we don`t get echo ping reply from host machine
    </li>
    <li>
        Instead of that, we get some reply such as
        <ul>
            <li>
                Destination unreachable
                <br>
                <img src="images/2022-08-01_11h35_26.png" />
            </li>
            <li>
                Time exceeded ( request timed out )
                <br>
                <img src="images/2022-08-01_11h36_20.png" />
            </li>
        </ul>
    </li>
    <li>
        This is known as ICMP error reporting message
    </li>
</ul>

<br>
<br>
<br>

### Ping - Request timed out

<br>
<img src="images/2022-08-01_11h36_20.png" />

<ul>
    <li>
        Did not answer to the Ping command.
    </li>
    <li>
        Negative answer does not always mean that the recipients is not alive.
        <ul>
            <li>
                Means that the host just does not answer to ICMP request. 
            </li>
        </ul>
    </li>
</ul>


#### Possible Reasons

<ul>
    <li>
        The host is down or has its network card deactivated.
        <br>
        <img src="images/2022-08-01_11h45_12.png" />
        <br>
        <br>
    </li>
    <li>
        Pinged machine is not connected to the IP network.
        <br>
        <img src="images/2022-08-01_11h46_29.png" />
        <br>
        <br>
    </li>
    <li>
        An external firewall blocks the ICMP requests.
        <br>
        <img src="images/2022-08-01_11h46_36.png" />
        <br>
        <br>
    </li>
    <li>
        The workstation has a personal firewall that blocks the ICMP message.
        <br>
        <img src="images/2022-08-01_11h46_52.png" />
        <br>
        <br>
    </li>
</ul>