
<p align="center">
   <img width="704" height="367" alt="image" src="https://github.com/user-attachments/assets/8291009e-175c-45a0-9c50-5ea09082d78c" />
</p>




CHAINARB
Smart contract engineering and security auditing for teams building the next generation of on-chain infrastructure.

We operate at the intersection of two disciplines most agencies treat separately: protocol development and adversarial security review. Every engineer who ships code here has also broken code professionally — our development process is informed by how contracts actually get exploited, not just how they're supposed to work.

Engineering Standards:

Test-first, invariant-driven. Every stateful contract ships with a Foundry invariant/fuzz suite covering core solvency and access-control properties before a single line of frontend code touches it.
Static + symbolic analysis as a gate, not a formality. Slither and Echidna (or Halmos for symbolic checks) run in CI on every PR; findings block merge until triaged.
Gas is a correctness concern, not a nice-to-have. We benchmark gas regressions in CI and document every optimization's assembly-level tradeoff.
No single points of failure in review. Internal audits are peer-reviewed by a second engineer who did not write the code under review.
Engagement Types
Service	Typical Scope


Protocol Development	- Full-cycle smart contract build, from spec to mainnet deployment & monitoring
Security Audit	- Manual review + automated analysis + PoC exploits for Critical/High findings, delivered as a formal report
Gas Optimization	- Bytecode-level refactor of existing deployed or pre-launch contracts, benchmarked before/after
Retainer / Fractional CTO	- Ongoing architecture review, code review, and security oversight for funded teams
Audit & Contract Inquiry Protocol
Scoping call — share your repo, docs, and target deployment timeline.
Fixed-fee proposal — scoped by LOC, complexity, and attack surface (oracles, external calls, upgradeability), not an hourly guess.
Engagement — for audits: findings delivered incrementally as Critical/High issues are found, not withheld until a final report; for development: milestone-based delivery with test coverage as an acceptance criterion.
Final deliverable — audit report (Trail-of-Bits-style severity classification) or deployed, documented, tested codebase with a handoff call.

📬 Start an engagement: sumanraj@chainarb.co — include your repo link, target chain(s), and whether you need development, audit, or both.
