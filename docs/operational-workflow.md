# Operational Workflow

The Embric protocol follows a structured, modular workflow to convert actions into tokenized value. Every interaction flows through clearly defined stages — from input to validation to reward.

---

## 1. Action Initiation

A user, node, or system performs a utility-focused action such as:

* Submitting data
* Running compute
* Validating a task
* Triggering governance

These are recorded as on-chain or off-chain events.

---

## 2. Agent Detection

Embric agents monitor for valid signals using:

* Task schemas
* Signal patterns
* Identity + stake combinations

If the input matches a reward condition, the agent flags it as **processable**.

---

## 3. Validation Phase

Inputs are validated using:

* On-chain confirmation logic
* Peer consensus (if required)
* Optional ZK verification layers

Invalid or duplicated actions are rejected automatically.

---

## 4. Reward Trigger

Once validated, the protocol:

* Calculates BRIC reward
* Assigns it to the contributor’s address
* Emits a reward receipt

The reward is proportional to the utility weight + pool logic.

---

## 5. Post-Processing & Sync

All reward events are:

* Logged on-chain
* Synced to Embric dashboards + RPCs
* Auditable for retroactive governance or review

---

This modular pipeline ensures that Embric’s reward system is **predictable, secure, and verifiable.**
