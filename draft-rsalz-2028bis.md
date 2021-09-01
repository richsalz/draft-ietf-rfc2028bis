---
docname: draft-rsalz-2028bis-latest
updates: 2028, 3668, 3979, 8717
title: The Entitities Involved in the IETF Standards Process
category: bcp
workgroup: ntp
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
  IAB: RFC2850
  IESG: RFC3710
  IETFPROCS: RFC2026
  IRTF: RFC2014
  NOMCOM: RFC8713
  RFC2028: RFC2028
  RFC5378: RFC5378
  RFC8721: RFC8721
  RFC8715: RFC8715
  RFC8719: RFC8719
  RFC5377: RFC5377
  WGPROCS: RFC2418
  IANA:
    target: https://www.ietf.org/standards/iana
    title: IANA
  ISOC:
    target: https://www.internetsociety.org/about-internet-society/governance-policies/by-laws/
    title: Amended and restatated By-Laws of the Internet Society

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
For clarity, this document does no use phrases like "Chair (or co-chair),"
unless strictly necessary to do so.

# Key individuals in the Process

This section describes the individual roles involved in the process.
It attempts to list the roles in the order in which they are involved
in the process, but no meaning is otherwise attached.

##  The Document Editor or Author {#doceditor}

Most Working Groups focus their efforts on one or more documents
that capture the results of the group's work.  A Working
Group generally designates a person to serve as the Editor
for a particular document.  The Document Editor is responsible for
ensuring that the contents of the document accurately reflect the
decisions that have been made by the working group.

When a document is composed and edited mainly by an individual,
they may be referred to as the Document Author. The distinction is
not significant.
This document will use the term Document Editor.

When a Document Editor is a Chair of the same working group, a
co-chair should manage the process around the document. If a co-chair is not
available, the process must be monitored carefully to ensure ensure that the
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

The details on the selection and responsibilites of an Working
Group chair can be found in {{WGPROCS}}.

## The Area Director

The Area Director assigned as the "Reponsible Area Director" for the
working will review the document after the working has approved its
last call, and when satisfied will request it to be put on the IESG
agenda.

## The Request for Comments Editor

The RFC publication series {{IETFPROCS}} is managed by an Editor
responsible both for the
mechanics of RFC publication and for upholding the
technical and editorial standards of the RFC series.

# Key organizations in the Process

The following organizations and organizational roles are involved in
the Internet standards process.

##  Internet Engineering Task Force (IETF)

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
each one under the the coordination of the Area Director.
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
three times a year {{RFC8719}}.
Active Working Group participation is possible without attending
any in-person meeting.

Participants in the IETF and its Working Groups must disclose
any relevant current or pending intellectual
property rights that are reasonably and personally known to the
participant if they participate in discussions about a specific
technology.
The full intellectual property policy is defined in {{RFC5378}}.

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

All members of the IESG are nominated by a nominations committee,
and are approved by the IAB.  See {{NOMCOM}} for a detailed
description of the Nomcom procedures. Other matters concerning its
organization and operation, are described in the IESG charter {{IESG}}.

##  Internet Architecture Board (IAB)

The IAB provides oversight of the architecture of the Internet and its
protocols.  The IAB must approve all IESG candidates put forward by the
IETF nominating committee.

The IAB provides oversight of the process used to create Internet
Standards and serves as an appeal board for complaints of improper
execution of the standards process {{IETFPROCS}}. In general it acts as source
of advice to the IETF and other entities mentioned here about
technical, architectural, procedural, and policy matters
pertaining to the Internet and its enabling technologies.

The members of the IAB are nominated by a nominations committee (the Nomcom),
and are approved by the ISOC board.  The IETF Chair is an ex-officio member.
See {{NOMCOM}} for a detailed description of the Nomcom procedures, Other
matters concerning its organization and operation, are described in the IAB
charter {{IAB}}.

##  IETF Secretariat

The administrative functions necessary to support the activities of
the IETF are performed by a Secretariat consisting of the IETF
Executive Director and his or her staff. The IETF Executive Director
is the formal point of contact for matters concerning any and all
aspects of the Internet standards process, and is responsible for
maintaining the formal public record of the Internet standards
process {{IETFPROCS}}.

##  Internet Society

The Internet Society (ISOC) is an international organization
concerned with the growth and evolution of the worldwide Internet and
with the social, political, and technical issues that arise from its
use.  The ISOC is an organization with individual and organizational
members.  The ISOC is managed by a Board of Trustees elected by the
worldwide individual membership.

Internet standardization is an organized activity of the ISOC, with
the Board of Trustees being responsible for ratifying the procedures
and rules of the Internet standards process {{IETFPROCS}}.

The way in which the members of the ISOC Board of Trustees are
selected, and other matters concerning the operation of the Internet
Society, are described in the ISOC By Laws {{ISOC}}.

##  Internet Assigned Numbers Authority

Many protocol specifications include numbers, keywords, and other
parameters that must be uniquely assigned.  Examples include version
numbers, protocol numbers, port numbers, and MIB numbers. The
Internet Assigned Numbers Authority (IANA) is responsible for
assigning the values of these protocol parameters for the Internet.
The IANA publishes tables of all currently assigned numbers and
parameters in RFCs entitled "Assigned Numbers" {{NOMCOM}}. The IANA
functions as the "top of the pyramid" for DNS and Internet Address
assignment establishing policies for these functions.

The functions of the IANA are performed by one or more individuals or
organizations selected in accordance with the procedures defined by
the IANA charter {{IANA}}.

## Internet Research Task Force

The Internet Research Task Force (IRTF) is not directly involved in
the Internet standards process.  It investigates topics considered to
be too uncertain, too advanced, or insufficiently well-understood to
be the subject of Internet standardization.  When an IRTF activity
generates a specification that is sufficiently stable to be
considered for Internet standardization, the specification is
processed through the IETF using the rules in this document.

The IRTF is composed of individual Research Groups, but its structure
and mode of operation is much less formal than that of the IETF, due
in part to the fact that it does not participate directly in the
Internet standards process.  The organization and program of work of
the IRTF is overseen by the Internet Research Steering Group (IRSG),
which consists of the chairs of the IRTF Working Groups.  Details of
the organization and operation of the IRTF and its Working Groups may
be found in {{IRTF}}.

An Working Group may ask an IRTF Research Group for advice or
other input.

## The IETF Trust

The IETF Trust holds the copyrights for IETF documents including RFCs, and
copyright licenses for IETF contribtions including Internet Drafts.  The
principles for the copyright licenses are described in {{RFC8721}} and
{{RFC5377}}, and the licenses themselves are in the Trust Legal Provisions on
the Trust's web site.

The trustees that govern the Trust are selected from the IETF community as
described in {{RFC8715}}.

# Security Considerations

Security is not addressed in this memo.

# IANA Considerations

None.

# Acknowledgements

The authors of this document would like to thank the IETF participants at the time
{{RFC2028}} was written; in particular, those involved with what was called the
POISED effort and the authors of that document, Richard Hovey
and Scott Bradner.
