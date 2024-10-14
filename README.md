# mjpdevopslabs

# File structure

.
├── .github
│   └── workflows
│       └── pipeline.yml
├── terraform
│   └── main.tf
├── ansible
│   ├── inventory
│   │   └── hosts
│   └── playbook.yml
├── docker
│   └── services
│       ├── userservice
│       │   └── Dockerfile
│       └── paymentservice
│           └── Dockerfile
└── k8s
    └── deployments
        ├── userservice.yaml
        └── paymentservice.yaml
