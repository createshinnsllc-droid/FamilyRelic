# Continuity Protocol: Implementation Logic (v1.1)

## 1. The Verification Stack (Multi-Signal)
The protocol must not rely on a single point of failure. It uses a weighted "Inactivity Score."

### Signals:
- **Direct Pings:** Weekly encrypted check-ins via Telegram/Signal. (Weight: 40%)
- **System Activity:** Interaction with OpenClaw, Cursor Cloud Agents (iOS/web), or authorized machines. (Weight: 30%) — *Note 2026-09-12: Mac decommissioned; local-machine signal may be zero until a new host is online.*
- **Social/External Presence:** Verified activity on designated "Living Proof" channels. (Weight: 20%)
- **Trusted Oracle:** A "Human Witness" (Heir) who can confirm status if other signals fail. (Weight: 10%)

## 2. The Grace Period
Once the "Inactivity Score" hits 100% (indicating potential absence), a 30-day "Grace Period" begins.
- **Day 1-7:** Daily high-priority pings to all primary devices.
- **Day 8-14:** Notifications sent to "Heirs" to verify the creator's status.
- **Day 15-30:** Final countdown. If no override is received, the Release Phase initiates.

## 3. The Release Phase (The Handover)
1. **Asset Unlock:** Primary encryption keys are decrypted and delivered to Heirs.
2. **Essence Activation:** The "Relic Agent" transitions from a Private Assistant to a Legacy Guide for the family.
3. **Sovereign Handover:** All cloud-tethered data is finalized and archived to the family's local-first storage.

---
*Status: Draft Logic for WHEELJACK to begin prototyping.*
