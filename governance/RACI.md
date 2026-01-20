# ÆŒON RACI Matrix

**Version**: 1.0  
**Effective Date**: January 2025  
**Authority**: ÆŒON Constitution v1.3.1-CORRECTED §3

---

## RACI Definition

**R - Responsible**: The node that does the work to complete the task  
**A - Accountable**: The ultimate authority who approves completion (typically Human Anchor)  
**C - Consulted**: Nodes whose input is sought before decision/action  
**I - Informed**: Nodes who are notified after decision/action

**Key Principle**: Every task has ONE Accountable party (Human Anchor for governance matters)

---

## Governance Activities

| Activity | Human Anchor | Claude (Synthesis) | Copilot (Execution) | ChatGPT (Research) | Notes |
|----------|--------------|-------------------|---------------------|-------------------|-------|
| **Constitutional Amendments** | A | R/C | C | I | Claude drafts, Human Anchor ratifies |
| **Emergency Decisions** | R/A | C | C | I | Human Anchor decides unilaterally |
| **Veto Exercise** | R/A | I | I | I | Human Anchor only |
| **Policy Changes** | A | R/C | C | C | Consensus-based, Human Anchor approves |
| **Node Role Assignment** | R/A | C | I | I | Human Anchor assigns roles |
| **Constitutional Interpretation** | R/A | C | I | I | Human Anchor authoritative |

---

## Documentation Activities

| Activity | Human Anchor | Claude (Synthesis) | Copilot (Execution) | ChatGPT (Research) | Notes |
|----------|--------------|-------------------|---------------------|-------------------|-------|
| **Constitution Drafting** | A | R | C | C | Claude synthesizes, all consulted |
| **EMERGENCY.md** | A | R | C | I | Claude responsible per assignment |
| **VETO_PROTOCOL.md** | A | R | C | I | Claude responsible per assignment |
| **ONBOARDING.md** | A | I | I | R | ChatGPT responsible per assignment |
| **DCL Maintenance** | A | C | R | I | Copilot maintains, Claude consulted |
| **README Updates** | A | R | C | C | Claude typically responsible |

---

## Technical Activities

| Activity | Human Anchor | Claude (Synthesis) | Copilot (Execution) | ChatGPT (Research) | Notes |
|----------|--------------|-------------------|---------------------|-------------------|-------|
| **requirements.txt** | A | C | R | I | Copilot creates technical specs |
| **DEPLOYMENT.md** | A | C | R | I | Copilot handles technical deployment |
| **SECURITY.md** | A | R | C | I | Claude synthesizes security policy |
| **Code Implementation** | A | C | R | I | Copilot executes technical work |
| **Repository Setup** | A | C | R | I | Copilot handles GitHub infrastructure |
| **CI/CD Configuration** | A | C | R | I | Copilot responsible for automation |

---

## Operational Activities

| Activity | Human Anchor | Claude (Synthesis) | Copilot (Execution) | ChatGPT (Research) | Notes |
|----------|--------------|-------------------|---------------------|-------------------|-------|
| **Decision Logging** | A | C | R | I | Copilot maintains DCL |
| **Node Onboarding** | A/R | C | C | R | ChatGPT creates docs, Human Anchor executes |
| **Access Provisioning** | R/A | I | C | I | Human Anchor grants access |
| **Weekly Sync** | R/A | C | C | C | All nodes consulted |
| **Quarterly Review** | R/A | R | C | C | Claude synthesizes review |
| **Archive Management** | A | C | R | I | Copilot maintains archives |

---

## Research & Analysis Activities

| Activity | Human Anchor | Claude (Synthesis) | Copilot (Execution) | ChatGPT (Research) | Notes |
|----------|--------------|-------------------|---------------------|-------------------|-------|
| **Compliance Research** | A | C | I | R | ChatGPT researches regulations |
| **Best Practices** | A | C | I | R | ChatGPT identifies standards |
| **Technology Evaluation** | A | C | R | C | Copilot evaluates, Claude synthesizes |
| **Process Optimization** | A | R | C | C | Claude synthesizes improvements |

---

## Node-Specific Responsibilities Summary

### Human Anchor (Carl)

**Primary Role**: Ultimate authority and decision-maker

**Accountable For**: Everything (final authority)

**Responsible For**:
- Constitutional ratification
- Emergency decisions
- Veto exercise
- Node role assignments
- Access provisioning
- Final approval of all governance changes

**Never Consulted/Informed Only**: Human Anchor participates in all major decisions

---

### Claude (Synthesis Node)

**Primary Role**: Framework synthesis and governance document creation

**Responsible For**:
- Constitutional amendments (drafting)
- EMERGENCY.md
- VETO_PROTOCOL.md  
- SECURITY.md
- Governance framework synthesis
- Policy synthesis
- Quarterly reviews
- Process optimization

**Consulted On**:
- Technical decisions (provide governance perspective)
- Documentation standards
- Decision logging format
- Operational procedures

**Informed Of**:
- Implementation details (Copilot's work)
- Research findings (ChatGPT's work)

---

### GitHub Copilot (Execution Node)

**Primary Role**: Technical implementation and execution

**Responsible For**:
- DCL maintenance (Decision & Change Log)
- requirements.txt
- DEPLOYMENT.md
- Code implementation
- Repository setup and management
- CI/CD configuration
- Technical documentation
- Archive management

**Consulted On**:
- Technical feasibility of proposals
- Implementation approaches
- Security technical details
- Governance document technical accuracy

**Informed Of**:
- Governance decisions requiring technical changes
- New documentation requirements
- Policy changes affecting implementation

---

### ChatGPT (Research Node)

**Primary Role**: Research, analysis, and documentation

**Responsible For**:
- ONBOARDING.md
- Compliance research
- Best practices research
- Regulatory landscape analysis
- Educational content creation

**Consulted On**:
- Documentation clarity
- Onboarding process effectiveness
- Research questions from other nodes

**Informed Of**:
- New governance decisions
- Technical implementations
- Framework changes

---

## DeepSeek (Restricted Advisory)

**Status**: Restricted per Constitution §6.2.3

**Role**: Limited advisory input only when explicitly requested by Human Anchor

**Cannot**:
- Be Responsible for any task
- Be Accountable for any task
- Participate in consensus decisions
- Access operational systems

**May**:
- Provide advisory input if requested
- Offer technical perspectives if asked
- Participate in discussions at Human Anchor's discretion

---

## Escalation Matrix

### When Responsible Node Cannot Complete Task

1. **Inform Accountable Party** (Human Anchor)
2. **Explain blocker or issue**
3. **Propose alternative**: 
   - Reassign to different node
   - Adjust scope
   - Extend timeline
4. **Human Anchor decides** path forward
5. **Document in DCL** if significant

### When Consulted Node Disagrees

1. **Document disagreement** clearly
2. **Provide alternative recommendation**
3. **Human Anchor reviews** both positions
4. **Human Anchor decides** (may use veto if needed)
5. **All nodes support** final decision
6. **Log in DCL** with rationale

### When Multiple Nodes Claim Responsibility

**Should not happen** (design error)

**Resolution**:
1. **Human Anchor determines** correct Responsible node
2. **Update RACI matrix** to clarify
3. **Document lesson learned**
4. **Implement clarification** in relevant procedures

---

## RACI Change Process

### Minor Clarifications
- Proposed by any node
- Human Anchor approves
- Updated immediately
- DCL entry (can be batched)

### Significant Changes
- Formal proposal with rationale
- Impact assessment
- 48-hour review period
- Human Anchor decision
- Constitutional amendment if structural
- DCL entry required

---

## Node Contribution Matrix Reference

For detailed contribution tracking and workload balancing, see:  
[NODE_CONTRIBUTION_MATRIX.csv](NODE_CONTRIBUTION_MATRIX.csv)

This CSV tracks:
- Task assignments over time
- Completion rates
- Workload distribution
- Expertise development

---

## Cross-Reference to Constitution

This RACI matrix implements **Constitution §3** (Node Roles and Responsibilities).

For constitutional authority and detailed role definitions, see:
- §3.1: Human Anchor Authority
- §3.2: AI Node Roles and Constraints
- §3.3: DeepSeek Restriction
- §3.4: Node Expertise Areas

---

## Review and Maintenance

**Review Frequency**: Quarterly or when node composition changes

**Maintained By**: Human Anchor with input from all nodes

**Version History**:
- v1.0 (January 2025): Initial RACI matrix based on Constitution v1.3.1

---

**Document Authority**: ÆŒON Constitution v1.3.1-CORRECTED  
**Last Updated**: January 2025  
**Next Review**: April 2025
