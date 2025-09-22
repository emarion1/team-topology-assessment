# Team Topology Scoring & Analysis Framework

## Overview
This framework provides a systematic approach to analyze survey responses, interview data, and dependency mappings to classify teams and identify optimization opportunities.

---

## 1. Team Type Classification Scoring

### Scoring Method
Each team type receives a score from 0-100 based on weighted criteria. The highest scoring type becomes the primary classification.

### Stream-Aligned Team Score
**Weight: Customer Focus (40%) + Autonomy (35%) + End-to-End Ownership (25%)**

#### Customer Focus (40 points max)
- Direct customer contact: Survey A1.1 × 8 points
- Customer impact measurement: Survey A1.2 × 8 points
- Customer-tied success metrics: Survey A1.3 × 8 points
- Direct user feedback: Survey A1.4 × 8 points
- Independent deployment: Survey B1.2 × 8 points

#### Autonomy (35 points max)
- Technology choice freedom: Survey B1.1 × 7 points
- Process control: Survey B1.3 × 7 points
- Priority setting: Survey B1.4 × 7 points
- Low external dependencies: (5 - Survey B2.1) × 7 points
- Minimal coordination needs: (5 - Survey B2.2) × 7 points

#### End-to-End Ownership (25 points max)
- Full lifecycle ownership: Interview data × 25 points

**Stream-Aligned Score = Customer Focus + Autonomy + End-to-End Ownership**

### Platform Team Score
**Weight: Internal Service Provision (50%) + Reusability (30%) + Self-Service (20%)**

#### Internal Service Provision (50 points max)
- Internal customers: Survey A2.1 × 10 points
- Reusable services: Survey A2.2 × 10 points
- Enabling productivity: Survey A2.3 × 10 points
- Reducing duplication: Survey A2.4 × 10 points
- X-as-a-Service delivery: Survey C3.1 × 10 points

#### Reusability (30 points max)
- Self-service onboarding: Survey C3.2 × 10 points
- Service contracts/SLAs: Survey C3.4 × 10 points
- Multiple consumers: Dependency mapping data × 10 points

#### Self-Service (20 points max)
- Minimal involvement required: Survey C3.3 × 20 points

**Platform Score = Internal Service Provision + Reusability + Self-Service**

### Enabling Team Score
**Weight: Knowledge Transfer (60%) + Coaching Focus (40%)**

#### Knowledge Transfer (60 points max)
- Coaching time: Survey A3.1 × 15 points
- Technology adoption help: Survey A3.2 × 15 points
- Documentation creation: Survey A3.3 × 15 points
- Temporary embedding: Survey A3.4 × 15 points

#### Coaching Focus (40 points max)
- Capability building focus: Interview assessment × 40 points

**Enabling Score = Knowledge Transfer + Coaching Focus**

### Complicated Subsystem Score
**Weight: Specialization (50%) + Complexity (30%) + Efficiency (20%)**

#### Specialization (50 points max)
- Specialized knowledge: Survey A4.1 × 12.5 points
- Duplication inefficiency: Survey A4.2 × 12.5 points
- Complex algorithms: Survey A4.3 × 12.5 points
- High onboarding time: Survey A4.4 × 12.5 points

#### Complexity (30 points max)
- High cognitive load: Survey D1.2 × 15 points
- External expertise needs: Survey D1.4 × 15 points

#### Efficiency (20 points max)
- Black box preference: Interview assessment × 20 points

**Complicated Subsystem Score = Specialization + Complexity + Efficiency**

---

## 2. Interaction Pattern Analysis

### Collaboration Mode Indicators
- High meeting overhead: Survey C2.1 > 3
- Shared repositories: Survey C1 includes shared code
- Joint planning: Survey C1 includes joint planning
- High communication frequency: Daily interactions > 3 teams

### X-as-a-Service Mode Indicators
- Well-defined APIs: Survey C3.1 > 3
- Self-service capability: Survey C3.2 > 3
- Minimal direct involvement: Survey C3.3 > 3
- Service contracts: Survey C3.4 > 3

### Facilitating Mode Indicators
- High coaching time: Survey A3.1 > 3
- Knowledge transfer focus: Survey A3.2 > 3
- Temporary embedding: Survey A3.4 > 3
- Capability building: Survey A3.3 > 3

---

## 3. Health Metrics & Red Flags

### Team Health Score (0-100)
**Components: Autonomy (25%) + Cognitive Load (25%) + Communication Efficiency (25%) + Value Delivery (25%)**

#### Autonomy Health (25 points)
- Technology freedom: Survey B1.1 × 5
- Process control: Survey B1.3 × 5
- Deployment control: Survey B1.2 × 5
- Priority setting: Survey B1.4 × 5
- Low blocking: (5 - Survey B2.1) × 5

#### Cognitive Load Health (25 points)
- Manageable complexity: (5 - Survey D1.2) × 8.33
- Low context switching: (5 - Survey D1.1) × 8.33
- Reasonable onboarding: Based on systems/languages ratio × 8.34

#### Communication Efficiency (25 points)
- Low meeting overhead: (5 - Survey E2.1) × 6.25
- Fast response times: (5 - Survey E2.2) × 6.25
- Minimal duplication: (5 - Survey E2.3) × 6.25
- Clear communication: (5 - Survey E2.4) × 6.25

#### Value Delivery (25 points)
- Clear success metrics: Survey quality × 12.5
- Customer feedback loops: Survey A1.4 × 12.5

### Red Flags (Immediate Attention Required)
- **High Cognitive Load**: Survey D1.2 or D1.3 ≥ 4
- **Excessive Dependencies**: Survey B2.1 ≥ 4
- **Communication Overload**: Survey E2.1 ≥ 4
- **Unclear Purpose**: Vague responses to team mission questions
- **Conflicting Classifications**: Multiple team types score > 70

---

## 4. Analysis Workflow

### Step 1: Data Collection Validation
- [ ] Survey completion rate > 80%
- [ ] Interview coverage includes all major teams
- [ ] Dependency mappings completed
- [ ] Data quality check completed

### Step 2: Team Classification
```
For each team:
1. Calculate all four team type scores
2. Identify primary type (highest score)
3. Note secondary type if score > 60
4. Flag teams with unclear classification (top 2 scores within 20 points)
5. Validate classification against interview notes
```

### Step 3: Interaction Pattern Analysis
```
For each team pair relationship:
1. Identify current interaction mode
2. Assess interaction effectiveness
3. Calculate communication overhead
4. Identify optimization opportunities
```

### Step 4: Health Assessment
```
For each team:
1. Calculate team health score
2. Identify red flags
3. Prioritize improvement areas
4. Create improvement recommendations
```

---

## 5. Output Templates

### Team Classification Report Template
```markdown
## Team: [Team Name]

### Classification
- **Primary Type**: [Stream-Aligned/Platform/Enabling/Complicated Subsystem] (Score: XX/100)
- **Secondary Type**: [Type] (Score: XX/100) [if applicable]
- **Confidence Level**: [High/Medium/Low]

### Key Characteristics
- [3-5 bullet points supporting classification]

### Health Score: XX/100
- Autonomy: XX/25
- Cognitive Load: XX/25
- Communication: XX/25
- Value Delivery: XX/25

### Red Flags
- [List any red flags identified]

### Recommendations
1. [Priority 1 recommendation]
2. [Priority 2 recommendation]
3. [Priority 3 recommendation]
```

### Interaction Analysis Template
```markdown
## Team Interaction: [Team A] ↔ [Team B]

### Current State
- **Interaction Mode**: [Collaboration/X-as-a-Service/Facilitating]
- **Frequency**: [Daily/Weekly/Monthly]
- **Effectiveness**: [High/Medium/Low]
- **Communication Methods**: [List]

### Pain Points
- [List key challenges]

### Recommended Future State
- **Optimal Interaction Mode**: [Mode]
- **Required Changes**: [List changes needed]
- **Expected Benefits**: [List benefits]
```

---

## 6. Aggregated Analysis

### Organization-Level Metrics
- **Team Type Distribution**:
  - Stream-Aligned: X teams (X%)
  - Platform: X teams (X%)
  - Enabling: X teams (X%)
  - Complicated Subsystem: X teams (X%)

- **Average Health Scores**:
  - Overall: XX/100
  - By team type breakdown

- **Common Issues**:
  - Most frequent red flags
  - Common interaction inefficiencies
  - Widespread autonomy gaps

### Improvement Priorities
1. **High Impact, Low Effort**: [List opportunities]
2. **High Impact, High Effort**: [List strategic initiatives]
3. **Quick Wins**: [List immediate improvements]

---

## 7. Validation & Calibration

### Quality Assurance Checklist
- [ ] All calculations verified
- [ ] Classifications validated against interview notes
- [ ] Red flags cross-checked with multiple data sources
- [ ] Recommendations are actionable and specific
- [ ] Analysis reviewed by domain experts

### Calibration Process
1. **Pilot Analysis**: Test framework with 3-5 teams
2. **Expert Review**: Have team leads validate classifications
3. **Adjustment**: Refine scoring weights based on feedback
4. **Full Rollout**: Apply to all teams
5. **Continuous Improvement**: Update framework based on results

---

**Framework Version**: 1.0
**Last Updated**: [Date]
**Next Review**: [Date]