# Claim Lifecycle

## States

DRAFT

SUBMITTED

DOCUMENT_PENDING

INSPECTION_PENDING

UNDER_REVIEW

AI_ASSESSMENT_COMPLETE

KEPT_OPEN
  
AI_KEPT_OPEN_ASSESSMENT_COMPLETE
  
UNDER_REPAIR_PHOTOS
  
REINSPECTION_PHOTOS
  
SETTLEMENT_PENDING
  
APPROVED
  
LIABILITY_CALCULATION
  
CLAIM_SETTLEMENT
  
CLOSED

OR


REJECTED
  
REJECTION_REASON

CLOSED



## State Flow


```html
<h2>State Flow</h2>

<table>
  <thead>
    <tr>
      <th width="30%">Status</th>
      <th width="70%">Meaning</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td><code>DRAFT</code></td>
      <td>Claim registration started but not submitted</td>
    </tr>
    <tr>
      <td><code>SUBMITTED</code></td>
      <td>Customer submitted claim</td>
    </tr>
    <tr>
      <td><code>DOCUMENT_PENDING</code></td>
      <td>Mandatory documents are missing</td>
    </tr>
    <tr>
      <td><code>INSPECTION_PENDING</code></td>
      <td>Initial inspection and image analysis pending</td>
    </tr>
    <tr>
      <td><code>UNDER_REVIEW</code></td>
      <td>Claims team reviewing claim details</td>
    </tr>
    <tr>
      <td><code>AI_ASSESSMENT_COMPLETE</code></td>
      <td>AI damage assessment completed</td>
    </tr>
    <tr>
      <td><code>KEPT_OPEN</code></td>
      <td>Claim kept open for internal/hidden damage inspection after dismantling</td>
    </tr>
    <tr>
      <td><code>AI_KEPT_OPEN_ASSESSMENT_COMPLETE</code></td>
      <td>AI assessment completed for newly identified internal damages and labor requirements</td>
    </tr>
    <tr>
      <td><code>UNDER_REPAIR_PHOTOS</code></td>
      <td>Garage uploads repair progress photos</td>
    </tr>
    <tr>
      <td><code>REINSPECTION_PHOTOS</code></td>
      <td>Final repair photos submitted for verification</td>
    </tr>
    <tr>
      <td><code>SETTLEMENT_PENDING</code></td>
      <td>Awaiting settlement and approval workflow</td>
    </tr>
    <tr>
      <td><code>APPROVED</code></td>
      <td>Claim approved</td>
    </tr>
    <tr>
      <td><code>LIABILITY_CALCULATION</code></td>
      <td>Liability report and payable amount calculation in progress</td>
    </tr>
    <tr>
      <td><code>CLAIM_SETTLEMENT</code></td>
      <td>Settlement amount processed and released</td>
    </tr>
    <tr>
      <td><code>REJECTED</code></td>
      <td>Claim rejected</td>
    </tr>
    <tr>
      <td><code>REJECTION_REASON</code></td>
      <td>Rejection rationale documented and communicated</td>
    </tr>
    <tr>
      <td><code>CLOSED</code></td>
      <td>Claim lifecycle completed</td>
    </tr>
  </tbody>
</table>
```


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
