# BizCo Brokerage Information System – Messaging Infrastructure

## Overview
An academic team project for the Software Architecture course. The project proposes a Messaging Infrastructure Layer for BizCo's Brokerage Information System (BIS).

The proposed design addresses communication between the main system and three existing branch systems:
- Commercial Property System (CPS)
- Residential Property System (RPS)
- Brokerage Billing System (BBS)

## Architectural Approach
The project applies the **Dynamic Routing Pattern (SOA)** to route requests to the appropriate existing service without direct coupling.

## Main Components
- Business Logic Layer
- Messaging Infrastructure
- Message Router
- Routing Rules
- Service Adapters
- Existing branch systems (CPS, RPS, and BBS)

## Quality Attributes Considered
- Security
- Performance
- Interoperability
- Availability
- Modifiability
- Maintainability

## Architectural Tactics
- Encapsulation
- Use an Intermediary
- Maintain Semantic Coherence
- Abstract Common Services

## Project Type
Academic Team Project

## Course
Software Architecture
