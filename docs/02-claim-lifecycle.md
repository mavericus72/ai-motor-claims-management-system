````md
# Claim Lifecycle

```mermaid
flowchart TD
    DRAFT --> SUBMITTED
    SUBMITTED --> DOCUMENT_PENDING
    DOCUMENT_PENDING --> INSPECTION_PENDING
    INSPECTION_PENDING --> UNDER_REVIEW

    UNDER_REVIEW --> AI_ASSESSMENT_COMPLETE
    AI_ASSESSMENT_COMPLETE --> KEPT_OPEN
    KEPT_OPEN --> AI_KEPT_OPEN_ASSESSMENT_COMPLETE
    AI_KEPT_OPEN_ASSESSMENT_COMPLETE --> UNDER_REPAIR_PHOTOS
    UNDER_REPAIR_PHOTOS --> REINSPECTION_PHOTOS
    REINSPECTION_PHOTOS --> SETTLEMENT_PENDING
    SETTLEMENT_PENDING --> APPROVED
    APPROVED --> LIABILITY_CALCULATION
    LIABILITY_CALCULATION --> CLAIM_SETTLEMENT
    CLAIM_SETTLEMENT --> CLOSED

    UNDER_REVIEW --> REJECTED
    REJECTED --> REJECTION_REASON
    REJECTION_REASON --> CLOSED
```
````




## State Flow


| Status                           | Meaning                                                                              |
| -------------------------------- | ------------------------------------------------------------------------------------ |
| DRAFT                            | Claim registration started but not submitted                                         |
| SUBMITTED                        | Customer submitted claim                                                             |
| DOCUMENT_PENDING                 | Mandatory documents are missing                                                      |
| INSPECTION_PENDING               | Initial inspection and image analysis pending                                        |
| UNDER_REVIEW                     | Claims team reviewing claim details                                                  |
| AI_ASSESSMENT_COMPLETE           | AI damage assessment completed                                                       |
| KEPT_OPEN                        | Claim kept open for internal/hidden damage inspection after dismantling              |
| AI_KEPT_OPEN_ASSESSMENT_COMPLETE | AI assessment completed for newly identified internal damages and labor requirements |
| UNDER_REPAIR_PHOTOS              | Garage uploads repair progress photos                                                |
| REINSPECTION_PHOTOS              | Final repair photos submitted for verification                                       |
| SETTLEMENT_PENDING               | Awaiting settlement and approval workflow                                            |
| APPROVED                         | Claim approved                                                                       |
| LIABILITY_CALCULATION            | Liability report and payable amount calculation in progress                          |
| CLAIM_SETTLEMENT                 | Settlement amount processed and released                                             |
| REJECTED                         | Claim rejected                                                                       |
| REJECTION_REASON                 | Rejection rationale documented and communicated                                      |
| CLOSED                           | Claim lifecycle completed                                                            |
