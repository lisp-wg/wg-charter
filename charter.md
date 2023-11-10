# LISP Working Group Charter Proposal

LISP supports an overlay routing architecture that decouples the routing locators and endpoint identifiers, thus allowing for efficient aggregation of the routing locator space and providing persistent identifiers in the endpoint space. LISP requires no changes to endpoints or routers that do not directly participate in the LISP deployment. LISP aims for an incrementally deployable protocol, so new features and services can be added easily and quickly to the network using overlays. The scope of the LISP technology is potentially applicable to have a large span. The LISP WG is chartered to continue work on the LISP protocol, including extensions for which the working group has consensus on deeming them necessary, and produce standard-track documents.

The working group will work on the following items:

- Moving to Standard Track: The core specifications of LISP have been published as “Standard Track” ([RFC9300], [RFC9301]). The WG will continue the work of moving select specifications to “Standard Track” (e.g., LISP Canonical Address Format [RFC8060], LISP Multicast [RFC6831][RFC8378], etc).

- Map Server Reliable Transport: LISP control plane messages are transported over UDP, however, in some cases, the use of a reliable transport protocol is a better fit, since it actually helps reduce periodic signaling. 

- Yang Models: The management of LISP protocol and deployments include data models, OAM, as well as allowing for programmable management interfaces.

- LISP for Traffic Engineering: Specifics on how to do traffic engineering on LISP deployments could be useful. For instance, encode in a mapping not only the routing locators associated to EIDs, but also an ordered set of re-encapsulating tunnel routers (RTRs) used to specify a path.

- NAT-Traversal: Support for a NAT-traversal solution in deployments where LISP tunnel endpoints are separated from by a NAT (e.g., LISP mobile node).

- Privacy and Security: The WG will work on EID anonymity, VPN segmentation leveraging on the Instance ID, and traffic anonymization. The reuse of existing mechanisms will be prioritized.

- LISP External Connectivity: [RFC6832] defines the Proxy ETR element, to be used to connect LISP sites with non-LISP sites. However, LISP deployments could benefit from more advanced internetworking, for instance by defining mechanism to discover such external connectivity.

- Mobility: Some LISP deployment scenarios include endpoints that move across different LISP xTRs and/or LISP xTRs that are themselves mobile. Support needs to be provided to achieve seamless connectivity.

- LISP Applicability: LISP has proved to be a very flexible protocol that can be used in various use-cases not considered during its design phase. [RFC7215], while remaining a good source of information, covers one single use case, which is no longer the main LISP application scenario. The LISP WG will document LISP deployments for most recent and relevant use-cases, so as to update and complement [RFC7215] as needed.


## Proposed Charter: Tentative Milestones

1. November 2023: Submit LISP Name Encoding document to the IESG for consideration
2. March 2024: Submit LISP Reliable Transport document to the IESG for consideration
3. March 2024: Submit LISP Yang model document to the IESG for consideration
4. March 2024: Submit LISP Traffic Engineering document to the IESG for consideration
5. March 2024: Submit LISP Geo-Coordinates document to the IESG for consideration
7. November 2024: Submit LISP NAT Traversal document to the IESG for consideration
8. November 2024: Submit LISP DDT bis document to the IESG for consideration
9. November 2024: Submit LISP LCAF bis document to the IESG for consideration
10. March 2025: Submit LISP Privacy and Security document(s) to the IESG for consideration
11. March 2025: Submit LISP External Connectivity document(s) to the IESG for consideration
12. July     2025: Submit LISP Mobility document(s) to the IESG for consideration
13. November 2025: Submit LISP Multicast document(s) to the IESG for consideration
14. March 2026: Submit LISP Applicability document(s) to the IESG for consideration
15. November 2026: Wrap-Up or recharter 
