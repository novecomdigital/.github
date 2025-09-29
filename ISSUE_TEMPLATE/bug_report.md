name: Bug report
description: Report a defect
labels: ["bug","severity:medium","P2"]
body:
  - type: textarea
    id: steps
    attributes:
      label: Steps to reproduce
  - type: textarea
    id: expected
    attributes:
      label: Expected result
  - type: textarea
    id: actual
    attributes:
      label: Actual result
  - type: input
    id: env
    attributes:
      label: Env (Preview/Staging/Prod)
