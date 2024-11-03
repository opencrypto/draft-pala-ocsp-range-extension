---

title: "Range Queries Extension for OCSP"
abbrev: "OCSP Range Queries"
category: standard

docname: draft-pala-ocsp-range-extension
submissiontype: IETF  # also: "independent", "editorial", "IAB", or "IRTF"
number:
date:
consensus: true
v: 3
area: SECURITY
workgroup: LAMPS Working Group
keyword:
 - ocsp
 - pki
 - revocation
# venue:
#   group: WG
#   type: Working Group
#   mail: WG@example.com
#   arch: https://example.com/WG
#   github: USER/REPO
#   latest: https://example.com/LATEST

author:
 -
    fullname: Massimiliano Pala
    organization: OpenCA Labs
    email: director@openca.org

normative:

informative:


--- abstract

The Online Certificate Status Protocol (OCSP) provides single-certificate-revocation status in real-time. However, the per-certificate lookup approach employed in OCSP has performance and scalability issues when faced with the need for verifying multiple certificates at once. This document describes an extension to OCSP to support optimized range-based queries.


--- middle

# Introduction

The OCSP protocol serves as a method to determine the validity status of an X.509 certificate


# Conventions and Definitions

{::boilerplate bcp14-tagged}


# Security Considerations

TODO Security


# IANA Considerations

This document has no IANA actions.


--- back

# Acknowledgments
{:numbered="false"}

TODO acknowledge.
