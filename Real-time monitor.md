## Network performance metrics

| Filed           | Description                               | Note      |
| --------------- | ----------------------------------------- | --------- |
| ip_version      | IPv4/IPv6                                 | dimension |
| tcp_udp         | TCP/UDP                                   | dimension |
| l7_protocol     | Application layer protocol                | dimension |
| signature_id    | APP Signature Identification              | dimension |
| rat             | RAT (Radio Access Type)                   | dimension |
| ul_bytes        | Uplink bytes                              | metric    |
| dl_bytes        | Downlink bytes                            | metric    |
| ul_pkts         | Number of uplink data packets             | metric    |
| dl_pkts         | Number of downlink data packets           | metric    |
| ul_retrans_pkts | Number of uplink retransmission packets   | metric    |
| dl_retrans_pkts | Number of downlink retransmission packets | metric    |
| internal_rtt    | Internal system delay (sum), unit: ms     | metric    |
| external_rtt    | External system delay (sum), unit: ms     | metric    |
| tcp_flows       | TCP session total                         | metric    |
| udp_flows       | UDP session total                         | metric    |
## User real-time monitoring
### User network metrics
| Filed       | Description                             | Note |
| ----------- | --------------------------------------- | ---- |
| msisdn      | MSISDN, phone number                    |      |
| imsi        | Unique identifier of the phone number   |      |
| imei        | Unique identifier of the terminal       |      |
| apn         | Access point name                       |      |
| rat         | RAT (Radio Access Type)                 |      |
| bts         | Cellular Base Station Unique Identifier |      |
| cgi_ecgi    | Unique identifier of the cellular       |      |
| online_time | Last online time                        |      |
### User service metrics

| Filed               | Description                               | Note |
| ------------------- | ----------------------------------------- | ---- |
| session_start_time  | Session start time                        |      |
| session_update_time | Session update time                       |      |
| msisdn              | MSISDN, phone number                      |      |
| user_ip             | User IP address                           |      |
| user_port           | User port number                          |      |
| server_ip           | Service IP address                        |      |
| server_port         | Service port number                       |      |
| l4_protocol         | Layer 4 protocol, TCP/UDP                 |      |
| l7_protocol         | Layer 7 protocol, DNS/FTP/HTTPS/...       |      |
| signature_id        | APP signature identification              |      |
| sni                 | Server name indication, e.g. google.com   |      |
| url                 | e.g. www.abc.com/def/gh/                  |      |
| ul_bytes            | Uplink bytes                              |      |
| dl_bytes            | Downlink bytes                            |      |
| internal_rtt        | Internal system delay (sum), unit: ms     |      |
| external_rtt        | External system delay (sum), unit: ms     |      |
| duration            | Session Duration                          |      |
| policy_id           | Policy ID                                 |      |
| template_id         | Service template ID                       |      |
| action_type         | Probe action type, e.g. block,redirection |      |
## Base station real-time monitoring
### Base station performance metrics

| Filed           | Description                               | Note |
| --------------- | ----------------------------------------- | ---- |
| nb_id           | Base station unique identifier            |      |
| ul_bytes        | Uplink bytes                              |      |
| dl_bytes        | Downlink bytes                            |      |
| ul_pkts         | Number of uplink data packets             |      |
| dl_pkts         | Number of downlink data packets           |      |
| ul_retrans_pkts | Number of uplink retransmission packets   |      |
| dl_retrans_pkts | Number of downlink retransmission packets |      |
| internal_rtt    | Internal system delay (sum), unit: ms     |      |
| external_rtt    | External system delay (sum), unit: ms     |      |
| tcp_flows       | TCP session total                         |      |
| udp_flows       | UDP session total                         |      |
| user_count      | User count                                |      |
### Base station user metrics
| Filed    | Description                       | Note |
| -------- | --------------------------------- | ---- |
| nb_id    | Base station unique identifier    |      |
| cgi_ecgi | Unique identifier of the cellular |      |
| msisdn   | MSISDN, phone number              |      |