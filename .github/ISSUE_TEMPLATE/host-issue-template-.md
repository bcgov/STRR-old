---
name: 'Host Issue Template '
about: 'Provide a template for the team to use for creating issues '
title: 'As an IH - '
labels: STR
assignees: ''

---

**As an individual host**
**I want**
**So that**

- [ ] Scenario 1: Authenticated and logged in to STR 
**Given** the host has been authenticated via SBC Connect 
**When** 
**Then**



<details>
<summary> Global Scenarios </summary>



**Saving, Cancelling and Reverting** 

**Scenario 1: Cancellation and Reverting Changes**
Given that I have made changes to @@@ form but decide not to save these changes,
When I click a "cancel" button or navigate away from @@@ form,
Then any unsaved changes should be discarded, and @@@ form should revert to its previous state.

**Scenario 2 : Validation and Error Handling**
Given that I am updating @@@ fom the newly opened section below the progress bar,
When I enter invalid data (such as ___________) and attempt to save,
Then I should receive immediate feedback indicating the error, and the information should not be saved until corrected.

**Scenario 3: Confirmation of Successful Update**
Given that I have entered new or updated @@@ in the form,
When I click the save button and the data is valid,
Then I should receive a confirmation message indicating my @@@ form  has been successfully updated.


**Internet Connection**

**Scenario 1:  Standard Internet Connection** 
Given that I am a host accessing the website from a standard internet connection,
When I navigate to any page on the site,
Then the page should load completely within 2 seconds, ensuring a fast and efficient host experience.

**Scenario 2: Optimizing Dashboard for Hosts with Low Internet Connectivity**
Given a host accesses the @@@ form with a low-speed internet connection.
When the host attempts to load and interact with the dashboard page.
Then the @@@ form should prioritize critical content and functionality, loading essential elements first to ensure usability.
And the page should implement efficient data usage strategies, such as compressing images, using caching for repeat visits, and minimizing the load of heavy scripts.
And the interface should provide feedback on loading progress for interactive elements, informing hosts of the current status and expected wait times.
And an option should be available for hosts to access a more simplified version of the dashboard that requires less bandwidth, ensuring that hosts can perform their necessary tasks even under constrained internet conditions.


 **Security and privacy**

**Scenario 1: Security and Privacy Settings**
Given that I am editing @@@ form, 
When I access the form,
Then I should also have the option to update my privacy settings related to who can view @@@ form.

**Scenario 2: Secure my information** 
Given that I am a host entering personal or login information @@@ form,
When I submit this information through any form or login page,
Then the platform should encrypt this data during transmission and storage, ensuring it is safeguarded against interception or unauthorized access.


**Mobile Responsiveness**

**Scenario 1: Mobile Responsiveness**
Given that I am accessing the @@@ form on a mobile device,
When I click on the "@@@" link,
Then the @@@ form should display correctly and be easily editable on my device, ensuring a responsive design. 
</details>

<details>
<summary> Accessibility Scenarios </summary>



Scenario: Navigating the page Using Keyboard Only
Given I am a non-mouse host accessing _______________________________
And the ______________ has loaded completely
When I press the Tab key on my keyboard
Then the focus should move to the next interactive element on the dashboard

When I press the Shift + Tab keys on my keyboard
Then the focus should move to the previous interactive element on the dashboard

When I press the Enter key while focusing on a button
Then the action associated with the button should be executed

And when I press the Arrow keys while focusing on a dropdown menu
Then the dropdown should expand and allow me to navigate the options

And when I select an option using the Enter key
Then the selected option should be applied

**Scenario: Using the "Skip to Main Content" link**
Given the "Skip to Main Content" link is the first focusable element
When the host presses the "Tab" key once
And the host presses the "Enter" key
Then the focus moves directly to the main content area

 **Scenario: Scenario: Interacting with form fields using the keyboard**
Given the host has navigated to a form with multiple input fields
When the host presses the "Tab" key to navigate through the input fields
And enters data using the keyboard
And presses the "Enter" key after filling out the form
Then the form data is submitted
And the host receives confirmation through keyboard-accessible feedback

 **Scenario: Scenario: Navigating dropdown menus using arrow keys**
Given the host has focused on a dropdown menu
When the host presses the "Down Arrow" key
Then the dropdown expands

And the host can navigate the options with the "Up Arrow" and "Down Arrow" keys
When the host presses the "Enter" key on an option
Then the option is selected
And the dropdown collapses

**Scenario: Closing modals using the Escape key**
Given a modal window is open and focused
When the host presses the "Escape" key
Then the modal closes
And focus returns to the element that opened the modal

**Scenario:  Scenario: Navigating paginated content using keyboard shortcuts**
 Given the host is viewing a page with paginated content
When the host presses a predefined keyboard shortcut for "next page"
Then the next page of content is displayed
And focus is set to the top of the new page content
When the host presses a predefined keyboard shortcut for "previous page"
Then the previous page of content is displayed
And focus is set to the top of the new page content


**Color Contrast**

Scenario: Ensuring ______ Usability with Color-Blind Friendly Design
Given I am a host with color vision deficiency
And I am viewing the ______

When I look at charts and graphs
Then they should use patterns or shapes, in addition to colors, to distinguish data points

And when I interact with status indicators
Then they should not rely solely on color to convey status (e.g., green for "good" or red for "alert")
And textual descriptions or icons should accompany color-coded elements to clarify their meaning

When I need to understand urgency or priority levels represented by colors
Then these levels should also be indicated by text labels or symbols next to the color-coded elements

And when I adjust the ______ settings
Then I should have an option to select a color-blind friendly palette
And the selected palette should override default colors to enhance visibility and contrast

Given the ______ includes interactive elements like buttons or links
When these elements are focused or hovered over
Then they should have clear focus indicators that do not rely solely on color changes


**Color Blind**

Scenario: Ensuring Usability with Color-Blind Friendly Design
Given I am a host with color vision deficiency
And I am viewing the _______
When I look at charts and graphs
Then they should use patterns or shapes, in addition to colors, to distinguish data points

And when I interact with status indicators
Then they should not rely solely on color to convey status
And textual descriptions or icons should accompany color-coded elements to clarify their meaning

When I need to understand urgency or priority levels represented by colors
Then these levels should also be indicated by text labels or symbols next to the color-coded elements

And when I adjust the_______settings
Then I should have an option to select a color-blind friendly palette
And the selected palette should override default colors to enhance visibility and contrast

Given the _______includes interactive elements like buttons or links
When these elements are focused or hovered over
Then they should have clear focus indicators that do not rely solely on color changes


https://www2.gov.bc.ca/gov/content/home/accessible-government/toolkit/accessible-digital-content/colour-contrast

</details>

> [!NOTE]
Story in Mural:
