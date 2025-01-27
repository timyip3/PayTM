# Interviews from PayTM

It consists of 3 rounds: 1. discussing with Engineering Director, 2. 1 DSA question 3. System Design

## Discussing with Engineering Director
The director asked about your knowledge about CAP theorm, Cassandra, DB indexing, service communication (REST), fault-handling on services (retry mechanism with backoff).

## DSA Question
1-hour Leetcode-style coding session
I asked to implement LRU Cache. This should be easy to pass (I completed within 30mins) if well-prepared.

## System Design
Design a system to validate the payment to be processed.

Functional Requirements:
1. threshold rule can be customised by operational team (e.g.: 100 in total amount from user over past 24 hours etc.)
2. validate the payment to proceed based on user data (e.g.: location, payment etc.)

Non-functional Requirements:
1. High throughput
2. low latency
