# Class 3: User Stories, Functional Requirements, and Acceptance Criteria

- [Class 3: User Stories, Functional Requirements, and Acceptance Criteria](#class-3-user-stories-functional-requirements-and-acceptance-criteria)
  - [Introduction](#introduction)
  - [Role of user stories](#role-of-user-stories)
  - [Understanding functional and non-functional requirements](#understanding-functional-and-non-functional-requirements)
    - [Distinguishing Between Functional and Non-functional Requirements](#distinguishing-between-functional-and-non-functional-requirements)
  - [Incorporating user stories into functional requirements](#incorporating-user-stories-into-functional-requirements)
  - [Acceptance Criteria and Testing Considerations](#acceptance-criteria-and-testing-considerations)
  - [Documenting non-functional requirements with user stories](#documenting-non-functional-requirements-with-user-stories)
  - [Collaborating with stakeholders to identify and prioritize requirements](#collaborating-with-stakeholders-to-identify-and-prioritize-requirements)
  - [Case study: Prioritizing requirements and user stories for a given project](#case-study-prioritizing-requirements-and-user-stories-for-a-given-project)
    - [User Stories](#user-stories)
    - [Prioritization](#prioritization)
  - [Links](#links)


## Introduction

Recap of the user stories

## Role of user stories

- **Definition and purpose of user stories**
  - **User stories** Are concise, user-centric descriptions of features told from the user's perspective.
  - **They serve** as a means of capturing requirements in a way that fosters collaboration between development teams and stakeholders."
- **Key elements of well-defined and effective user stories**
  - **User Role**: Clearly defining the end-user or stakeholder involved.
  - **Action**: Describing the action or functionality the user wants.
  - **Benefit**: Outlining the value or benefit the user gains from the feature.
  - **Acceptance Criteria**: Specifying conditions for the story to be considered complete.
  - **Priority**: Indicating the relative importance or urgency.
  - **Estimation**: Providing effort estimation for implementation."
- **Examples of user stories**
  - `As an online shopper, I want to easily search for products so that I can find what I need quickly`
  - `As a project manager, I want to view a project's progress on a dashboard, including key metrics and timelines`

## Understanding functional and non-functional requirements

> it's essential to distinguish between two fundamental types: functional and non-functional requirements

- **Functional vs Non-functional requirements**
  - **Functional requirements** define what the system should do, focusing on specific functionalities and features. These are the '**what**' of a system.
  - **Non-functional requirements** define how the system should perform, encompassing qualities like performance, security, and usability. These are the '**how**' of a system."
- **Examples**
  - Functional Requirement Example:
    - `Users should be able to add products to their shopping cart`
  - Non-functional Requirement Example:
    - `The system must respond to user interactions within two seconds`
- **Contribution to Project Success**
  - Functional Requirements
    - Ensure that the system meets user needs and expectations
    - Serve as the basis for design, development, and testing phases
  - Non-functional Requirements
    - Guarantee the system's performance, security, and usability
    - Define the criteria for acceptance testing and overall system quality

### Distinguishing Between Functional and Non-functional Requirements

1. **Universality across all conditions**: one method to differentiate between functional and non-functional requirements involves considering the universality across all conditions and users:
   - Functional Requirements:
     - **Characteristic**: Typically conditional in nature, varying based on specific conditions or user interactions.
     - **Identification**: If a requirement is conditional, it is likely functional in nature.
   - Non-functional Requirements:
     - **Characteristic**: Universality across all conditions and users, independent of specific scenarios.
     - **Identification**: If a requirement is universal, it is likely non-functional.
2. **Nature of the requirement**: another approach is to consider the nature of the requirement in relation to the system's behavior and characteristics:
   - Functional Requirements:
     - **Nature**: Describes specific functionalities and features that the system must provide.
     - **Examples**: Input validation, data processing, user authentication.
   - Non-functional Requirements:
     - **Nature**: Encompasses system qualities and attributes rather than specific behaviors.
     - **Examples**: `Performance, reliability, security, usability, Quality, Maintainability`.

## Incorporating user stories into functional requirements

> This process is crucial for translating user needs into actionable specifications that align with project goals

- **Mapping user stories to functional requirements**
Mapping user stories to functional requirements involves connecting the user's narrative to specific functionalities. This ensures that each user need is addressed through actionable specifications

- **Translating user needs into actionable functional specifications**
Translating user needs involves breaking down the high-level user stories into detailed, implementable functional requirements. This step clarifies what the development team needs to deliver to meet user expectations.

- **Ensuring alignment between user stories and project goals**
Functional requirements derived from user stories should contribute directly to achieving project objectives

- **Practical Example**
  - **User story**: `As an online shopper, I want to easily search for products so that I can find what I need quickly.`
  - **Translating into a functional requirement**: `The system shall provide a robust search functionality, allowing users to filter and find products efficiently`

## Acceptance Criteria and Testing Considerations

- **Acceptance criteria**: are the conditions that must be met for a user story to be considered complete.

- **Purpose**: They serve as the bridge between user expectations and the delivered product, providing a clear definition of success

- **Importance of acceptance criteria**
  - Validating that the implemented functionality meets user expectations.
  - Providing a clear understanding of what success looks like for each user story.

- **Test Cases**
  - *Test cases* are detailed sets of conditions, inputs, or variables that are systematically designed to determine whether a specific aspect of a software application or system functions as intended
  - *Purpose* These cases serve as a means to verify that the software meets its specified requirements and behaves correctly under various scenarios
  - *Importance* Test cases are crucial components of the testing process, providing a structured approach to evaluate the functionality, performance, and security of software

- **Considerations for effective test cases**
  - *Coverage*: Ensure test cases cover all aspects of the user story.
  - *Clarity*: Clearly define steps, expected outcomes, and criteria for success.
  - *Relevance*: Align test cases with acceptance criteria and user expectations.
  - *Automation*: Evaluate opportunities for automated testing to enhance efficiency."

- **Practical Example**
  - **User story** `As a registered user, I want to reset my password via email for enhanced security`
  - **Acceptance Criteria**:
    - User receives a password reset email within 5 minutes
    - The email contains a secure link for password reset
  - **Test Cases**:
    - Clicking the password reset link redirects the user to a secure page
    - Entering a new password and confirming the reset successfully updates the user's credentials

## Documenting non-functional requirements with user stories

> While functional requirements address what the system does, non-functional requirements focus on how it performs. It's essential to identify these aspects and ensure they align seamlessly with user expectations

- **Identifying non-functional aspects related to user stories**
  "As we analyze user stories, we must identify non-functional aspects that go beyond the visible functionalities. Let's explore three key areas:

  - **Performance**
    - Assessing how quickly the system responds to user interactions.
    - Ensuring efficient handling of simultaneous user requests.
  - **Security**
    - Identifying measures to safeguard user data and system integrity.
    - Implementing secure authentication and authorization processes.
  - **Usability**
    - Enhancing the user interface for intuitive navigation.
    - Ensuring accessibility for users with diverse needs."

- **Ensuring that non-functional requirements align with user expectations**
  Documenting non-functional requirements is not just about technicalities; it's about ensuring these aspects align with what users expect. Here's how we achieve that:
  - **User-Centric Approach**:
    - Aligning non-functional requirements with user expectations.
    - Balancing performance enhancements with user-friendly experiences.
  - **Clear Communication**:
    - Transparently communicating non-functional expectations to stakeholders.
    - Incorporating non-functional requirements into user stories for holistic understanding.
  - **Validation**:
    - Regularly validating non-functional aspects during the development process.
    - Incorporating feedback loops to refine non-functional requirements based on user needs.

## Collaborating with stakeholders to identify and prioritize requirements

- **Techniques for effective collaboration with stakeholders**
  - **Active Listening**: Demonstrating genuine interest in understanding stakeholder perspectives
  - **Workshops and Brainstorming Sessions**: Organizing collaborative workshops to gather insights from diverse stakeholders
  - **Prototyping and Visualization**: Creating prototypes or visual representations to help stakeholders envision proposed solutions

## Case study: Prioritizing requirements and user stories for a given project

- **Case Study Scenario**
 In TechTrade, an e-commerce platform. Our goal is to enhance the platform with new features. The challenge lies in determining which features should take precedence.
- **Analyzing User Stories**
  Break down the user stories and understand their potential impact on the project and business objectives
- **Prioritizing Based on Business Objectives**
  - **Strategic Alignment**: How does each user story align with the overall business strategy
  - **Customer Value**: What value does each feature bring to the end-users and the business
  - **Feasibility**: Assess the feasibility of implementing each user story within project constraints.

### User Stories

- **User Story: Enhanced Search Functionality**
  - **User Perspective**: "I want to easily find products on the platform using specific criteria or keywords to save time and find exactly what I'm looking for."
  - **Requirement**: Implement an advanced search feature to improve product discoverability.
  - **Business Objectives:**
    - **Strategic Alignment**: Aligns with the goal of enhancing user experience and increasing customer satisfaction.
    - **Customer Value**: Enhances the platform's usability, providing value to customers.
    - **Feasibility**: Requires moderate development effort; feasible within project constraints.

- **User Story: Integrated Third-Party Payment Gateway**
  - **User Perspective**: "I want a secure and hassle-free payment process, and I trust using my preferred payment methods for online transactions."
  - **Requirement**: Integrate a reliable third-party payment gateway for seamless and secure transactions.
  - **Business Objectives:**
    - **Strategic Alignment**: Enhances the platform's security and user trust, contributing to overall strategic goals.
    - **Customer Value**: Provides a secure and convenient payment option, improving the user experience.
    - **Feasibility**: Requires careful integration but is feasible within project constraints.

- **User Story: Personalized Product Recommendations**
  - **User Perspective**: "I want to discover new products that match my interests and preferences without spending too much time searching for them."
  - **Requirement**: Implement an algorithm for personalized product recommendations based on user preferences.
  - **Business Objectives:**
    - **Strategic Alignment**: Enhances user engagement and promotes product discovery, aligning with strategic goals.
    - **Customer Value**: Provides a personalized shopping experience, adding value for customers.
    - **Feasibility**: Requires algorithm development and data integration; feasible within project constraints.

- **User Story: Mobile App Integration**
  - **User Perspective**: "I want the convenience of shopping on the go, and having a mobile app would make it easier for me to explore and purchase products."
  - **Requirement**: Develop a mobile app for TechTrade to expand the platform's reach.
  - **Business Objectives:**
    - **Strategic Alignment**: Expands the platform's reach and accessibility, aligning with strategic goals.
    - **Customer Value**: Offers convenience and flexibility, enhancing the user experience.
    - **Feasibility**: Requires mobile app development effort; feasible within project constraints.

- **User Story: Customer Loyalty Program**
  - **User Perspective**: "I want to be rewarded for my loyalty as a customer, and having access to exclusive offers would make me more likely to continue shopping here."
  - **Requirement**: Implement a customer loyalty program with rewards and exclusive offers.
  - **Business Objectives:**
    - **Strategic Alignment**: Encourages customer retention and loyalty, supporting strategic goals.
    - **Customer Value**: Rewards loyal customers and enhances overall satisfaction.
    - **Feasibility**: Requires program design and integration; feasible within project constraints.

- **User Story: Real-time Order Tracking**
  - **User Perspective**: "I want to know exactly where my order is and when I can expect it to arrive. Real-time tracking would provide me with peace of mind."
  - **Requirement**: Enable real-time order tracking to keep customers informed about their purchase status.
  - **Business Objectives:**
    - **Strategic Alignment**: Improves transparency and customer satisfaction, aligning with strategic goals.
    - **Customer Value**: Enhances the post-purchase experience, providing peace of mind for customers.
    - **Feasibility**: Requires integration with logistics systems; feasible within project constraints.

### Prioritization

| User Story                                | Strategic Alignment | Customer Value | Feasibility   |
|-------------------------------------------|---------------------|-----------------|---------------|
| Integrated Third-Party Payment Gateway     | High                | High            | Medium        |
| Mobile App Integration                    | High                | High            | Medium        |
| Real-time Order Tracking                   | Medium              | High            | High          |
| Enhanced Search Functionality             | Medium              | High            | High          |
| Personalized Product Recommendations      | Medium              | Medium          | Medium        |
| Customer Loyalty Program                  | High                | Medium          | Low           |

1. **Integrated Third-Party Payment Gateway**
   - **Reason**: Prioritizing this user story ensures a secure and seamless payment process, a crucial aspect of any e-commerce platform. It directly impacts user trust and can contribute to increased transactions and customer satisfaction.

2. **Mobile App Integration**
   - **Reason**: Developing a mobile app expands the platform's accessibility and aligns with modern user preferences for convenient shopping experiences. This can potentially attract a broader audience and improve user engagement.

3. **Real-time Order Tracking**
   - **Reason**: Providing real-time order tracking enhances the post-purchase experience, addressing a common customer concern. It contributes to transparency, customer satisfaction, and can lead to positive reviews and repeat business.

4. **Enhanced Search Functionality**
   - **Reason**: Improving the search functionality contributes to overall user experience by helping users find products quickly. It aligns with customer expectations for efficient navigation on the platform.

5. **Personalized Product Recommendations**
   - **Reason**: While personalized recommendations are valuable, they might depend on a robust user base and data collection. Hence, it could be strategically placed after foundational features like payment, app integration, and order tracking.

6. **Customer Loyalty Program**
   - **Reason**: While a loyalty program is important for customer retention, it might be more effective once the platform has gained a substantial user base. Implementing it later ensures that rewards have a more significant impact on customer loyalty.

**Considerations for Prioritization:**

- **Strategic Alignment**: Prioritize features that align with the overall strategic goals of the platform
- **Customer Value**: Features that directly enhance the user experience and provide clear value to customers may be prioritized.
- **Feasibility**: Consider the technical complexity and feasibility of implementing each feature within the project constraints.

## Links

- [geeksforgeeks: Functional vs Non Functional Requirements](https://www.geeksforgeeks.org/functional-vs-non-functional-requirements/)
- [Why is the difference between functional and Non-functional requirements important?](https://reqtest.com/en/knowledgebase/functional-vs-non-functional-requirements/)
- [Business, User, and System Requirements](https://enfocussolutions.com/business-user-and-system-requirements/)
