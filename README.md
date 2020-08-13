# developer-docs

**Hi!**

This page attempts to aid navigation of web dev by exploring it through a nested structure. It is being built and integrated into an educational platform for full-stack development called Stackweaver ([contact on Discord](https://discord.gg/nSAveSC)).

The goal is to do this collaboratively with the community so it makes as few assumptions as possible. It will eventually be enhanced through features such as sandboxes, discussions, collaborative learning and mentoring.

I would greatly appreciate any suggestions or feedback on the topics or categories below.

Note: Some items below can be clicked for related resources (non-biased and official where possible).

---
## Web Development Outline
---

### General

- Development Environment
    - Local, staging, production

- Development Tools
    - Editors
        - [Vim](https://www.vim.org/)
        - [Emacs](https://www.gnu.org/software/emacs/)
        - [Sublime](https://www.sublimetext.com/)
        - [Atom](https://atom.io/)
    - IDEs
        - [Visual Studio](https://visualstudio.microsoft.com/)
        - [Eclipse](https://www.eclipse.org/)
        - [IntelliJ IDEA](https://www.jetbrains.com/idea/)

- Testing
    - Resources
        - [softwaretestingfundamentals.com](http://softwaretestingfundamentals.com)
    - Types
        - [Unit Testing](https://en.wikipedia.org/wiki/Unit_testing)
        - [Integration Testing](https://en.wikipedia.org/wiki/Integration_testing)
        - [Functional Testing](https://en.wikipedia.org/wiki/Functional_testing)
        - [Acceptance Testing](https://en.wikipedia.org/wiki/Acceptance_testing#Acceptance_testing_in_extreme_programming)
        - [Performance Testing](https://en.wikipedia.org/wiki/Software_performance_testing)
        - [Load Testing](https://en.wikipedia.org/wiki/Load_testing)
        
- Debugging
    - Skills
        - [Asking Good Questions](https://en.wikipedia.org/wiki/Wikipedia:Reference_desk/How_to_ask_a_software_question)
        - [Bug Reports](https://developer.mozilla.org/en-US/docs/Mozilla/QA/Bug_writing_guidelines)

- Security
    - Encryption

- Workflow
    - Productivity
    - Estimation

- [Version Control](https://en.wikipedia.org/wiki/Version_control)
    - [Git](https://git-scm.com/)
    - [Subversion](https://subversion.apache.org/)
    - [Mecurial](https://www.mercurial-scm.org/)
    - [Perforce](https://www.perforce.com/)

- Package management
    - [Semantic Versioning](https://semver.org/)

- Virtualisation
    - [VPS](https://en.wikipedia.org/wiki/Virtual_private_server)
    - VirtualBox / Vagrant / VMWare
    - Containers (see infrastructure section below)

- Programming
    - Principles
    - [Design Patterns](https://github.com/kamranahmedse/design-patterns-for-humans)
    - Profiling
    - Refactoring
    - Benchmarking
    - Paradigms
        - Object-Oriented Programming (OOP)
        - Functional Programming (FP)
        - Procedural Programming
    - Languages
        - Java
        - JavaScript
        - Python
        - C#
        - Ruby
        - Go

- Design & Architecture
    - [Domain-Driven Design (DDD)](https://en.wikipedia.org/wiki/Domain-driven_design)
    - [12 Factor App](https://12factor.net/)
    - [Client/Server Model](https://en.wikipedia.org/wiki/Client%E2%80%93server_model)
    - [Serverless](https://en.wikipedia.org/wiki/Serverless_computing)

- Collaboration
    - Code Reviews

- [Localization/i18n](https://en.wikipedia.org/wiki/Internationalization_and_localization)
    - [gettext](https://www.gnu.org/software/gettext/)
    - Geolocation

- Data
    - Formats
        - JSON
        - XML
        - YAML
        
-Legal
    - Software Licensing
    - Copyright
        
### Frontend

- Development Tools
    - Browser Console ([Chrome](https://developers.google.com/web/tools/chrome-devtools/console), [Firefox](https://developer.mozilla.org/en-US/docs/Tools/Browser_Console))
    - Task runners
        - NPM scripts
        - Gulp
    - Module Bundlers
        - Webpack

- UX
    - Navigation
    - Information Architecture

- HTML
    - Syntax
    - Elements and attributes
    - DOM
    - Semantic HTML
    - Template engines
    - SEO
    - Accessibility

- CSS
    - Syntax
    - Attributes and values
    - Layout
        - Box model
        - Float
        - Positioning
        - Display
        - CSS Grid
        - Flexbox
    - Decoration
    - Animation
    - Preprocessors
        - SCSS
        - LESS
    - Frameworks
        - Bootstrap
        - Bulma
        - Materialize
        - Semantic UI
    - Architecture
        - BEM
        - OOCSS
        - SMACSS
    - CSS in JS
        - Styled Components
        - CSS Modules

- JavaScript
    - Syntax
    - Control Structures
    - DOM
        - Manipulation
        - Query
        - Shadow DOM
    - Object-oriented programming
    - Prototypal inheritance
    - Scope
    - Mode (strict)
    - XHR
    - Modules
    - Linters
    - Package managers
        - NPM
        - Yarn
    - Universal Applications (React Native)
    - Frameworks
        - React
        - Vue
        - Angular
    - Testing
        - Jest
        - Cyrpress
        - Enzyme
        - Selenium
    - Type Checkers
        - TypeScript
        - Flow

- Client
    - Compatibility
    - Progressive Web Apps
        - PRPL Pattern
        - RAIL Model
    - Browser
        - Web Assembly
        - Storage
        - Web Sockets
        - Service Workers
        - Location
        - Caching
        - Security
            - CSRF
    - Mobile Device
        - React Native
        - NativeScript
    - Desktop
        - Electron
            
### Mobile
- Operating Systems
    - Android
        
### Backend
- JavaScript
    - Server-side rendering
    - Node
    - APIs
    - Static site generators
    
- Frameworks
    - Python: Django
    - Ruby: Ruby on Rails
    - JavaScript: Express
    - C#: .NET
    - Java: Spring
    
- Web Servers
    - Apache
    - Nginx
    
- Security
    - Authentication
    - Authorisation
        - Framework
            - OAuth2

- Devops
    - Continuous Integration (and Continuous Delivery)
    
- Systems
    - Windows
        - Command Line
    - Linux
        - Terminal
        - Scripting
            - Bash
            
- Performance
    - Caching
    
- Databases
    - RDBMSs
        - PostgreSQL
        - MySQL
        - MSSQL
    - NoSQL
        - Redis
        - MongoDB
    - Indexing
    - [Data Warehousing](https://en.wikipedia.org/wiki/Data_warehouse)
    - Tools
        - PHPMyAdmin, DBeaver
        
- Architecture
    - Service-Oriented
    - Microservices
    - Monolith
    - Scalability
    
- Infrastructure
    - Automation
        - Ansible
        - Chef
        - Puppet
        - Terraform
    - Jobs/Workers
        - Job Scheduling
            - [Cron](https://en.wikipedia.org/wiki/Cron)
        - Job Queues
    - Monitoring
    - Containers
        - Orchestrators
            - Kubernetes
            - Nomad
            - Docker Swarm
    - Communication
        - Message Queues
        - Message Systems
            - RabbitMQ
            - Kafka
    - ETL (extract, transform, load)
    - Logging
    - Performance
        - Load Testing
    - Security
        - Virtual Private Networks
        - TLS
        - Penetration Testing
        - Authentication
            - Devices
                - YubiKey
    - Serverless
    - Cloud
        - Platforms
            - AWS
            - Google Cloud
            - Azure
            - Heroku
        - Dedicated Hosting
            - Hetzner
    - Resiliency
        - Chaos Engineering: [https://en.wikipedia.org/wiki/Chaos_engineering](https://en.wikipedia.org/wiki/Chaos_engineering)
    - Networking
        - Load Balancers
        - DNS
