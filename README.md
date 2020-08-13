# Full-Stack Web Development Outline

This page attempts to create a nested structure of all aspects of web development. It will be progressively improved based on community feedback. The links are safe to click and lead to official resources where possible.

**Why?**

It is being built and integrated into an educational platform for full-stack development called Stackweaver. This outline is central to how the platform itself will be structured; it will inform a full-stack curriculum and web docs (similar to MDN).

It will eventually be enhanced through features such as sandboxes, discussions, collaborative learning and mentoring. 

If you want to get involved feel free to contact: [Discord Server](https://discord.gg/nSAveSC), [Subreddit](https://www.reddit.com/r/Stackweaver), [Twitter](https://twitter.com/stackweaver), [Facebook](https://www.facebook.com/stackweaver).

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
        
- Legal
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
        - [Bootstrap](https://getbootstrap.com/)
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
        - [React](https://reactjs.org/)
        - [Vue](https://vuejs.org/)
        - [Angular](https://angularjs.org/)
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
    - Python: [Django](https://www.djangoproject.com/)
    - Ruby: [Ruby on Rails](https://rubyonrails.org/)
    - JavaScript: [Express](https://expressjs.com/)
    - C#: [ASP.NET](https://dotnet.microsoft.com/apps/aspnet)
    - Java: [Spring](https://spring.io/)
    - PHP: [Laravel](https://laravel.com/)
    
- Web Servers
    - [Apache](https://httpd.apache.org/)
    - [Nginx](https://www.nginx.com/)
    
- Security
    - Authentication
    - Authorisation
        - Framework
            - [OAuth2](https://oauth.net/2/)

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
    - Relational Database (RDBMS)
        - [SQLite](https://www.sqlite.org/index.html)
        - [PostgreSQL](https://www.postgresql.org/)
        - [MySQL](https://www.mysql.com/)
        - [MSSQL](https://www.microsoft.com/en-us/sql-server)
        - [Oracle](https://en.wikipedia.org/wiki/Oracle_Database)
    - NoSQL/Schemaless
        - [Redis](https://redis.io/)
        - [MongoDB](https://www.mongodb.com/)
        - [ElasticSearch](https://www.elastic.co/)
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
        - [Ansible](https://github.com/ansible/ansible)
        - [Chef](https://github.com/chef/chef)
        - [Puppet](https://github.com/puppetlabs/puppet)
        - [Terraform](https://github.com/hashicorp/terraform)
    - Jobs/Workers
        - Job Scheduling
            - [Cron](https://en.wikipedia.org/wiki/Cron)
        - Job Queues
    - Monitoring
    - Containers
        - Engines
            - [Docker](https://docs.docker.com/)
        - Orchestrators
            - [Kubernetes](https://kubernetes.io/)
            - [Nomad](https://www.nomadproject.io/)
            - [Docker Swarm](https://docs.docker.com/engine/swarm/)
    - Communication
        - Message Queues
        - Message Systems
            - [RabbitMQ](https://www.rabbitmq.com/)
            - [Kafka](https://kafka.apache.org/)
    - Extract, Transform, Load (ETL)
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
            - [AWS](https://aws.amazon.com/about-aws/)
            - [Google Cloud](https://cloud.google.com/)
            - [Azure](https://docs.microsoft.com/en-gb/azure)
            - [Heroku](https://dashboard.heroku.com/)
            - [Digital Ocean](https://www.digitalocean.com/)
        - Dedicated Hosting
            - [Hetzner](https://www.hetzner.com/)
    - Resiliency
        - [Chaos Engineering](https://en.wikipedia.org/wiki/Chaos_engineering)
    - Networking
        - Load Balancers
        - DNS
