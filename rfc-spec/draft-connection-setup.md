---
title: Quantum Connection Setup (QCS)
abbrev: QCS
docname: draft-connection-setup-00
date: 2023-04-21
category: info

stream: independent
ipr: trust200902
area: Quantum
workgroup: AQUA
keyword: Internet-Draft

stand_alone: yes
pi: [toc, sortrefs, symrefs]

author:
 -
    ins: R. Van Meter
    name: Rodney Van Meter
    organization: Keio University
    street: 5322 Endo
    region: Fujisawa, Kanagawa
    code: 252-0882
    country: Japan
    email: rdv@sfc.wide.ad.jp

normative:
  RFC2119:
  RFC5151:
  RFC6001:
  I-D.setup:
    target: https://github.com/sfc-aqua/draft-quantum-connection-setup
    title: Connection Setup in a Quantum Network
    author:
      name: Rodney Van Meter
      ins: R. Van Meter
    author:
      name: Takaaki Matsuo
      ins: T. Matsuo
    date: 2021-03-18
  QNA:
    target: https://github.com/sfc-aqua/network-architecture-specifications
    title: Quantum Network Architecture
    author:
      name: Rodney Van Meter
      ins: R. Van Meter
    date: 2023-03-18
  marchese-tannenbaum-van-steen-summary:
    target: https://csis.pace.edu/~marchese/CS865/Lectures/Chap5/Chapter5a.htm
    title: CS865 – Distributed Software Development, Lecture 5, Tannenbaum and Van Steen – Chapter 5
    author:
      name: Francis T. Marchese
      ins: F. T. Marchese

informative:
  RFC9340:
  wehner-science: DOI.10.1126/science.aam9288
  cocori-ms-thesis:
    target: TBD
    title: RuLa A Programming Language for RuleSet-based Quantum Repeaters
    author:
      name: Ryosuke Satoh
      ins: R. Satoh
    date: 2023-02-01
  rdv-qce-arch: DOI.10.1109/QCE53715.2022.00055
  altepeter-tomography: DOI.10.1016/S1049-250X(05)52003-2
  eisert-certification: DOI.10.1038/s42254-020-0186-4
  oka-qcit: DOI.10.1109/GLOCOMW.2016.7848802

--- abstract

This documents specifies the Connection Setup Process for quantum network nodes.

--- middle

Introduction        {#intro}
============


Two-Path Connection Setup
============


Sequence
------

Sync and Async mode
-----


Connection Setup Request
===========


Request Body
-----



Icon
-----


Connection Setup Acknowloegement
=====


Ack message body
---  

RuleSet Distribution
--- 

RuleSet Rewriting
---



--- back


