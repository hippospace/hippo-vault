Hippo Vault

Hippo Vault is an on-chain locking and escrow system designed to enforce long-term alignment, transparency, and capital discipline across the Hippo ecosystem.

It is used to lock tokens, manage release schedules, and make commitments verifiable on-chain.

Overview

The Hippo Vault exists to solve a common problem in crypto projects:

Trust should be enforced by code, not promises.

Instead of relying on social assurances or off-chain agreements, the Vault provides a verifiable mechanism for locking tokens with predefined rules that cannot be changed arbitrarily.

Core Concepts
Vault

A Vault is a program-controlled account that holds tokens under strict conditions.

Once tokens are deposited:

They cannot be moved freely

Release conditions are enforced on-chain

All balances and schedules are publicly verifiable

Locks

A Lock defines how and when tokens can be released from the Vault.

Each lock includes:

Token mint

Amount locked

Beneficiary address

Unlock schedule

Release rules

Locks are immutable once created.

Lock Types
Time-Based Locks

Tokens are locked until a specific timestamp or block height.

Use cases:

Team allocations

Long-term incentives

Delayed distributions

Vesting Locks

Tokens unlock gradually over time according to a predefined schedule.

Use cases:

Contributor compensation

Protocol incentives

Long-term alignment

Cliff Locks

Tokens remain fully locked until a cliff date, after which they unlock either fully or begin vesting.

Use cases:

Early contributors

Strategic allocations

Risk-aligned commitments

How It Works

Tokens are deposited into the Hippo Vault

A lock configuration is created on-chain

The Vault enforces all lock rules programmatically

Tokens are released only when conditions are met

All activity is publicly visible and auditable

There are no admin overrides or backdoors.

Transparency & Security

All locks are verifiable on-chain

Token balances and schedules are publicly readable

Unlock events are deterministic and predictable

No manual intervention required

The Vault is designed to reduce trust assumptions as much as possible.

Why Locks Matter

Locks are not about restriction - they are about credibility.

They ensure:

Teams cannot exit early

Allocations are honored as stated

Long-term builders are aligned

Users can verify commitments themselves

Current Usage

The Hippo Vault is currently used to:

Lock HIPPO token allocations

Enforce long-term release schedules

Demonstrate alignment with the Solana Index roadmap

Specific lock addresses and parameters are documented separately for clarity.
