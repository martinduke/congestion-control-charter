# Congestion Control Working Group Charter (CCWG)

RFC 5033 describes a Best Current Practice to evaluate new congestion control
algorithms as Experimental or Proposed Standard RFCs. TCP was the dominant
consumer of this work, and proposals were typically discussed in research
groups, for example the Internet Congestion Control Research Group (ICCRG).

Since RFC 5033 was published, many conditions have changed. Congestion control
algorithm proponents now often have the opportunity to test and deploy at scale
without IETF review. The set of protocols using these algorithms has spread
beyond TCP and SCTP to include DCCP, QUIC, and beyond. There is more interest
in specialized use cases such as data centers and real-time protocols. Finally,
the community has gained much more experience with indications of congestion
beyond packet loss.

The Congestion Control Working Group will review some of the impediments to
congestion control work occurring in the IETF and can generalize transports
from TCP to all of the relevant transport protocols. This will inform a
revision of RFC 5033 that encourages IETF review of congestion control
proposals and standardization of mature congestion control algorithms.

The congestion control expertise in the working group also makes it a natural
venue to take on other work related to indications of congestion such as delay,
queuing algorithms, rate pacing, multipath, interaction with other layers,
among others. In particular, it can address congestion control algorithms with
empirical evidence of safety and stated intent to deploy by major
implementations. The working group is intended to be a home for such work, and
it is chartered to adopt proposals in this space regardless of the status of
the initial deliverable.

The group will coordinate closely with other relevant working and research
groups, including ICCRG, TCPM, QUIC, and TSVWG. Documents in CCWG will remain
as transport protocol agnostic as possible, but they may have short specific
instructions, such as header options or parameter formats, for one or more
protocols. Documents that are wholly specific to mechanisms in a single
protocol will remain in the maintenance working group for that protocol.

Algorithms proposed for Experimental status, in consultation with ICCRG, based
on an assessment of their maturity and likelihood of near-term wide-scale
deployment, are in scope.

CCWG is not chartered to publish Informational RFCs documenting the state of
congestion control in the Internet, including assessments of compliance with
existing standards. Other venues, such as the IRTF, may be more appropriate for
publishing such documents.

Upon completion of its deliverables, the Congestion Control WG will close in 
the absence of suitable proposals for further work.

#Milestones

  - Submit 5033bis to IESG for publication. 	
