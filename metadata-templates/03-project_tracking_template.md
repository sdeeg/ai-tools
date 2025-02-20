# Project Tracking

## Metadata
```yaml
last_updated: [YYYY-MM-DD]
sprint: [Sprint Name]
sprint_goal: [Sprint Goal]
sprint_end: [YYYY-MM-DD]
overall_progress: [%]
critical_tasks:
  - [Task 1]
  - [Task 2]
  - [Task 3]
documentation_version: [Version]
```

## Task Board
```yaml
backlog:
  high_priority:
    - id: [TASK-1]
      title: [Task Title]
      status: [TODO|IN_PROGRESS|DONE]
      owner: [Owner]
      estimate: [Time Estimate]
      dependencies: []
      subtasks:
        - [Subtask 1] [TODO|DONE]
        - [Subtask 2] [TODO|DONE]

    - id: [TASK-2]
      title: [Task Title]
      status: [TODO|IN_PROGRESS|DONE]
      owner: [Owner]
      estimate: [Time Estimate]
      dependencies: [TASK-1]
      subtasks:
        - [Subtask 1] [TODO|DONE]
        - [Subtask 2] [TODO|DONE]

  medium_priority:
    - id: [TASK-3]
      title: [Task Title]
      status: [TODO|IN_PROGRESS|DONE]
      owner: [Owner]
      estimate: [Time Estimate]
      dependencies: []
      subtasks:
        - [Subtask 1] [TODO|DONE]
        - [Subtask 2] [TODO|DONE]

  low_priority:
    - id: [TASK-4]
      title: [Task Title]
      status: [TODO|IN_PROGRESS|DONE]
      owner: [Owner]
      estimate: [Time Estimate]
      dependencies: []
      subtasks:
        - [Subtask 1] [TODO|DONE]
        - [Subtask 2] [TODO|DONE]
```

## Implementation Progress
```mermaid
graph TD
    A[Component 1] -->|Status| B[Component 2]
    B -->|Status| C[Component 3]
    C -->|Status| D[Component 4]
    D -->|Status| E[Component 5]
    
    style A fill:#[Color]
    style B fill:#[Color]
    style C fill:#[Color]
    style D fill:#[Color]
    style E fill:#[Color]
```

## Sprint Metrics
```yaml
sprint_metrics:
  planned_points: [Points]
  completed_points: [Points]
  remaining_points: [Points]
  velocity: [Points/Sprint]
  burndown:
    - date: [YYYY-MM-DD]
      remaining: [Points]
    - date: [YYYY-MM-DD]
      remaining: [Points]
```

## Component Progress
```yaml
components:
  component_1:
    status: [Status]
    progress: [%]
    remaining_work:
      - [Task 1]
      - [Task 2]
    blockers: []

  component_2:
    status: [Status]
    progress: [%]
    remaining_work:
      - [Task 3]
      - [Task 4]
    blockers: []
```

## Testing Progress
```yaml
test_coverage:
  unit_tests:
    implemented: [Number]
    planned: [Number]
    coverage: [%]
    priority: [Priority]

  integration_tests:
    implemented: [Number]
    planned: [Number]
    coverage: [%]
    priority: [Priority]

  e2e_tests:
    implemented: [Number]
    planned: [Number]
    coverage: [%]
    priority: [Priority]
```

## Development Tasks
```yaml
tasks:
  implementation:
    - id: [TASK-5]
      title: [Task Title]
      status: [Status]
      priority: [Priority]
      dependencies: []

  optimization:
    - id: [TASK-6]
      title: [Task Title]
      status: [Status]
      priority: [Priority]
      dependencies: [TASK-5]

  testing:
    - id: [TASK-7]
      title: [Task Title]
      status: [Status]
      priority: [Priority]
      dependencies: []
```

## Risk Assessment
```yaml
risks:
  technical:
    - id: [RISK-1]
      description: [Description]
      severity: [Severity]
      mitigation: [Mitigation Strategy]

    - id: [RISK-2]
      description: [Description]
      severity: [Severity]
      mitigation: [Mitigation Strategy]

  schedule:
    - id: [RISK-3]
      description: [Description]
      severity: [Severity]
      mitigation: [Mitigation Strategy]
```

## Development Workflow
```mermaid
graph LR
    A[Development] -->|Gate| B[Code Review]
    B -->|Gate| C[Integration]
    C -->|Gate| D[Deployment]
    
    style A fill:#[Color]
    style B fill:#[Color]
    style C fill:#[Color]
    style D fill:#[Color]
```

## Next Actions
### Immediate (24 Hours)
1. [Action 1]
   - [Detail 1.1]
   - [Detail 1.2]

2. [Action 2]
   - [Detail 2.1]
   - [Detail 2.2]

### Short Term (Week)
1. [Action 3]
   - [Detail 3.1]
   - [Detail 3.2]

2. [Action 4]
   - [Detail 4.1]
   - [Detail 4.2]

### Medium Term (Sprint)
1. [Action 5]
   - [Detail 5.1]
   - [Detail 5.2]

## Dependencies
```mermaid
graph TD
    A[Component 1] -->|Requires| B[Component 2]
    B -->|Requires| C[Component 3]
    C -->|Requires| D[Component 4]
    B -->|Requires| E[Component 5]
    
    style A fill:#[Color]
    style B fill:#[Color]
    style C fill:#[Color]
    style D fill:#[Color]
    style E fill:#[Color]
```

## Resource Tracking
```yaml
resources:
  development:
    allocated: [true|false]
    focus: [Focus Area]
    next: [Next Focus]

  testing:
    allocated: [true|false]
    focus: [Focus Area]
    next: [Next Focus]

  documentation:
    allocated: [true|false]
    focus: [Focus Area]
    next: [Next Focus]
```

See `implementation_state.md` for detailed implementation status and `architecture.md` for system design details.
