---
name: 'Host Issue Template '
about: 'Provide a template for the team to use for creating issues '
title: "[FEATURE] - [ADD Title ] - [Brief Description]"
labels: STR
assignees: ''

---

# Issue Template

## User Story
**As an** individual host,  
**I want** [specific feature or action],  
**So that** [desired outcome].

<details>
<summary>Use Parameters</summary>

## Parameters Definition
Replace the placeholders (e.g., `[Form Name]`, `[Specific Page]`, `[X] seconds`) with specific details relevant to your issue.

- `[Form Name]` - Name of the form or section this issue is about.
- `[Authentication Method]` - Method through which users are authenticated.
- `[Specific Page]` - Specific page or section of the application being referenced.
- `[X] seconds` - Specific time frame for actions or page loading.
- `[Data or Condition]` - Specific data or condition relevant to the scenario.
- `[Action/Event]` - Specific action or event that triggers the scenario.
- `[Expected Result]` - Desired outcome of the scenario.

</details>

## Scenario 1: Authenticated and Logged in to STR
**Given** the User has been authenticated via `[Authentication Method]`  
**When** [Action/Event]  
**Then** [Expected Result]

<details>
<summary>Global Scenarios</summary>

### Saving, Cancelling, and Reverting

#### Scenario 1: Cancellation and Reverting Changes
**Given** that I have made changes to `[Form Name]` but decide not to save these changes,  
**When** I click a "cancel" button or navigate away from `[Form Name]`,  
**Then** any unsaved changes should be discarded, and `[Form Name]` should revert to its previous state.

#### Scenario 2: Validation and Error Handling
**Given** that I am updating `[Form Name]` from the newly opened section below the progress bar,  
**When** I enter invalid data (such as `[Data or Condition]`) and attempt to save,  
**Then** I should receive immediate feedback indicating the error, and the information should not be saved until corrected.

#### Scenario 3: Confirmation of Successful Update
**Given** that I have entered new or updated information in the form,  
**When** I click the save button and the data is valid,  
**Then** I should receive a confirmation message indicating my `[Form Name]` has been successfully updated.

### Internet Connection

#### Scenario 1: Standard Internet Connection
**Given** that I am a User accessing the website from a standard internet connection,  
**When** I navigate to any page on the site,  
**Then** the page should load completely within `[X] seconds`, ensuring a fast and efficient User experience.

#### Scenario 2: Optimizing Dashboard for Hosts with Low Internet Connectivity
**Given** a User accesses the `[Form Name]` with a low-speed internet connection,  
**When** the User attempts to load and interact with the dashboard page,  
**Then** the `[Form Name]` should prioritize critical content and functionality, loading essential elements first to ensure usability.

### Security and Privacy

#### Scenario 1: Security and Privacy Settings
**Given** that I am editing `[Form Name]`,  
**When** I access the form,  
**Then** I should also have the option to update my privacy settings related to who can view `[Form Name]`.

### Mobile Responsiveness

#### Scenario 1: Mobile Responsiveness
**Given** that I am accessing the `[Form Name]` on a mobile device,  
**When** I click on the "[Link Name]" link,  
**Then** the `[Form Name]` should display correctly and be easily editable on my device, ensuring a responsive design.

</details>

<details>
<summary>Accessibility Scenarios</summary>

#### Scenario: Navigating the Page Using Keyboard Only
**Given** I am a non-mouse User accessing `[Specific Page]`,  
**When** I press the Tab key on my keyboard,  
**Then** the focus should move to the next interactive element on the dashboard.

</details>

[!NOTE]
Story in Mural: [Insert relevant information or link to the story in Mural]
