## 1. Conceptual Architecture 

### Purpose

The broadly stated goal of enterprise architecture is to create a common
and cohesive vision between business and technology thought leaders. A principal
design consideration of a technical infrastructure and architecture is
to facilitate easy and rapid change. This change, driven by business
requirements from the internal business process change and external
trends, will be implemented across the enterprise and even with external
partners, not just within individual projects. Accommodation of these
rapid business changes is enabled by a well-designed technical
infrastructure that is broader and more forward-looking than the
immediate application requirements.

The Conceptual Architecture contains values and practices that represent
the core business and technical ideas on which all the technical domain
architectures are derived. These values guide the implementation of
technology to meet business requirements. They are the rules that guide
investment and design to maximize business value and the
adaptability, flexibility, and agility of the IT environment.

### Scope

The Conceptual Architecture describes the top-level concepts of the
entire Enterprise Technical Architecture. Values and practices listed
here apply to all domains. Concepts that are focused on more specific
areas of the technical architecture are in the applicable domain
chapters.

### Business Drivers

A Technical Architecture must be based upon an accepted set of business
needs: the motivation factors and case for action. The following have
been defined for the purposes of this Enterprise Technical Architecture:

-   -   **Transparency:** **must provide the capability to locate and
    present information seamlessly based on the requestor's needs and
    context, without requiring the requestor to know in advance the
    source or location of the information.**

-   -   **Extensible and Open:**

-   -   **must** **be flexible, scalable, adaptable, enduring,
    extensible, and open.** **The architecture should be able to expand
    or contract its infrastructure in concert with shifts in demand for
    services, without sacrificing response time or efficiency.** **This
    model will reduce the total cost of ownership of IT investments
    though the elimination of duplicate infrastructures or support
    services and the leveraging of economies of scale by using** **and**
    **designing applications to fit this model.**

-   **Interoperable:** **must** **enable domains to combine** **or
    transact data** **across systems;** **users** **and customers**
    **need to access information and services from varied sources;**
    **business partners need to interface to conduct business.**

-   **Reusability:** **must support reuse through the storage of, and
    the access to, reusable objects; and through providing access
    mechanisms for other reusable resources.**

-   **Security: must protect the confidentiality and integrity of data
    being stored or transmitted. It must also support multiple levels of
    security, access control and audit capability yet facilitate ease of
    access to information within the constraints of privacy and
    security. Access to information and services will be authenticated
    to the degree required by organizational standards.**

-   **User Access and Preferences: must provide coherent and navigable
    portal access for users and customers. The Enterprise Architecture
    must provide mechanisms to access, collect, continuously update, and
    use customer information via portal services where desired.**

-   **Manageable and Serviceable: must consider recommending solutions
    by which all parties are able to rapidly develop or acquire
    resources with a high level of expertise to support new
    technologies.**

-   -   -   -   -   -   

### Values 

These provide an expression of values to be used in making technical
choices in all new development efforts.

1.  **Architecture as enterprise business assets:** Business Process,
    Information and applications technology are valued as enterprise
    assets, managed by specified custodians on behalf of the enterprise

Rationale

-   -   Information is an important company asset. Collecting data and
    assembling information is expensive. This information is used to
    enhance and accelerate decision-making. Information is used to build
    a competitive edge for the enterprise via creation of value chains
    in customer relationship, asset management and other key process
    areas of the company

    [Implication]{.underline}

-   There must be documentation and inventory of assets. There must be a
    consistent technical architecture or framework to share information
    and services. There must be sufficient security precautions and
    disaster recovery procedures. There must be a new way of thinking
    about ownership of information, i.e. data and information are a
    common asset rather than local property. There must be a structure
    to ensure a safe and timely delivery of information

2.  **Total cost of ownership design:** Systems will use a total cost of
    ownership model for technologies which balances the costs of
    development or purchase, support, disaster recovery, and retirement
    against the costs of flexibility, scalability, ease of use, risk of
    data loss, and reduction of integration complexity.

Rationale

-   This allows us to make better choices about better managed
    information and IT infrastructure assets on an enterprise level. An
    overall better solution will likely be deployed. The IT environment
    will be simplified.

Implication**:**

-   This require deliberate injection of the model up front in the early
    build or purchase stage, which will be offset by longer-term lower
    TCO.

3.  **Mainstream technology use:** Production IT solutions must use
    industry-proven, mainstream technologies except in those areas where
    advanced higher-risk solutions provide a substantial benefit.
    Mainstream is defined to exclude advanced technologies not yet in
    general use and older technologies and systems that have outlived
    their effectiveness.

Rationale

-   The Enterprise does not want to be on the leading edge for its core
    service systems. Risk will be minimized.

Implication**:**

-   There will be an element of risk avoidance in constructing core
    production systems. We are generally not going to be early adopters
    of new technology. There must be a continual evaluation of old
    technology deployed to hasten its retirement.

4.  **Interoperability and reusability:** Systems will be constructed
    with methods that substantially improve interoperability and the
    reusability of components.

Rationale

-   Enables the development of service oriented solution applications.

Implication**:**

-   Use multi-tier distributed component design. Provide the service of
    message brokers and middleware.

5.  **Open systems:** Design choices prioritized toward open systems
    will provide the Enterprise with the best ability to create
    adaptable, flexible and interoperable designs.

Rationale

-   An open, vendor-neutral policy provides the flexibility and
    consistency that allows business to respond more quickly to changing
    requirements.

-   This policy allows the Enterprise to choose from a variety of
    sources and select the most economical solution without impacting
    applications. It also supports implementation flexibility because
    technology components can be purchased from many vendors, insulating
    the Enterprise from unexpected changes in vendor strategies and
    capabilities.

Implication**:**

-   Open standards do not exist for all parts of the architecture.
    Therefore, a combination of de facto industry standards, product
    standards, and open standards will be required in order to support a
    heterogeneous operating environment. An Enterprise Application
    Integration (EAI) approach is defined in the middleware document in
    detail.

-   Open systems must be differentiated from proprietary systems
    throughout this architecture.

6.  **Reduction of integration complexity:** The architecture must
    reduce integration complexity to the greatest extent possible.

Rationale

-   Increases the ability of the enterprise to adapt and change.

-   Reduces product and support costs.

Implication**:**

-   May reduce flexibility as a trade off toward interoperability.

-   May sacrifice performance and functionality in some rare instances.

7.  **Scalability:** The underlying technology infrastructure and
    applications must be scalable in size, capacity, and functionality
    to meet changing business and technical requirements.

Rationale**:**

-   Reduces total cost of ownership by minimizing application and
    platform changes required to respond to increasing or decreasing
    system demand.

-   Encourages reuse.

-   Leverages the continuing decline in hardware costs.

Implication**:**

-   Scalability must be reviewed for both "upward" and "downward"
    capability.

-   May increase initial costs of development and deployment.

-   Will reduce some solution choices.

8.  **Integrated reliability, availability, and maintainability:** All
    systems, subsystems, and components must be designed with the
    inclusion of reliability and maintainability as an integral part.
    Systems must contain high-availability features commensurate with
    business availability needs. An assessment of business recovery
    requirements is mandatory when acquiring, developing, enhancing, or
    outsourcing systems. Based on that assessment, appropriate disaster
    recovery and business continuity planning, design and testing must
    take place.

Rationale

-   Users and customers depend upon the availability of Enterprise
    applications and services. To assure this, reliability and
    availability must be designed in from the beginning; they cannot be
    added afterward. The ability to manage and maintain all service
    resources must also be included in the design to assure availability

Implication

-   Additional up-front design effort, additional design expense,
    built-in redundancies and rapid recovery facilities, integration
    with a common management system.

1.  **Manageability:** Systems must be designed to be easy to manage and
    administer.

Rationale

-   Operations costs can be substantial if environments are designed
    which demand more care and feed than appropriate. There is a great
    need to ensure ease of management & administration so that the over
    all total cost of ownership is reduced over the life of the system.

Implication

-   Additional up-front design effort, additional design expense,
    built-in administrative menus and facilities, integration with a
    common management system.

2.  **Security:** Systems must be designed with a security process which
    is appropriate for the business process it supports**.**

Rationale

-   Operations costs can be substantial if differing environments are
    maintained which demand more care and feed than appropriate. There
    is a great need to ensure ease of management & administration so
    that the overall total cost of ownership is reduced over the life of
    the system.

Implication

-   Additional up-front design effort, additional design expense,
    built-in administrative menus and facilities, integration with a
    common management system

9.  **Talent optimization:** System development and operational
    environments will be oriented towards an Enterprise wide
    consistency.

Rationale

-   Programming and operations staff is the most difficult resource to
    acquire and the largest portion of any project or operations budget.
    Costs of training, education, and ramp-up time, if staff migrates
    among the projects or organization, can be substantial if differing
    environments are maintained. The need to make the best use of
    available talent and provide the greatest career opportunities for
    staff is critical to the success of rapid system deployment and
    technical talent retention.

Implication

-   The variety of development tools, programming languages, supporting
    systems (middleware, data and records management, platforms, etc.)
    must be minimized or standardized on the smallest number of
    alternatives.

### 

### Ground rules and Practices

These provide the preparatory tasks and ongoing practices to be observed
and followed by systems developers for overall best
results and adherence to this enterprise architecture:

1.  **Common vision:** Business and IT staff must have a common vision
    of both its business functions and the role of technology in those
    business functions. They jointly have the responsibility for
    defining requirements and ensuring that the solutions delivered by
    the project teams provide the projected benefits.

Justification

-   Executive leadership of a program is responsible for its mission.
    Information technology staff provides automation of processes to aid
    in accomplishing that mission. Business and IT purposes must be
    synchronized to best accomplish the mission.

10. **Business processes drive technical architecture:** The technical
    architecture of any individual system must be driven by the business
    processes of the business or organizational domain.

Justification

-   There must not be a deployment of technology for technology's sake.
    Effective deployments are focused on the mission and goals of the
    business.

11. **Reengineer first:** New solutions will only be implemented after
    business processes have been analyzed, simplified, or otherwise
    redesigned.

Justification

-   Avoids automation of flawed processes. Work processes will be more
    streamlined, efficient, and cost effective and automation of those
    processes will be easier to implement and maintain.

12. **Design for sharing:** Identify opportunities for cross-functional
    components or subsystems and implement them in such a way that there
    is an opportunity for reuse by any other domains.

Justification

-   Sharable components must be built as sharable from the beginning. It
    is difficult and expensive to do so after the fact.

13. **Design for growth:** Err on the side of infrastructure over
    capacity rather than under capacity. Fixed investments should be
    oriented toward purchasing the most capacity or capability available
    within organizational financial limitations. This can create the
    lowest total cost of ownership while creating the greatest
    flexibility for future growth.

Justification

-   Growth in demand of IT support systems has historically been greater
    than envisioned. Building extra capacity up front, though it
    involves larger initial cost, will save in the long run because of
    there is less need to devote technical and management talent to
    upgrade projects on a more frequent basis.

14. **Design for performance and reliability** **measurement:**
    Applications and technology components (processors, network, etc.)
    should be implemented in such a manner that performance measurement
    and quality assurance data may be captured to support management and
    analysis of the IT environment.

Justification

-   The most effective use of systems can only occur if it is known when
    they are approaching limits. Forecasts for upgrades for capacity or
    to cure reliability issues can only come from statistical
    measurements.

15. **Tiered and Partitioned design:** The logical design of components,
    subsystems, application systems and databases should be clearly
    partitioned. These partitions must have well-defined interfaces
    established.

Justification

-   A change in a database or business rules can affect many large
    programs, if they are not partitioned. Logical boundaries are needed
    to separate components from each other. Modular design is more
    adaptive to changes in internal logic, platforms, and structures. It
    is the interfaces that allow partitioned components to interact
    well.

16. **Use industry standards:** Priority should be given to products
    adhering to industry standards and open architecture.

Justification

-   Provides ability to leverage the knowledge and efforts of others.
    Risk is reduced. Proven solutions are implemented.

17. **Set realistic expectations:** Set the right expectations of
    results among project staff and users/customers regarding quality,
    cost, and delivery time of new systems, recognizing that tradeoffs
    in these three attributes are critical to realistically meeting the
    requirements.

Justification

-   A new solution with high availability and performance cannot be
    implemented if lowest cost is a driving criteria. Tradeoffs in
    reliability or performance against cost must be made on a
    case-by-case basis in the best interest of the business purpose**.**

### Domain Architectures

This table contains a listing of the individual Domain Architectures and
the chapter groupings where they may be found:

The Enterprise Architecture is typically divided into sets of related
technologies and components, referred to as \"domains.\" The purpose of
a Domain Architecture is to provide a combination of domain principles,
best practices, methods, products and configurations that represent
"reusable building blocks". Thus, the Domain Architecture provides the
technical components within the Enterprise Architecture that enable the
business strategies and functions. Note, ***the Conceptual Architecture
serves as the foundation for the Domain Architectures,*** and ensures
that they are aligned and compatible with one another. To date, the
Design Authority for Applications and Infrastructure has identified and
approved the following twelve domains (below) for inclusion in the
Enterprise Architecture. It was further agreed that XXX, XXX,XXX domains
would be given highest priority, in order to support the 'Foundation'
initiatives

  **Chapter**   **Domain**                          **Definition**
  ------------- ----------------------------------- ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
  Chapter 1     Conceptual Architecture             The Conceptual Architecture describes the top-level concepts of the entire Enterprise Technical Architecture. Values and practices listed here apply to all domains. Concepts that are focused on more specific areas of the technical architecture are in the applicable domain chapters.
  Chapter 2     Network                             The Network Architecture defines the communications infrastructure defines the various topologies, carrier services and protocols necessary to facilitate the interconnection of the organization's business. Included in this architecture is the definition of both internal networks and connections to external networks.
  Chapter 3     Platform and Storage                The Platform Architecture defines the client and server computing platforms, and the operating systems interfaces supported. Components of the platform domain range from enterprise class servers to workstations and hand held computing devices and the operating systems (not applications) that run on these devices.
  Chapter 4     Data and Records Management         The Data and Records Management describes the logical structure of databases and the methodology used to correlate data in multiple databases. The information architecture provides a framework for defining responsibility for data integrity and distribution.
  Chapter 5     Data Interchange                    Through data integration, new applications can access the existing business processes and information between applications on the same platform and applications on different (heterogeneous) platforms.
  Chapter 6     Application                         The Application Architecture defines how applications are designed and how they cooperate. Application architecture promotes common presentation standards to facilitate rapid training and implementation of new applications and functions. Good application architecture enables a high level of system integration, reuse of components and rapid deployment of applications in response to changing business requirements.
  Chapter 7     Middleware                          The Middleware Architecture defines the components that create integration among the ERP, legacy, client, server, and portal systems to improve the overall usability of the distributed architecture. Middleware provides interfaces between applications and network communications. Middleware architecture includes such things as message brokers, XML and directory structures used to facilitate interconnection of systems and applications.
  Chapter 8     Presentation and Accessibility      Presentation and Accessibility Domain identifies criteria and techniques for designing and implementing interfaces needed for adaptive deployment of internet/intranet web applications.
  Chapter 9     Collaboration and Workflow Tools    Collaboration technologies enable organizations to create, share, and leverage information and knowledge across the entire organization and their associated service programs.
  Chapter 10    Security                            The Security Architecture defines the technologies, security standards and policies necessary to both protect the information assets and to make the information available to the appropriate resources. The security architecture includes definitions of such things as Public Key Infrastructure (PKI) and digital signatures.
  Chapter 11    System Management and Reliability   The Systems Management Architecture defines how the hardware and software components of the infrastructure will be monitored and controlled. Systems management includes the automation and control of platforms and associated resources, networks and applications and the coordination and control of work flowing through the infrastructure systems. It focuses on issues of configuration management, event and state management, fault detection and isolation, performance measurement, and problem reporting.
  Chapter 12    Testing                             Definition

Conclusion
==========

The creation of the Conceptual Architecture Principles facilitates and
supports the establishment of a common technology vision across the
enterprise and builds consensus and understanding between the different
domain architecture teams. The Principles enable the organization to
integrate various components of the technology into the overall business
vision by providing auditable linkages back to the business change
drivers. They help to ensure that not only are business rules enforced,
but a principle-based model is used in the governance of deployment.

The Principles provide guidance, in lieu of defined standards, while the
architecture effort continues to evolve to a comprehensive set of
product and configuration standards. These principles should enable
faster deployment of new technologies by providing the common framework
that will reduce the need to reassess each individual domain. This
common framework, i.e. the Conceptual Architecture, will ensure that
systems are defined logically as well as independent of technology
constraints.

----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
These principles also establish a common direction and consistent use of technical terms and components. This common language and common inventory will enhance communications and streamline business understanding. As a result, IT's environment complexity will be reduced as redundant standards and components are eliminated. And lastly, this consistent set of principles will facilitate cost avoidance as it limits the purchase of technologies outside of the Principles.
----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

