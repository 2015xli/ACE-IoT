Introduction [video](files/ACE-IoT.mp4) by the project owner Prof. Grace A. Lewis - downloaded from [youtube](https://www.youtube.com/watch?v=RaAioL1Kpno).

The SEI ACE Implementation for Constrained and Unconstrained Resource Servers consists of five repositories:
* [Client](https://github.com/SEI-TTG/ace-client)
* [Authorization Server](https://github.com/SEI-TTG/ace-as)
* [Unconstrained Resource Server](https://github.com/SEI-TTG/ace-rs)
* [Constrained Resource Server](https://github.com/SEI-TTG/ace-6lbr) - token revocation functionality under development
* [Supporting Libraries](https://github.com/SEI-TTG/aaiot-lib)

It is an implementation of the ACE Working Group proposal for [Authentication and Authorization in Resource-Constrained Environments](https://datatracker.ietf.org/wg/ace/about/) with two extensions to support operation in disadvantaged environments:
* RS to AS Pairing
* Periodic introspection for token revocation

The implementation is based on previous work in [establishing trusted identities in disconnected edge environments](https://ieeexplore.ieee.org/abstract/document/7774673) and explicit threat modeling. Supporting documents for this work are:
* [Sequence Diagrams](files/Sequence-Diagrams.pdf)
* [Threat Model Report for Pairing](files/ACE-Threat-Model-Pairing-Report.pdf) (produced using [Microsoft SDL Threat Modeling Tool](https://www.microsoft.com/en-us/sdl/adopt/threatmodeling.aspx))
* [Threat Model Report for Resource Access](files/ACE-Threat-Model-Resource-Access-Report.pdf) (produced using [Microsoft SDL Threat Modeling Tool](https://www.microsoft.com/en-us/sdl/adopt/threatmodeling.aspx))
