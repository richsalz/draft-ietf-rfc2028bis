---
docname: draft-rsalz-2028bis-latest
obsoletes: 2028
title: Entitities Involved in the IETF Standards Process
category: bcp
workgroup: ???
ipr: trust200902

stand_alone: yes
pi:
  toc: yes
  sortrefs: yes
  symrefs: yes
  compact: yes
  subcompact: no

keyword: [IESG, RFC Editor, IRTF, IETF LLC, ISOC, registries, IANA]

author:
  -
    name: Rich Salz
    org: Akamai Technologies
    email: rsalz@akamai.com
normative:
  RFC2028: RFC2028
  IPRPOLICY: RFC5378
  IANADOCS: RFC8126
  MEETINGS: RFC8719
  IAB: RFC2850
  IESG: RFC3710
  IETFPROCS: RFC2026
  IRTF: RFC2014
  NOMCOM: RFC8713
  WGPROCS: RFC2418
  ISOC:
    target: https://www.internetsociety.org/about-internet-society/governance-policies/by-laws/
    title: Amended and restatated By-Laws of the Internet Society
    date: March, 2021
informative:
  LLCLEGAL: RFC8712
  COPYRIGHT: RFC8721
  TRUSTEES: RFC8715

--- abstract

This document describes the individuals and organizations involved in
the IETF standards process as described in {{IETFPROCS}}.
It includes brief descriptions of the entities involved,
and the role they place in the standards process.

--- middle

# The IETF Standards Process

The process used by the IETF community for the standardization of
protocols and procedures is described in {{IETFPROCS}}.
That document defines
the stages in the standardization process, the requirements for
moving a document between stages, and the types of documents used
during this process. It also addresses the intellectual property
rights and copyright issues associated with the standards process.
This document identifies some of the key individual and organizations
and the roles they play in that process.

# Terminology

In general, this document refers to individual roles as individuals,
such as "a Document Editor."
In reality, many roles are filled by more than one person at the same
time.
For clarity, this document does not use phrases like "Chair (or co-chair),"
unless strictly necessary to do so.

# Key Individuals in the Process

This section describes the individual roles involved in the process.
It attempts to list the roles in the order in which they are involved
in the process, but no meaning is otherwise attached.

## The Document Editor or Author {#doceditor}

Most Working Groups focus their efforts on one or more documents
that capture the results of the group's work.  A Working
Group generally designates a person to serve as the Editor
for a particular document.  The Document Editor is responsible for
ensuring that the contents of the document accurately reflect the
decisions that have been made by the Working Group.

When a document is composed and edited mainly by an individual,
they may be referred to as the Document Author. The distinction is
not significant.
This document will use the term Document Editor.

When a Document Editor is a Chair of the same Working Group, a
co-chair should manage the process around the document. If a co-chair is not
available, the process must be monitored carefully to ensure that the
resulting documents accurately reflect the consensus of the Working Group and
that all processes are followed. This can be the collective obligation
of all parties involved in the document.

## The Working Group Chair {#wgchair}

Each Working Group is headed by a chair with
the responsibility for directing the group's activities, presiding
over the group's meetings, and ensuring that the commitments of the
group with respect to its role in the Internet standards process are
met. In particular, the WG chair is the formal point of contact
between the WG and the IESG, via the Area Director of the area to
which the WG is assigned.

The details on the selection and responsibilites of a Working
Group chair can be found in {{WGPROCS}}.

## The Area Director

The Area Director assigned as the "Reponsible Area Director" for the
Working Group will review the document after the Working Group has approved its
last call, and when satisfied will request it to be put on the IESG
agenda.

## The Request for Comments Editor

The RFC publication series {{IETFPROCS}} is managed by an Editor
responsible both for the
mechanics of RFC publication and for upholding the
technical and editorial standards of the RFC series.

# Key Organizations in the Process

The following organizations and organizational roles are involved in
the Internet standards process.

## Internet Engineering Task Force (IETF)

The IETF is an open international
community of network designers, operators, vendors, researchers,
and other interested parties who are
concerned with the evolution of the Internet architecture and the
smooth operation of the Internet.  It is the principal body engaged
in the development of new Internet Standard specifications.

## Working Groups

The technical work of the IETF is done in its Working Groups, which
are organized by topics into several
[Areas](https://www.ietf.org/topics/areas/),
each one under the coordination of the Area Director.
Working Groups typically have a narrow focus and a lifetime bounded
by completion of specific tasks as defined in their charter
and milestones.

For all purposes relevant to the Internet Standards development
process, membership in the IETF and its Working Groups is defined to
be established solely and entirely by individuals who
participate in
IETF and Working Group activities.
These individuals do not formally represent their organizations, if any,
although affiliations are often used for identification.

Anyone with the time and interest to do so is entitled and urged to
participate actively in one or more Working Groups and to attend
IETF meetings which are usually held
three times a year {{MEETINGS}}.
Active Working Group participation is possible without attending
any in-person meeting.

Participants in the IETF and its Working Groups must disclose
any relevant current or pending intellectual
property rights that are reasonably and personally known to the
participant if they participate in discussions about a specific
technology.
The full intellectual property policy is defined in {{IPRPOLICY}}.

New Working Groups are established by the IESG
and almost always have a specific and explicit charter.
The charter can be modified as the Working Group progresses.
The guidelines and procedures for the formation and
operation of Working Groups are described in detail in {{WGPROCS}}.

A Working Group is managed by a Working Group chair, as described at
{{wgchair}}.  Documents produced by the group will have an Editor, as
described at {{doceditor}}.  Further details of Working Group operation can
also be found in {{WGPROCS}}.

Working Groups ideally display a spirit of cooperation as well as a high
degree of technical maturity; IETF participants recognize that the
greatest benefit for all members of the Internet community results
from cooperative development of technically superior protocols and
services.

## Internet Engineering Steering Group (IESG)

The IESG is
responsible for the management of the IETF technical
activities.  It administers the Internet Standards process according
to the rules and procedures defined in {{IETFPROCS}}.  The IESG is responsible
for the actions associated with the progression of technical
specification along the "standards track" including the initial
approval of new Working Groups and the final approval of
specifications as Internet Standards.  The IESG is composed of the
IETF Area Directors and the IETF Chair, who also chairs the IESG and
is the Area Director for the General Area.

All members of the IESG are nominated by a nominations committee
(colloquially, NomCom),
and are approved by the IAB.  See {{NOMCOM}} for a detailed
description of the NomCom procedures. Other matters concerning its
organization and operation, are described in the IESG charter {{IESG}}.

## Internet Architecture Board (IAB)

The IAB provides oversight of the architecture of the Internet and its
protocols.  The IAB must approve all IESG candidates put forward by the
NomCom.

The IAB provides oversight of the process used to create Internet
Standards and serves as an appeal board for complaints of improper
execution of the standards process {{IETFPROCS}}. In general, it acts as source
of advice to the IETF and other entities mentioned here about
technical, architectural, procedural, and policy matters
pertaining to the Internet and its enabling technologies.

The members of the IAB are nominated by NomCom,
and are approved by the ISOC board.  The IETF Chair is an ex-officio member
of the board.
See {{NOMCOM}} for a detailed description of the NomCom procedures. Other
matters concerning its organization and operation, are described in the IAB
charter {{IAB}}.

## Internet Assigned Numbers Authority (IANA)

Many protocol specifications include
parameters that must be uniquely assigned.  Examples of this
include port numbers, option identifiers within a protocol,
and so on. The
Internet Assigned Numbers Authority (IANA) is responsible for
assigning the values of these protocol parameters for the Internet.
These registries used to be published as RFCs entitled "Assigned
Numbers," but are [now maintained online](https://www.iana.org/protocols).
Assignments are coordinated by writing an "IANA Considerations" section
in a draft, as documented in {{IANADOCS}}.

IANA also is responsible for operating and maintaining
[several aspects of DNS](https://www.iana.org/domains) and
[coordination of IP address numbering](https://www.iana.org/numbers).

## IETF Secretariat

The administrative functions necessary to support the activities of
the IETF are performed by a Secretariat hired by the IETF LLC.
The secretariat handles much of the logistics of running the in-person
meetings, and is responsible for
maintaining the formal public record of the Internet standards
process {{IETFPROCS}}.

## Internet Research Task Force (IRTF)

While the IRTF generally follows IETF policies and procedures, it is not
directly involved in the Internet standards process.  It investigates topics
considered to be too uncertain, too advanced, or insufficiently
well-understood to be the subject of Internet standardization.  If an IRTF
activity generates a specification that is sufficiently stable to be
considered for Internet standardization, the specification is processed
through the IETF using the rules in this document.

A Working Group may ask an IRTF Research Group for advice or other input.

Details of the organization and operation of the IRTF, the ISRG,
and its Research Groups may be found in {{IRTF}}.

## The IETF Trust

The IETF Trust holds the copyrights for IETF documents including RFCs, and
copyright licenses for IETF contributions including Internet Drafts.  The
principles for the copyright licenses are described in {{COPYRIGHT}},
and the licenses themselves are online in the
[Trust Legal Provisions](https://trustee.ietf.org/documents/trust-legal-provisions/).

The trustees that govern the Trust are selected from the IETF community as
described in {{TRUSTEES}}.

## IETF Administration LLC (IETF LLC)

The IETF Administration Limited Liability Corporation provides
the corporate legal home for the IETF, the IAB, and the IRTF.
(The IETF Trust is a separate legal entity.)

The IETF LLC is responsible for supporting the ongoing operations
of the IETF, managing its finances and budget, and raising money.
It regularly reports to the community.
The LLC is the legal entity who signs contracts, including the
Secretariat, meeting hotels, tools development contractors, and so on.
The LLC also responds to legal requests; these are often subpoenas
in patent suits.

Selection of the LLC Board of Directors is defined in {{NOMCOM}}.

The IETF Executive Director handles the daily tasks and management,
and they are overseen by the LLC Board of Directors.

{{LLCLEGAL, Section 6}} describes the legal relationship between the
LLC and ISOC.

## Internet Society (ISOC)

ISOC plays a small but important role in the standards process.
It appoints the NomCom Chair, confirms IAB candidates,
and acts as the last resort in the appeals process.

The way in which the members of the ISOC Board of Trustees are
selected, and other matters concerning the operation of the Internet
Society, are described in the ISOC By-Laws {{ISOC}}.

# Security Considerations

This document introduces no new security considerations.

# IANA Considerations

This document has no IANA actions.

# Acknowledgements

The author of this document would like to thank the IETF participants at the
time {{RFC2028}} was written; in particular, those involved with the POISED
effort and the authors of that document, Richard Hovey and Scott Bradner.
