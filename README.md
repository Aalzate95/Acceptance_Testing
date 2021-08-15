# Acceptance Testing
---
#### Ingeniería de Software
WorkShop solved by  ***Alexander Alzate***

## Resume
Acceptance Testing is a level of software testing where a system is tested for acceptability. It is formal testing with respect to user needs, requirements, and business processes conducted to determine whether a system satisfies the acceptance criteria and to enable the user, customers or other authorized entity to determine whether or not to accept the system, and if it is acceptable for delivery.

The framework to write the acceptance tests is Cucumber, what use “Gherkin” language. The 10 key words of Gherkin are:

**Feature**
• Scenario
• Given
• When
• Then
• And
• But
• Scenario Outline
• Examples
• Background

**The 10 key words.**
• **Given:** This puts the system in a known state. It’s a set of key pre-conditions for a scenario (e.g., user has logged in, user has money in their account etc)
• **When:** This is the key action, a user will take. It’s the action that leads to an outcome
• **Then:** This is the observable outcome. It’s what happens after the user makes that action
• **Scenario:** This is used to describe the scenario & give it a title. The reason we do this is because a feature or user story will likely have multiple scenarios.
• **And:** This is used when a scenario is more complicated. It can be used in association with Given, When, or Then.
• **But:** Can be used in association with Then. It’s used to say something shouldn’t happen as an outcome.