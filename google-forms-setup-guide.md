# Google Forms Setup Guide for Team Topology Assessment

## Overview
This guide will help you create a Google Form version of the Team Topology Assessment Survey using the provided CSV file.

## Quick Setup Method

### Step 1: Create New Google Form
1. Go to [forms.google.com](https://forms.google.com)
2. Click "Blank" to create a new form
3. Title: "Team Topology Assessment Survey"
4. Description: "This assessment will help identify your team's topology type and interaction patterns. Please complete all sections honestly based on your team's current reality."

### Step 2: Import Questions from CSV
Unfortunately, Google Forms doesn't have direct CSV import, but you can use the structured data below to quickly set up all questions.

## Manual Setup Instructions

### Form Settings
- **Title**: Team Topology Assessment Survey
- **Description**: This assessment will help identify your team's topology type and interaction patterns. Rate each statement on a scale of 1-5 (1 = Strongly Disagree, 5 = Strongly Agree).
- **Collect email addresses**: Yes (to track responses by team)
- **Response receipts**: Optional
- **Edit after submit**: No

### Section 1: Team Information
Create a new section titled "Team Information"

1. **Team Name** (Short answer, Required)
2. **Team Lead** (Short answer, Required)
3. **Team Size** (Number, Required)
4. **Primary Technology Stack** (Short answer, Required)

### Section 2: Team Purpose & Focus - Customer Orientation
Create a new section titled "Section A: Team Purpose & Focus - Customer Orientation"

1. **A1.1 - Direct customer contact** (Linear scale 1-5, Required)
   - Question: "Our team has direct contact with external customers/end-users"
   - Scale: 1 = Strongly Disagree, 5 = Strongly Agree

2. **A1.2 - Customer impact measurement** (Linear scale 1-5, Required)
   - Question: "We can directly measure the impact of our work on customer outcomes"

3. **A1.3 - Customer-tied success metrics** (Linear scale 1-5, Required)
   - Question: "Our success metrics are tied to customer satisfaction or business KPIs"

4. **A1.4 - Direct user feedback** (Linear scale 1-5, Required)
   - Question: "We regularly receive feedback directly from users of our products/services"

### Section 3: Team Purpose & Focus - Service Provision
Create a new section titled "Section A: Team Purpose & Focus - Service Provision"

1. **A2.1 - Internal customers** (Linear scale 1-5, Required)
   - Question: "Other internal teams are our primary customers"

2. **A2.2 - Reusable services** (Linear scale 1-5, Required)
   - Question: "We provide reusable services/tools that multiple teams consume"

3. **A2.3 - Enabling productivity** (Linear scale 1-5, Required)
   - Question: "We focus on enabling other teams to be more productive"

4. **A2.4 - Reducing duplication** (Linear scale 1-5, Required)
   - Question: "Our work reduces duplication of effort across the organization"

### Section 4: Team Purpose & Focus - Knowledge Transfer
Create a new section titled "Section A: Team Purpose & Focus - Knowledge Transfer"

1. **A3.1 - Coaching time** (Linear scale 1-5, Required)
   - Question: "We spend significant time coaching or mentoring other teams"

2. **A3.2 - Technology adoption** (Linear scale 1-5, Required)
   - Question: "We help teams adopt new technologies, practices, or standards"

3. **A3.3 - Documentation creation** (Linear scale 1-5, Required)
   - Question: "We create documentation, guidelines, or best practices for others"

4. **A3.4 - Temporary embedding** (Linear scale 1-5, Required)
   - Question: "We temporarily embed with other teams to transfer knowledge"

### Section 5: Team Purpose & Focus - Specialized Expertise
Create a new section titled "Section A: Team Purpose & Focus - Specialized Expertise"

1. **A4.1 - Specialized knowledge** (Linear scale 1-5, Required)
   - Question: "Our work requires highly specialized domain knowledge"

2. **A4.2 - Duplication inefficiency** (Linear scale 1-5, Required)
   - Question: "It would be inefficient for other teams to duplicate our capabilities"

3. **A4.3 - Complex algorithms** (Linear scale 1-5, Required)
   - Question: "Our systems involve complex algorithms or mathematical models"

4. **A4.4 - Training requirements** (Linear scale 1-5, Required)
   - Question: "New team members require extensive training to become productive"

### Section 6: Autonomy & Dependencies - Decision Making
Create a new section titled "Section B: Autonomy & Dependencies - Decision Making"

1. **B1.1 - Technology choice** (Linear scale 1-5, Required)
   - Question: "We can choose our own technology stack without external approval"

2. **B1.2 - Deployment control** (Linear scale 1-5, Required)
   - Question: "We control our own deployment process and schedule"

3. **B1.3 - Process control** (Linear scale 1-5, Required)
   - Question: "We can change our team processes without affecting other teams"

4. **B1.4 - Priority setting** (Linear scale 1-5, Required)
   - Question: "We set our own priorities and roadmap"

### Section 7: Autonomy & Dependencies - External Dependencies
Create a new section titled "Section B: Autonomy & Dependencies - External Dependencies"

1. **B2.1 - Waiting for teams** (Linear scale 1-5, Required)
   - Question: "We frequently wait for other teams to complete work before we can proceed"

2. **B2.2 - Release coordination** (Linear scale 1-5, Required)
   - Question: "Our releases require coordination with multiple other teams"

3. **B2.3 - Breaking changes** (Linear scale 1-5, Required)
   - Question: "Changes in other teams' systems often break our functionality"

4. **B2.4 - Approval requirements** (Linear scale 1-5, Required)
   - Question: "We need approval from other teams for most of our changes"

### Section 8: Interaction Patterns - Collaboration Frequency
Create a new section titled "Section C: Interaction Patterns - Collaboration Frequency"

1. **C1.1 - Daily interactions** (Number, Optional)
   - Question: "How many teams does your team interact with daily?"

2. **C1.2 - Weekly interactions** (Number, Optional)
   - Question: "How many teams does your team interact with weekly?"

3. **C1.3 - Monthly interactions** (Number, Optional)
   - Question: "How many teams does your team interact with monthly?"

4. **C1.4 - Quarterly interactions** (Number, Optional)
   - Question: "How many teams does your team interact with quarterly?"

### Section 9: Interaction Patterns - Communication Methods
Create a new section titled "Section C: Interaction Patterns - Communication Methods"

1. **C2 - Communication Methods** (Checkboxes, Optional)
   - Question: "Select all communication methods your team uses with other teams"
   - Options:
     - Shared Slack channels with other teams
     - Regular cross-team meetings
     - Shared documentation/wikis
     - Joint planning sessions
     - Shared code repositories
     - Cross-team embedded members

### Section 10: Interaction Patterns - Service Relationships
Create a new section titled "Section C: Interaction Patterns - Service Relationships"

1. **C3.1 - Well-defined APIs** (Linear scale 1-5, Required)
   - Question: "Other teams consume our services through well-defined APIs"

2. **C3.2 - Self-service onboarding** (Linear scale 1-5, Required)
   - Question: "We provide self-service onboarding for teams using our services"

3. **C3.3 - Minimal involvement** (Linear scale 1-5, Required)
   - Question: "Teams can use our services without direct involvement from us"

4. **C3.4 - Service contracts** (Linear scale 1-5, Required)
   - Question: "We have SLAs or service contracts with consuming teams"

### Section 11: Cognitive Load - Complexity Management
Create a new section titled "Section D: Cognitive Load - Complexity Management"

1. **D1.1 - Context switching** (Linear scale 1-5, Required)
   - Question: "Team members frequently context-switch between different domains"

2. **D1.2 - System overload** (Linear scale 1-5, Required)
   - Question: "We maintain more systems than we can comfortably handle"

3. **D1.3 - Overwhelmed feeling** (Linear scale 1-5, Required)
   - Question: "Team members often feel overwhelmed by the breadth of responsibilities"

4. **D1.4 - External expertise** (Linear scale 1-5, Required)
   - Question: "We frequently need expertise from outside our team"

### Section 12: Cognitive Load - System Ownership
Create a new section titled "Section D: Cognitive Load - System Ownership"

1. **D2.1 - Applications owned** (Number, Optional)
   - Question: "Number of applications/services owned"

2. **D2.2 - Programming languages** (Number, Optional)
   - Question: "Number of programming languages used"

3. **D2.3 - Technology platforms** (Number, Optional)
   - Question: "Number of different technology platforms"

4. **D2.4 - External integrations** (Number, Optional)
   - Question: "Number of external integrations maintained"

### Section 13: Interaction Preferences - Preferred Interaction Mode
Create a new section titled "Section E: Interaction Preferences - Preferred Interaction Mode"

1. **E1.1 - Collaboration preference** (Linear scale 1-5, Required)
   - Question: "Rate your preference for Collaboration Mode - Joint working on shared goals"
   - Scale: 1 = Not Preferred, 5 = Highly Preferred

2. **E1.2 - XaaS preference** (Linear scale 1-5, Required)
   - Question: "Rate your preference for X-as-a-Service Mode - Providing/consuming services with minimal interaction"

3. **E1.3 - Facilitating preference** (Linear scale 1-5, Required)
   - Question: "Rate your preference for Facilitating Mode - Helping other teams improve their capabilities"

### Section 14: Interaction Preferences - Communication Overhead
Create a new section titled "Section E: Interaction Preferences - Communication Overhead"

1. **E2.1 - Meeting overhead** (Linear scale 1-5, Required)
   - Question: "We spend too much time in meetings with other teams"
   - Scale: 1 = Strongly Disagree, 5 = Strongly Agree

2. **E2.2 - Communication delays** (Linear scale 1-5, Required)
   - Question: "Communication delays with other teams slow down our delivery"

3. **E2.3 - Work duplication** (Linear scale 1-5, Required)
   - Question: "We often duplicate work being done by other teams"

4. **E2.4 - Misunderstandings** (Linear scale 1-5, Required)
   - Question: "Misunderstandings with other teams cause rework"

### Section 15: Open-Ended Questions
Create a new section titled "Open-Ended Questions"

1. **Team Purpose** (Paragraph, Required)
   - Question: "In one sentence, describe your team's primary purpose"

2. **Key Relationships** (Paragraph, Required)
   - Question: "List the 3 teams you interact with most frequently and describe the nature of each relationship"

3. **Biggest Challenges** (Paragraph, Required)
   - Question: "What are your team's biggest challenges related to working with other teams?"

4. **Ideal State** (Paragraph, Required)
   - Question: "If you could redesign how your team interacts with others, what would you change?"

5. **Success Metrics** (Paragraph, Required)
   - Question: "What metrics does your team use to measure success?"

## Form Configuration Tips

### Response Settings
- **Collect email addresses**: Yes
- **Limit to 1 response**: Yes
- **Allow response editing**: No
- **See summary charts and text responses**: Yes

### Sharing Settings
- **Send via email**: Recommended for tracking
- **Get shareable link**: For broader distribution
- **Embed in website**: If needed for internal portal

## Data Export & Analysis

### Exporting Responses
1. Go to "Responses" tab in your form
2. Click the green spreadsheet icon to "Create Spreadsheet"
3. Choose "Create a new spreadsheet"
4. This will create a Google Sheets file with all responses

### Preparing for Analysis
The response data can be imported into the scoring framework using the column headers that correspond to the question IDs (A1.1, A1.2, etc.).

## Estimated Setup Time
- **Manual setup**: 45-60 minutes
- **Testing**: 10-15 minutes
- **Total**: ~1 hour

## Pro Tips
- Use the "Preview" button frequently to test the form flow
- Consider adding page breaks between major sections for better user experience
- Test the form with a colleague before distributing
- Set up response notifications to track completion rates