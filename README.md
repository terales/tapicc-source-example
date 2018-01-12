# Work Package 4: API Specification

COTI is solid and uses a three‐level model which should be considered for
TAPICC as well. The COTI API is based on the SOAP protocol, which is not preferred by most
software developers. Also, it is a pure PUSH model, meaning the CMS pushes content to the
L10N tools. TAPICC should also add a pull concept, so the L10N tools can pull tasks from the
previous systems and push them back.

## Goals:
* Selection of the transfer protocols (REST, SOAP, JSON...).
* Define whether we want to support three levels, just like COTI
(file only, hot folders, API calls).
* Extend COTI to also PULL translation jobs through the supply
chain, not only PUSH.
* Concrete API calls, plus sample implementation modules
(code snippets). Much of this can be taken from COTI.

## Executive decision

* Transfer protocols. Current specification aims to target REST transfer protocol at first.
