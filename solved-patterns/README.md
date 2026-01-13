# Solved Patterns

Code examples demonstrating architectural fixes to historic blockchain problems using MOI's participant-centric model.

## 🔒 The Re-Entrancy Fix

**Problem**: The DAO Hack (2016)
- Traditional smart contracts vulnerable to re-entrancy attacks
- Global state allows recursive calls to drain funds

**MOI Solution**:
- Participant-centric architecture prevents re-entrancy
- Each participant has isolated state
- [Example Code](./re-entrancy-fix.md) - [Link TBD]

## ⚡ The Scalability Fix

**Problem**: The CryptoKitties Incident (2017)
- Single global state creates bottlenecks
- Network congestion from one popular dApp

**MOI Solution**:
 
- [Example Code](./scalability-fix.md) - [Link TBD]

## ✅ The Compliance Fix

**Problem**: The Tornado Cash Dilemma
- Privacy vs. compliance conflict
- Global state makes selective compliance difficult

**MOI Solution**:
- Context-aware logic
- Participant-specific compliance rules
- Policy enforcement at the logic level
- [Example Code](./compliance-fix.md) - [Link TBD]

## 📚 Additional Patterns

- **State Bloat Solution** - [Link TBD]
- **Gas Optimization Patterns** - [Link TBD]
- **Security Best Practices** - [Link TBD]

## 🤝 Contributing

Have a pattern to add? Submit a PR with:
- The problem it solves
- Traditional blockchain approach
- MOI's solution
- Working code example
