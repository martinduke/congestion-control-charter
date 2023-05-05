# Congestion Control Working Group Charter (CCWG)


RFC 5033 describes a Best Current Practice to evaluate new congestion control
algorithms as Experimental or Proposed Standard RFCs. TCP was the dominant
consumer of this work, and proposals were typically discussed in research
groups (for example, the Internet Congestion Control Research Group - ICCRG).

Since RFC 5033 was published, many conditions have changed. Congestion control
algorithm proponents now often have the opportunity to test and deploy at scale
without IETF review. The set of protocols using these algorithms has spread
beyond TCP and SCTP to include DCCP, QUIC, and beyond. There is more interest
in specialized use cases such as data centers and real-time protocols. Finally,
the community has gained much more experience with indications of congestion
beyond packet loss.

The Congestion Control Working Group will review some of the impediments to 
congestion control work occurring in the IETF and can generalize transports
from TCP to all of the relevant transport protocols. This will inform a revision
of RFC 5033 that encourages IETF review of congestion control proposals and
standardization of mature congestion control algorithms.

The congestion control expertise in the working group would also make it a
natural venue to take on other work related to indications of congestion (such
as delay), queueing algorithms, rate pacing, interaction with other layers,
etc. In particular, it could address congestion control algorithms with
empirical evidence of safety and stated intent to deploy by major
implementations. The working group is intended to be a home for such work, should
it arise, if not suitable for the IRTF. It is chartered to consider proposals in
this space, and given consensus to adopt, seek an immediate recharter regardless
of the status of the initial deliverable.

Upon completion of its deliverables, the Congestion Control WG will close in 
the absence of suitable proposals for further work.
