# Specifications

## Agent2Agent (A2A) Protocol

[A2A Protocol Specification](https://a2a-protocol.org/latest/specification/) | [GitHub](https://github.com/a2aproject/A2A)

The Agent2Agent (A2A) protocol is an open protocol enabling communication and interoperability between opaque agentic applications. A2A addresses a critical challenge in the AI landscape: enabling gen AI agents, built on diverse frameworks by different companies running on separate servers, to communicate and collaborate effectively—as agents, not just as tools. With A2A, agents can discover each other's capabilities, negotiate interaction modalities (text, forms, media), securely collaborate on long running tasks, and operate without exposing their internal state, memory, or tools. Key features include standardized communication via JSON-RPC 2.0 over HTTP(S), agent discovery via "Agent Cards", flexible interaction patterns (synchronous, streaming SSE, asynchronous push), and enterprise-ready security. Originally developed by Google, A2A has been donated to the Linux Foundation.

## IETF Internet-Drafts

### Active Internet-Drafts

#### Agent Directory Service (ADS)

[draft-mp-agntcy-ads](https://datatracker.ietf.org/doc/draft-mp-agntcy-ads/)

The Agent Directory Service (ADS) is a distributed directory service designed to store metadata for AI agent applications. This metadata, stored as directory records, enables the discovery of agent applications with specific skills for solving various problems. The implementation features distributed directories that interconnect through a content-routing protocol.

#### Secure Low-Latency Interactive Messaging (SLIM)

[draft-mpsb-agntcy-slim](https://datatracker.ietf.org/doc/draft-mpsb-agntcy-slim/)

This document specifies the Secure Low-Latency Interactive Real-Time Messaging (SLIM), a protocol designed to support real-time interactive AI applications at scale. SLIM leverages gRPC and adds publish-subscribe capabilities to enable efficient many-to-many communication patterns between AI agentic applications (AI models, tools and data). The protocol provides mechanisms for connection management, stream multiplexing, and flow control while maintaining compatibility with existing gRPC deployments.

#### Messaging Systems for Agentic AI

[draft-mpsb-agntcy-messaging](https://datatracker.ietf.org/doc/draft-mpsb-agntcy-messaging/)

This document analyzes messaging protocols—AMQP, MQTT, NATS, AMQP over WebSockets, Kafka, and AGNTCY SLIM—across dimensions critical for GenAI agent systems: streaming performance, delivery guarantees, security models, and operational complexity. AGNTCY SLIM emerges as a purpose-built solution, integrating Message Layer Security (MLS) with gRPC over HTTP/2 to provide quantum-safe end-to-end encryption, efficient streaming, and OAuth-based authentication.

### Expired Internet-Drafts

#### Hybrid Information-Centric Networking (hICN)

[draft-muscariello-intarea-hicn](https://datatracker.ietf.org/doc/draft-muscariello-intarea-hicn/)

This document describes the hybrid information-centric networking (hICN) architecture for IPv6. The hICN architecture is based on the Internet protocol (IP) and it is designed to seamlessly integrate into existing networks. The hICN architecture inherits the IP address structure and forwarding semantics with the addition of name-based routing and data-centric security.

#### MAP-Me: Managing Anchorless Mobility in CCN

[draft-irtf-icnrg-mapme](https://datatracker.ietf.org/doc/draft-irtf-icnrg-mapme/)

MAP-Me is an anchor-less solution to manage micro-mobility of content producers in the CCN (Content Centric Networking) and NDN (Named Data Networking) architectures, with support for latency-sensitive applications. MAP-Me consists in the combination of two data plane protocols, triggered by producer movements, and leveraging ICN named-based data plane.

#### hICN Mobility

[draft-auge-dmm-hicn-mobility](https://datatracker.ietf.org/doc/draft-auge-dmm-hicn-mobility/)

This document describes mobility support in hybrid Information-Centric Networking (hICN) architectures.

#### hICN Mobility Deployment Options

[draft-auge-dmm-hicn-mobility-deployment-options](https://datatracker.ietf.org/doc/draft-auge-dmm-hicn-mobility-deployment-options/)

This document describes deployment options for mobility support in hybrid Information-Centric Networking (hICN) architectures.

#### Optimized Mobile User Plane

[draft-bogineni-dmm-optimized-mobile-user-plane](https://datatracker.ietf.org/doc/draft-bogineni-dmm-optimized-mobile-user-plane/)

This document describes optimizations for the mobile user plane using distributed mobility management approaches.
