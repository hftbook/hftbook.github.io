# Network in HFT

## OSI model

<table>
<tbody><tr>
<th colspan="3">Layer</th>
<th>Protocol data unit (PDU)</th>
<th>Function</th></tr>
<tr>
<th rowspan="4">Host<br />layers
</th>
<td style="background:#00ff00;">7
</td>
<td style="background:#00ff00;"><a href="/wiki/Application_layer" title="Application layer">Application</a>
</td>
<td style="background:#00ff00;" rowspan="3"><a href="/wiki/Data_(computing)" class="mw-redirect" title="Data (computing)">Data</a>
</td>
<td style="background:#00ff00;">High-level protocols such as for resource sharing or remote file access, e.g. <a href="/wiki/Hypertext_Transfer_Protocol" title="Hypertext Transfer Protocol">HTTP</a>.
</td></tr>
<tr>
<td style="background:#00ff00;">6
</td>
<td style="background:#00ff00;"><a href="/wiki/Presentation_layer" title="Presentation layer">Presentation</a>
</td>
<td style="background:#00ff00;">Translation of data between a networking service and an application; including <a href="/wiki/Character_encoding" title="Character encoding">character encoding</a>, <a href="/wiki/Data_compression" title="Data compression">data compression</a> and <a href="/wiki/Encryption" title="Encryption">encryption/decryption</a>
</td></tr>
<tr>
<td style="background:#00ff00;">5
</td>
<td style="background:#00ff00;"><a href="/wiki/Session_layer" title="Session layer">Session</a>
</td>
<td style="background:#00ff00;">Managing communication <a href="/wiki/Session_(computer_science)" title="Session (computer science)">sessions</a>, i.e., continuous exchange of information in the form of multiple back-and-forth transmissions between two nodes
</td></tr>
<tr>
<td style="background:#ffff00;">4
</td>
<td style="background:#ffff00;"><a href="/wiki/Transport_layer" title="Transport layer">Transport</a>
</td>
<td style="background:#ffff00;"><a href="/wiki/Packet_segmentation" title="Packet segmentation">Segment</a>, <a href="/wiki/Datagram" title="Datagram">Datagram</a>
</td>
<td style="background:#ffff00;">Reliable transmission of data segments between points on a network, including <a href="/wiki/Packet_segmentation" title="Packet segmentation">segmentation</a>, <a href="/wiki/Acknowledgement_(data_networks)" title="Acknowledgement (data networks)">acknowledgement</a> and <a href="/wiki/Multiplexing" title="Multiplexing">multiplexing</a>
</td></tr>
<tr>
<th rowspan="3">Media<br />layers
</th>
<td style="background:#eddc9c;">3
</td>
<td style="background:#eddc9c;"><a href="/wiki/Network_layer" title="Network layer">Network</a>
</td>
<td style="background:#eddc9c;"><a href="/wiki/Network_packet" title="Network packet">Packet</a>
</td>
<td style="background:#eddc9c;">Structuring and managing a multi-node network, including <a href="/wiki/Address_space" title="Address space">addressing</a>, <a href="/wiki/Routing" title="Routing">routing</a> and <a href="/wiki/Network_traffic_control" title="Network traffic control">traffic control</a>
</td></tr>
<tr>
<td style="background:#e9c189;">2
</td>
<td style="background:#e9c189;"><a href="/wiki/Data_link_layer" title="Data link layer">Data link</a>
</td>
<td style="background:#e9c189;"><a href="/wiki/Frame_(networking)" title="Frame (networking)">Frame</a>
</td>
<td style="background:#e9c189;">Transmission of data frames between two nodes connected by a physical layer
</td></tr>
<tr>
<td style="background:#ff0000;">1
</td>

<td style="background:#ff0000;">Physical
</td>
<td style="background:#ff0000;"><a href="/wiki/Bit" title="Bit">Bit</a>, <a href="/wiki/Symbol_rate#Symbols" title="Symbol rate">Symbol</a>
</td>
<td style="background:#ff0000;">Transmission and reception of raw bit streams over a physical medium
</td></tr></tbody></table>