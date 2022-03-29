# Taskcontrols

Workflow Automation Library with support for Concurrent or Event based processes or activities in Local/Network Automation Tasks, including CI/CD activities.

* taskcontrol (py-taskcontrol) is a python library to create tasks in and based on named taskflow controls. It allows middlewares before and after each task with support for concurrent processing. taskcontrol can run single or multiple tasks during task invocation/runs.
* It provides a simple decorator called task that takes arguments to set up the named taskflow controls. It also provides methods to create a plugin and allow working with tasks as a module and/or pre-created ordered task list. Taskcontrol allows for scaling of plugin development with various utilities like authentication, logging, concurrency, sockets, events, publisher-subscriber architectures, webhooks, client-server http api servers etc.

#### [Actively Developed, Funding Invited]

`pip3 install taskcontrol`

Read more about it here: [https://taskcontrols.github.io/](https://taskcontrols.github.io/) or [https://github.com/taskcontrols/py-taskcontrol](https://github.com/taskcontrols/py-taskcontrol)


### Features

* Create Named task controls (tasks) - instance isolated and shared
* Allows creation of before / after middlewares for each task with access read-only contexts and results of middlewares/tasks
* Allows merging two instances of taskcontrols with namespace clash handling
* Run instance, shared, and mix of tasks (individual or all groups)
* Allows working with Logging, Sockets, Events, Queues, etc
* Allows working with Publisher-Subscriber Architectures, Client-Agent Architectures, Webhooks
* In-Development:
    - Allows support for / working with Concurrency
    - Allows working with Commands & Scripts (T), SSH (T), etc
    - Allows working with Scheduling (T), Files (T - normal, yaml, ini, and csv), etc
    - Allows working with ORMs/Databases (T), Authentication (T)
    - Allows creating, registering, and using tasks / workflows as a plugin
    - Planned Integrations with Subversioning, Build Tools, Deployment
    - Planned Integrations with Data Transformation / Analytics Tooling
    - Planned Integrations with Testing, and Infrastructure Automation toolings
    - Monitoring Support (T)
    - Allows working with best practices like Dependency Injection (T) within the library (including Tasks, Workflow)
    - Hooks support after dependency-injection package integration
    - Provided in and Allows plugins support for Python, Javascript languages
