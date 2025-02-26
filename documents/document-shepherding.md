---
title: Document shepherding
description: A short informal description of how shepherds help documents progress through the working group process.
published: true
date: 2022-08-12T15:14:33.940Z
tags: 
editor: markdown
dateCreated: 2022-05-09T14:28:44.149Z
---

# About document shepherding
Someone—sometimes a Working Group Chair or Secretary but often another designated individual—has to take responsibility for pushing a document along. Firstly, to the point where the working group (WG) has consensus, and then through the Internet Engineering Steering Group (IESG) review, and finally through the RFC Editor (and IANA) processing. A document won't shepherd itself; the Area Director has to worry about many other documents. Authors sometimes vanish. 

More detail about the document shepherding process can be found in:
* [RFC 4858](https://www.rfc-editor.org/rfc/rfc4858.html)
* [A description of the document lifecyle](/documents/lifecycle)

## Document shepherd writeup

One of the key things a document shepherd does is to write up the history of a document's path through the Working Group (WG) process. The purpose of the shepherd writeup is to make sure that the document has been properly reviewed and to provide information to the IESG for use in IESG Evaluation. The IESG has provided a [writeup template for individual submissions](https://datatracker.ietf.org/doc/shepherdwriteup-template/individual) and a [writeup template for working group submissions](https://datatracker.ietf.org/doc/shepherdwriteup-template/workinggroup) as a guides.

The document shepherd writeup is not subject to working group consensus. Quite the opposite, it's the place for the shepherd to communicate with the Area Directors, and SHOULD include information that the shepherd thinks is important, even or especially if the WG isn't in agreement.

## Intended status

The writeup should be explicit about which document the writeup is about  and its target status (e.g. Informational, Proposed Standard). Working Group charters or milestones are sometimes unclear about the intended status of a document. And, the WG may decide to change the intended status based on consensus (should be discussed with your AD). Therefore, to avoid problems with this and also make it clear in the WG process what is happening it's strongly recommended that the WG chairs do the following.

* Check that WG documents have the right intended status header. This is occasionally in error.
* When performing a WG last call, write explicitly in the WG last call message what the intended status is.
* When doing the shepherd writeup, be explicit about which document the writeup is about, and what the target status is.