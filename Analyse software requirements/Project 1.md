# Project 1

- [Requirement Definitions](./Class%201%20Introduction%20to%20Software%20Requirements%20Analysis%20and%20Agile%20Principles.md#1-overview-of-software-requirements-analysis)
- [Understanding functional and non-functional requirements](./Class%203%20User%20Stories,%20Functional%20Requirements,%20and%20Acceptance%20Criteria.md#distinguishing-between-functional-and-non-functional-requirements)
- [Confirm user needs](./Confirm%20user%20needs.md)
- [Project scoping practice](./Project%20scoping%20practice.md)
- [Requirement Activities](./Class%205%20Requirement%20Activities.md)

## Executive summary

- **The Executive Summary is typically written at the end of the report preparation process**
- The Executive Summary should be concise and to the point.
- Decision-makers typically have limited time, and the executive summary serves as a quick reference to understand the key aspects of the project.
- Aim for a length of around one to two pages, focusing on presenting essential information in a clear and compelling manner.
- Use concise language, bullet points, and clear headings to make it easily scannable while ensuring that it captures the project's significance and recommendations effectively.

> In practice, the Executive Summary is typically a high-level overview designed to provide decision-makers with a quick understanding of the project. It generally does not include detailed technical specifications.

**Parts that can be included in the Executive Summary:**

- **Project Overview**: Briefly introduce the project, its purpose, and its significance.
- C**lient Background**: Provide a quick overview of the client, emphasizing their industry and business areas.
- **Current Challenges**: Outline the existing issues that necessitate the project.
- **Proposed Solution**: Highlight the core functionalities of the proposed solution.
- **Functional Requirements**: Mention a couple of key functional requirements as user stories.
- **Non-Functional Requirements**: Summarize essential non-functional requirements using the FURPS+ model.
- **Gap Analysis**: Briefly mention how the gap analysis identified opportunities for improvement.
- **Feasibility Assessment**: Provide a concise overview of the project's feasibility.
- **Proposed Solutions**: Outline the feasible solutions and briefly discuss their merits.
- **Assumptions and Risks**: Highlight key assumptions and potential risks.
- **Recommendation**: Present the recommended solution and briefly justify the selection.
- **Conclusion**: Summarize the readiness and importance of the proposed solution.

**Parts that can be omitted from the Executive Summary:**

- **Technical Specifications**: Detailed technical specifications are usually better placed in the main body of the document or in an appendix. However, you may include high-level technical considerations if they significantly impact the decision-making process.
- **Detailed Use Case Diagrams or Digital Models**: These can be provided in the main body or as separate attachments.

## Offline Capability and Synchronization

> The mobile application should be designed and developed to operate seamlessly even when the device is not consistently connected to the internet

1. **Offline Functionality:**
   - The mobile app should provide features that are accessible and fully functional even in the absence of an internet connection.

2. **Data Synchronization:**
   - The app must support seamless synchronization of data with the server when an internet connection is re-established, ensuring consistency between local and server data.

3. **Local Storage:**
   - To enable offline access, the app should have the capability to store relevant data locally on the device, allowing users to perform tasks without continuous internet connectivity.

4. **User Experience:**
   - The user experience should remain smooth and intuitive during transitions between online and offline states, providing clear feedback to users about the status of their connection.

These key implications ensure that the mobile app is designed to handle varying levels of internet connectivity, offering a reliable and efficient experience for users in different scenarios.

## Data encryption

> Considering the sensitivity of HR-related information and the emphasis on security, it would be advisable to include data encryption measures.

## FURPS+ model

The FURPS+ model is a framework used for specifying and **evaluating non-functional requirements** in software development.

The acronym FURPS+ stands for:

- **Functionality**: Describes the capabilities and features of the system.
  - **Capability** (Size & Generality of Feature Set)
  - **Reusability** (Compatibility, Interoperability, Portability)
  - **Security** (Safety & Exportability)
- **Usability**: Concerns the user interface, user experience, and overall usability aspects.
  - Human Factors
  - Aesthetics
  - Consistency
  - Documentation
  - Responsiveness
- **Reliability**: Focuses on how well the software performs its functions under normal and exceptional conditions.
  - Availability (Failure Frequency, robustness, durability, Resilience)
  - Failure Extent & Time-Length (Recoverability, Survivability)
  - Predictability (Stability)
  - Accuracy (Frequency, Severity of Error)
- **Performance**: Refers to the system's responsiveness, speed, and efficiency.
  - Speed
  - Efficiency
  - Resource Consumption (power, ram, cache, etc.)
  - Throughput
  - Capacity
  - Scalability
- **Supportability**: Encompasses maintainability, adaptability, and other factors that make the software easy to support.
  - Serviceability
  - Maintainability
  - Sustainability
  - Repair Speed
  - Testability
  - Flexibility (Modifiability, Configurability, Adaptability, Extensibility, Modularity)
  - Installability
  - Localizability
- **(+) Plus**: Includes additional qualities such as design constraints, implementation requirements, and external interfaces.
  - Implementation (resource limitations, languages and tools, hardware)
  - Interface (Protocols used, constraints imposed by interfacing with external systems)
  - Operations (Who manages the running system)
  - Packaging (physical box, Who installs the system, How many installations)
  - Legal (licensing)

## Gap Analysis in Software Requirements

1. **Current State Assessment**:
   - Evaluate the existing software, systems, or processes to understand their functionalities, features, and limitations.

2. **Desired Future State Definition**:
   - Clearly define the desired or expected state of the software system. Identify new features, improvements, or changes needed to meet business objectives.

3. **Identifying Gaps**:
   - Compare the current state with the desired future state to identify differences, deficiencies, or gaps. Analyze missing features, functionalities, or any discrepancies.

4. **Documenting Findings**:
   - Document the identified gaps, detailing what is currently lacking or not aligned with the desired state. This serves as a basis for decision-making and action.

5. **Prioritization**:
   - Prioritize the identified gaps based on their impact, urgency, and importance to the overall project or business objectives.

6. **Action Planning**:
   - Develop strategies or action plans to address and bridge the identified gaps. This may involve creating new requirements, modifying existing functionalities, or implementing new software components.

7. **Communication**:
   - Communicate the findings and recommendations to stakeholders, ensuring a shared understanding of the current state, desired state, and the steps required to close the gaps.

## Representing user stories

- User Stories as **Cards**: A physical or digital card that encapsulates a user story
  - *Focus on individual features or functionalities, enhancing collaboration and prioritization*
  - ```As a [user type], I want [an action] so that [benefit]```
- **Use Case Diagram**: A visual representation of the interactions between actors and the system to achieve a specific goal
  - *Provide a holistic view of system interactions, aiding communication and serving as a blueprint for development.*
  - Content:
    - **Actors**: Represent entities interacting with the system.
    - **Use Cases**: Depict individual functionalities or actions the system can perform.
    - **Associations**: Lines connecting actors and use cases, illustrating relationships.
    - **System Boundary**: Represents the scope of the system.

## Feasibility Analysis

When evaluating a project, you're basically asking:

>"Can we realistically pull this off?"

A feasibility study helps assess this by examining four key areas

### Feasibility Areas

#### Technical Feasibility

- Can we do it with current technology, or is there a need for significant research and development?
- Are the necessary skills and expertise available?
- Are there any technological limitations or dependencies?

#### Operational Feasibility

- Does the project align with the overall goals and strategy of the organization?
- How will it impact existing workflows and processes?
- What resources (people, equipment, etc.) are required, and how will they be integrated?

#### Budgetary Feasibility

- Can we afford it?
- What are the estimated costs (development, implementation, ongoing maintenance)?
- Is there a clear funding source or plan to secure funding?
- What is the projected return on investment (ROI)?

#### Scheduling Feasibility

- How long will it take to complete the project?
- Are there any critical deadlines or dependencies?
- Are the resources available to meet the desired timeline?
- What are the potential risks and mitigation plans for delays?

### Steps

1. **Identify the Project Goals**: Clearly define what the project aims to achieve.
2. **Analyze Each Area**: For each feasibility area (technical, operational, budgetary, scheduling):
   - Describe the relevant factors and considerations.
   - Assess the strengths and weaknesses of the project in that area.
   - Identify any potential risks or challenges.
3. **Summarize the Overall Feasibility**:
   - Based on the analysis, conclude whether the project seems feasible (possible and worthwhile) with the current resources and approach.
   - Highlight any areas that require further investigation or mitigation strategies.

### Example

**Project**: Develop a new mobile app to streamline customer service interactions.

#### Technical Feasibility Analysis

- Existing development tools and frameworks can be used.
- Some in-house developers possess the necessary skills, but additional training may be required.

#### Operational Feasibility Analysis

- Aligns with the company's goal of improving customer satisfaction.
- Requires integrating with existing customer data systems.

#### Budgetary Feasibility Analysis

- Initial development costs may be high, ongoing maintenance costs are moderate.
- Funding can be secured through a budget allocation.
- Potential cost savings from improved customer service efficiency need to be evaluated.

#### Scheduling Feasibility Analysis

- Development can likely be completed within 6 months.
- However, data system integration might cause delays.

#### Overall Feasibility

- The project appears technically feasible with some additional training.
- Operational fit is strong, but data system integration needs careful planning.
- Budgetary feasibility hinges on a clear cost-benefit analysis.
- The schedule is achievable, but risks associated with data integration need mitigation strategies.

### Important Notes

- A feasibility study is an ongoing process, not a one-time assessment.
- As the project progresses, new information may emerge, requiring adjustments to the feasibility analysis.

## Solution Comparison

After completing software requirement development, comparing potential solutions is a crucial part of the feasibility analysis

- **Software Requirements Development (SRD)**: Focuses on understanding the problem, identifying stakeholder needs, and defining the functionalities (what) the software needs.
- **Feasibility Analysis**: This stage assesses if the requirements defined in SRD are achievable within project constraints (technical, operational, budgetary, scheduling)
- **Comparing solutions**: help to choose the solution that best meets all feasibility criteria, identify potential technical or implementation challenges early on, anf provides valuable insights to stakeholders when deciding

### Proposed solutions

- [bamboohr](https://www.bamboohr.com/mobile)
- [employmenthero](https://employmenthero.com)
- [clickup](https://clickup.com/blog/bamboohr-alternatives/)
- [brighthr](https://www.brighthr.com/au/?utm_source=bing&utm_medium=cpc&utm_term=hr%20software&utm_campaign=HR-Terms-AUS&utm_source=bing&utm_medium=cpc&utm_campaign=HR%20Terms&utm_term=hr%20software&utm_content=HR%20Terms)
- [Alternatives to BambooHR](https://www.capterra.com.au/alternatives/110968/bamboohr)
- [10 BambooHR alternatives for 2023](https://joinhomebase.com/blog/bamboohr-alternatives/)
- [BambooHR Alternatives](https://www.getapp.com.au/alternatives/20517/bamboohr)
- [7 Best BambooHR Alternatives in 2024](https://connecteam.com/best-bamboohr-alternatives/)

### Comparison with Market Solutions:

1. **Staff Directory:**
   - Your Solution: Yes
   - Competitors: Varies (Check specific features and usability)

2. **Company Intranet:**
   - Your Solution: Yes
   - Competitors: Varies (Evaluate collaboration features, document sharing, and accessibility)

3. **HR Management:**
   - Your Solution: Yes
   - Competitors: Check specific HR functionalities (Recruitment, Leave Management, Performance Reviews)

4. **Payroll:**
   - Your Solution: Yes
   - Competitors: Verify payroll processing capabilities and integration with financial systems

5. **API Connections:**
   - Your Solution: Yes
   - Competitors: Check the extensibility and integration options with external systems

6. **Mobile Support (Android and iOS):**
   - Your Solution: Yes
   - Competitors: Evaluate the usability and responsiveness of their mobile applications

7. **Security:**
   - Your Solution: Implement strong authentication and authorization controls
   - Competitors: Verify security measures and compliance with industry standards

8. **Customization:**
   - Your Solution: Tailored to meet specific company needs
   - Competitors: Check the level of customization and flexibility in configurations

9. **User-Friendly Interface:**
   - Your Solution: Ensure a user-friendly design following ROI Style Guide
   - Competitors: Assess the intuitiveness of the user interface in competitors' solutions

10. **Cost (Pricing):**
    - Your Solution: POA (Potential higher costs)
    - Competitors: Check the pricing models, including subscription fees, additional costs, and overall value for money

11. **Scalability:**
    - Your Solution: Consider scalability for future staff growth
    - Competitors: Assess the scalability options and potential limitations

12. **Support and Training:**
    - Your Solution: Plan for adequate support and training resources
    - Competitors: Evaluate the support and training provided by market solutions

13. **Data Migration:**
    - Your Solution: Facilitate the migration of current records
    - Competitors: Check data migration capabilities and ease of transition

14. **Regulatory Compliance:**
    - Your Solution: Ensure compliance with HR regulations
    - Competitors: Verify compliance features and updates in competitors' solutions

15. **Future Expansion:**
    - Your Solution: Built with future expandability in mind
    - Competitors: Assess the extensibility and adaptability of market solutions

Remember to highlight the strengths and unique features of your in-house solution, especially if it aligns closely with the specific needs and preferences of Red Opal Innovations (ROI).

> POA" stands for "Price on Application." It means that the pricing details for your in-house developed solution are not publicly disclosed, and interested parties need to contact the vendor (in this case, Gelos Enterprises) directly to get a customized price quote based on their specific requirements and needs.

## Links

- [wikipedia FURPS](https://en.wikipedia.org/wiki/FURPS)
- [Identifying Non-Functional Requirements](https://www.cs.sjsu.edu/faculty/pearce/modules/lectures/ooa/requirements/IdentifyingURPS.htm)
- [FURPS Requirement Model](https://mymusing.co/furps-requirement-model/)
- [PlantUML at a Glance](https://plantuml.com/)