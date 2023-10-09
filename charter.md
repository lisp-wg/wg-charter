# LISP Working Group Charter Proposal


## Proposed Charter: Introduction

LISP supports a routing architecture which decouples the routing locators and identifiers, thus
allowing for efficient aggregation of the routing locator space and providing persistent
identifiers in the identifier space. LISP requires no changes to end-systems or to routers that
do not directly participate in the LISP deployment. LISP aims for an incrementally deployable
protocol, so new features and services can be added easily and quickly to the network using
overlays. The scope of the LISP technology is potentially applicable to have a large span.The
LISP WG is chartered to continue work on the LISP protocol and produce standard-track
documents.


## Proposed Charter: Work Items Part 1

- NAT-Traversal: Support for NAT-traversal solution in deployments where LISP tunnel routers
are separated from correspondent tunnel routers by a NAT (e.g., LISP mobile node).
- YANG models for managing the LISP protocol and deployments that include data models,
OAM, as well as allowing for programmable management interfaces. These management
methods should be considered for both the data-plane, control plane, and mapping system
components.
- Multicast Support: LISP support for multicast environments has a growing number of use
cases. Support for multicast is needed in order to achieve scalability. The current documents
[Ref to experimental multicast RFCs] should be merged and published as Standard Track.
- Map Server Reliable Transport: LISP control plane messages are transported over UDP, however, in some cases, the use of a reliable transport protocol is a better fit, since it actually helps reduce periodic signaling. 


## Proposed Charter: Work Items Part 2

- Standard Track Documents: The core specifications of LISP have been published as
“Standard Track” [references]. The WG will continue the work of moving select
specifications to “Standard Track”.
- Mobility: Some LISP deployment scenarios include mobile nodes (in mobile environments)
or Virtual Machines (VMs in data centers), hence, support needs to be provided in order to
achieve seamless connectivity.
- Privacy and Security: The WG will work on topics of EID anonymity, VPN segmentation
leveraging on the Instance ID, and traffic anonymization. The reuse of existing mechanisms
will be prioritized.
- LISP Applicability: In time, LISP has proved to be a very flexible protocol that can be used
in various use-cases not even considered during its design phase. RFC 7215, while
remaining a good source of information, covers one single use case, which is not anymore
the main LISP application scenario. The LISP WG will document LISP deployments for most
recent and relevant use-cases so as to update RFC 7215.


## Proposed Charter: Tentative Milestones

1. November 2023: Submit a LISP YANG document to the IESG for consideration
2. March 2024: Submit a LISP NAT Traversal document to the IESG for consideration
3. June 2024: Submit 8111bis to the IESG for consideration
4. June 2024 : Submit LISP geo-coordinates for consideration
5. November 2024: Submit merged Multicast document to the IESG for consideration
6. March 2025: Submit 6832bis pXTRs to the IESG for consideration
7. June 2025: Submit merged LCAFbis to the IESG for considerations
8. November 2025: Submit LISP Mobile Node to the IESG for considerations
9. March 2026: Submit LISP Applicability document to the IESG for considerations
10. November 2026: Wrap-Up or recharter
