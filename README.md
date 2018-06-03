
# SCTP

Package sctp implements the Stream Control Transmission Protocol.

Work in progress.

## RFCs

The package aims to implement the follwing RFCs. Note that the requirement status is based on the [WebRTC spec](https://tools.ietf.org/html/draft-ietf-rtcweb-overview), focusing on data channels for now.

rfc | status | requirement | description
----|--------|-------------|----
[![RFC4960](https://img.shields.io/badge/RFC-4960-blue.svg)](https://tools.ietf.org/html/rfc4960) | ![status](https://img.shields.io/badge/status-research-orange.svg) | [![status](https://img.shields.io/badge/requirement-MUST-green.svg)](https://tools.ietf.org/html/rfc2119) | Stream Control Transmission Protocol
[![RFC3758](https://img.shields.io/badge/RFC-3758-blue.svg)](https://tools.ietf.org/html/rfc3758) | ![status](https://img.shields.io/badge/status-research-orange.svg) | [![status](https://img.shields.io/badge/requirement-MUST-green.svg)](https://tools.ietf.org/html/rfc2119) | SCTP Partial Reliability Extension
[![RFC7496](https://img.shields.io/badge/RFC-7496-blue.svg)](https://tools.ietf.org/html/rfc7496) | ![status](https://img.shields.io/badge/status-research-orange.svg) | [![status](https://img.shields.io/badge/requirement-MUST-green.svg)](https://tools.ietf.org/html/rfc2119) | Additional Policies for Partially Reliable Extension
[![RFC6525](https://img.shields.io/badge/RFC-6525-blue.svg)](https://tools.ietf.org/html/rfc6525) | ![status](https://img.shields.io/badge/status-research-orange.svg) | [![status](https://img.shields.io/badge/requirement-MUST-green.svg)](https://tools.ietf.org/html/rfc2119) | SCTP Stream Reconfiguration
[![RFC8260](https://img.shields.io/badge/RFC-8260-blue.svg)](https://tools.ietf.org/html/rfc8260) | ![status](https://img.shields.io/badge/status-research-orange.svg) | [![status](https://img.shields.io/badge/requirement-MUST-green.svg)](https://tools.ietf.org/html/rfc2119) | Stream Schedulers and User Message Interleaving for the SCTP
[![RFC8261](https://img.shields.io/badge/RFC-8261-blue.svg)](https://tools.ietf.org/html/rfc8261) | ![status](https://img.shields.io/badge/status-research-orange.svg) | [![status](https://img.shields.io/badge/requirement-MUST-green.svg)](https://tools.ietf.org/html/rfc2119) | DTLS Encapsulation of SCTP Packets
[![RFC4821](https://img.shields.io/badge/RFC-4821-blue.svg)](https://tools.ietf.org/html/rfc4821) | ![status](https://img.shields.io/badge/status-research-orange.svg) | [![status](https://img.shields.io/badge/requirement-MUST-green.svg)](https://tools.ietf.org/html/rfc2119) | Packetization Layer Path MTU Discovery
[![RFC4820](https://img.shields.io/badge/RFC-4820-blue.svg)](https://tools.ietf.org/html/rfc4820) | ![status](https://img.shields.io/badge/status-research-orange.svg) | [![status](https://img.shields.io/badge/requirement-MUST-green.svg)](https://tools.ietf.org/html/rfc2119) | Padding Chunk and Parameter for SCTP
[![RFC5061](https://img.shields.io/badge/RFC-5061-blue.svg)](https://tools.ietf.org/html/rfc5061) | ![status](https://img.shields.io/badge/status-research-orange.svg) | [![status](https://img.shields.io/badge/requirement-MUST-green.svg)](https://tools.ietf.org/html/rfc2119) | SCTP Dynamic Address Reconfiguration