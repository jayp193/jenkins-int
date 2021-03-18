# SCM for Device Configurations on Aruba Central
This is source repository holding all the configuration templates and variable files for Aruba Access Points and CX Swtiches on a per-group basis.
Directory Structure:
    .
    ├── ...
    ├── Group                    # Documentation files (alternatively `doc`)
    │   ├── templates 
            |
            # Table of contents
    │   ├── variables             # Frequently asked questions
    │              # etc.
    └── ...
    ```bash
├── Group
│   ├── templates
│   │   ├── CX
|   |   ├── IAP
|   |
│   ├── variables
│   │   ├── CX
│   └── ├── IAP
|
├── README.md
└── .gitignore

```

```bash
├── app
│   ├── css
│   │   ├── **/*.css
│   ├── favicon.ico
│   ├── images
│   ├── index.html
│   ├── js
│   │   ├── **/*.js
│   └── partials/template
├── dist (or build)
├── node_modules
├── bower_components (if using bower)
├── test
├── Gruntfile.js/gulpfile.js
├── README.md
├── package.json
├── bower.json (if using bower)
└── .gitignore
```

- Jenkins integration with GitHub 
- GitHub Webhooks are sent as a JSON payload to Jenkins, when a change is made to a templates/variables file
- This webhook acts as a trigger for the Jenkins pipeline which is used to build a job
- A Build in Jenkins is nothing but a set of steps that Jenkins is configured to perform
