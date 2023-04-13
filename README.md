# Markprompt Data

This repository contains the following files:

docs.package.json
.
├── README.md
├── community
│   └── community
│       ├── cloud-resources
│       │   ├── cloud-resources.md
│       │   ├── clouds-public.yaml
│       │   ├── clouds.yaml.sample
│       │   ├── getting-started-openstack.md
│       │   ├── plusserver-gx-scs.md
│       │   └── wavestack.md
│       ├── collaboration.md
│       ├── communication
│       │   ├── jitsi.md
│       │   ├── mailinglists.md
│       │   └── matrix.md
│       ├── contribute
│       │   ├── adding-docs-guide.md
│       │   ├── doc-files-structure-guide.md
│       │   ├── docs-workflow-explanation.md
│       │   ├── linting-guide.md
│       │   ├── local-docusaurus-development-guide.mdx
│       │   └── styleguide.md
│       ├── github
│       │   ├── branchprotection.md
│       │   ├── dco-and-licenses.md
│       │   ├── github-failed-dco.png
│       │   └── tips-and-tricks.md
│       └── license-considerations.md
└── docs
    ├── k8s-cluster-api-provider
    │   └── doc
    │       ├── LoadBalancer-ExtTrafficLocal.md
    │       ├── Maintenance_and_Troubleshooting.md
    │       ├── Upgrade-Guide.md
    │       ├── application-credentials.md
    │       ├── configuration.md
    │       ├── getting-started.md
    │       ├── overview.md
    │       ├── quickstart.md
    │       ├── requirements.md
    │       ├── roadmap.md
    │       ├── teardown.md
    │       └── usage
    │           ├── cluster-mgmt-capi-mgmt-node.md
    │           ├── create-new-cluster.md
    │           ├── managing-many-clusters.md
    │           ├── multi-az-and-multi-cloud-environments.md
    │           ├── testing.md
    │           └── usage.md
    ├── operations
    │   ├── iaas
    │   │   └── LBaaS
    │   │       ├── Amphora-diagram.drawio
    │   │       ├── Amphora-diagram.png
    │   │       ├── LoadbalancerShema.drawio
    │   │       ├── LoadbalancerShema1.png
    │   │       ├── dsr.drawio
    │   │       ├── dsr.png
    │   │       ├── lbaas.md
    │   │       ├── natbased.drawio
    │   │       ├── natbased.png
    │   │       ├── reverse-proxy.drawio
    │   │       └── reverse-proxy.png
    │   ├── iam
    │   │   └── intra-SCS-federation-setup-description-for-osism-doc-operations.md
    │   ├── kaas
    │   └── operations
    ├── release-notes
    │   ├── home
    │   │   └── runner
    │   │       └── work
    │   │           └── markprompt-data
    │   │               └── markprompt-data
    │   │                   └── repo_to_be_edited
    │   │                       └── release-notes
    │   │                           ├── Release0.md
    │   │                           ├── Release1.md
    │   │                           ├── Release2.md
    │   │                           ├── Release3.md
    │   │                           ├── Release4.md
    │   │                           └── ReleaseX.md
    │   └── repo_to_be_edited
    │       └── release-notes
    │           ├── Release0.md
    │           ├── Release1.md
    │           ├── Release2.md
    │           ├── Release3.md
    │           ├── Release4.md
    │           └── ReleaseX.md
    ├── status-page-openapi
    │   └── docs
    │       ├── components.md
    │       ├── levels_of_consensus.md
    │       └── overview.md
    └── testbed
        ├── cloud-in-a-box
        │   └── doc
        │       ├── images
        │       │   └── broken_disk_setup.png
        │       └── quickstart.md
        └── doc
            ├── LICENSE
            ├── authentication.md
            ├── configuration.md
            ├── contribute.md
            ├── getting_started.md
            ├── images
            │   ├── ara.png
            │   ├── ceph-dashboard.png
            │   ├── grafana.png
            │   ├── homer.png
            │   ├── horizon-login-identity-testbed.png
            │   ├── horizon.png
            │   ├── keycloak.png
            │   ├── logo.png
            │   ├── netbox.png
            │   ├── netdata.png
            │   ├── overview.png
            │   ├── patchman.png
            │   └── stack-topology.png
            ├── important_notes.md
            ├── license.md
            ├── networking.md
            ├── overview.md
            ├── preparations.md
            ├── quickstart.md
            ├── requirements.md
            ├── requirements.txt
            └── usage.md

34 directories, 95 files

**NOTE:** This repository is only a snapshot of the files defined in the `docs.package.json` file for training purposes. Do **not** manually commit to this repository.
.
├── README.md
├── community
│   └── community
│       ├── cloud-resources
│       │   ├── cloud-resources.md
│       │   ├── clouds-public.yaml
│       │   ├── clouds.yaml.sample
│       │   ├── getting-started-openstack.md
│       │   ├── plusserver-gx-scs.md
│       │   └── wavestack.md
│       ├── collaboration.md
│       ├── communication
│       │   ├── jitsi.md
│       │   ├── mailinglists.md
│       │   └── matrix.md
│       ├── contribute
│       │   ├── adding-docs-guide.md
│       │   ├── doc-files-structure-guide.md
│       │   ├── docs-workflow-explanation.md
│       │   ├── linting-guide.md
│       │   ├── local-docusaurus-development-guide.mdx
│       │   └── styleguide.md
│       ├── github
│       │   ├── branchprotection.md
│       │   ├── dco-and-licenses.md
│       │   ├── github-failed-dco.png
│       │   └── tips-and-tricks.md
│       └── license-considerations.md
└── docs
    ├── k8s-cluster-api-provider
    │   └── doc
    │       ├── LoadBalancer-ExtTrafficLocal.md
    │       ├── Maintenance_and_Troubleshooting.md
    │       ├── Upgrade-Guide.md
    │       ├── application-credentials.md
    │       ├── configuration.md
    │       ├── getting-started.md
    │       ├── overview.md
    │       ├── quickstart.md
    │       ├── requirements.md
    │       ├── roadmap.md
    │       ├── teardown.md
    │       └── usage
    │           ├── cluster-mgmt-capi-mgmt-node.md
    │           ├── create-new-cluster.md
    │           ├── managing-many-clusters.md
    │           ├── multi-az-and-multi-cloud-environments.md
    │           ├── testing.md
    │           └── usage.md
    ├── operations
    │   ├── iaas
    │   │   └── LBaaS
    │   │       ├── Amphora-diagram.drawio
    │   │       ├── Amphora-diagram.png
    │   │       ├── LoadbalancerShema.drawio
    │   │       ├── LoadbalancerShema1.png
    │   │       ├── dsr.drawio
    │   │       ├── dsr.png
    │   │       ├── lbaas.md
    │   │       ├── natbased.drawio
    │   │       ├── natbased.png
    │   │       ├── reverse-proxy.drawio
    │   │       └── reverse-proxy.png
    │   ├── iam
    │   │   └── intra-SCS-federation-setup-description-for-osism-doc-operations.md
    │   ├── kaas
    │   └── operations
    ├── release-notes
    │   ├── home
    │   │   └── runner
    │   │       └── work
    │   │           └── markprompt-data
    │   │               └── markprompt-data
    │   │                   └── repo_to_be_edited
    │   │                       └── release-notes
    │   │                           ├── Release0.md
    │   │                           ├── Release1.md
    │   │                           ├── Release2.md
    │   │                           ├── Release3.md
    │   │                           ├── Release4.md
    │   │                           └── ReleaseX.md
    │   └── repo_to_be_edited
    │       └── release-notes
    │           ├── Release0.md
    │           ├── Release1.md
    │           ├── Release2.md
    │           ├── Release3.md
    │           ├── Release4.md
    │           └── ReleaseX.md
    ├── status-page-openapi
    │   └── docs
    │       ├── components.md
    │       ├── levels_of_consensus.md
    │       └── overview.md
    └── testbed
        ├── cloud-in-a-box
        │   └── doc
        │       ├── images
        │       │   └── broken_disk_setup.png
        │       └── quickstart.md
        └── doc
            ├── LICENSE
            ├── authentication.md
            ├── configuration.md
            ├── contribute.md
            ├── getting_started.md
            ├── images
            │   ├── ara.png
            │   ├── ceph-dashboard.png
            │   ├── grafana.png
            │   ├── homer.png
            │   ├── horizon-login-identity-testbed.png
            │   ├── horizon.png
            │   ├── keycloak.png
            │   ├── logo.png
            │   ├── netbox.png
            │   ├── netdata.png
            │   ├── overview.png
            │   ├── patchman.png
            │   └── stack-topology.png
            ├── important_notes.md
            ├── license.md
            ├── networking.md
            ├── overview.md
            ├── preparations.md
            ├── quickstart.md
            ├── requirements.md
            ├── requirements.txt
            └── usage.md

34 directories, 95 files

**NOTE:** This repository is only a snapshot of the files defined in the `docs.package.json` file for training purposes. Do **not** manually commit to this repository.
.
├── README.md
├── community
│   └── community
│       ├── cloud-resources
│       │   ├── cloud-resources.md
│       │   ├── clouds-public.yaml
│       │   ├── clouds.yaml.sample
│       │   ├── getting-started-openstack.md
│       │   ├── plusserver-gx-scs.md
│       │   └── wavestack.md
│       ├── collaboration.md
│       ├── communication
│       │   ├── jitsi.md
│       │   ├── mailinglists.md
│       │   └── matrix.md
│       ├── contribute
│       │   ├── adding-docs-guide.md
│       │   ├── doc-files-structure-guide.md
│       │   ├── docs-workflow-explanation.md
│       │   ├── linting-guide.md
│       │   ├── local-docusaurus-development-guide.mdx
│       │   └── styleguide.md
│       ├── github
│       │   ├── branchprotection.md
│       │   ├── dco-and-licenses.md
│       │   ├── github-failed-dco.png
│       │   └── tips-and-tricks.md
│       └── license-considerations.md
└── docs
    ├── k8s-cluster-api-provider
    │   └── doc
    │       ├── LoadBalancer-ExtTrafficLocal.md
    │       ├── Maintenance_and_Troubleshooting.md
    │       ├── Upgrade-Guide.md
    │       ├── application-credentials.md
    │       ├── configuration.md
    │       ├── getting-started.md
    │       ├── overview.md
    │       ├── quickstart.md
    │       ├── requirements.md
    │       ├── roadmap.md
    │       ├── teardown.md
    │       └── usage
    │           ├── cluster-mgmt-capi-mgmt-node.md
    │           ├── create-new-cluster.md
    │           ├── managing-many-clusters.md
    │           ├── multi-az-and-multi-cloud-environments.md
    │           ├── testing.md
    │           └── usage.md
    ├── operations
    │   ├── iaas
    │   │   └── LBaaS
    │   │       ├── Amphora-diagram.drawio
    │   │       ├── Amphora-diagram.png
    │   │       ├── LoadbalancerShema.drawio
    │   │       ├── LoadbalancerShema1.png
    │   │       ├── dsr.drawio
    │   │       ├── dsr.png
    │   │       ├── lbaas.md
    │   │       ├── natbased.drawio
    │   │       ├── natbased.png
    │   │       ├── reverse-proxy.drawio
    │   │       └── reverse-proxy.png
    │   ├── iam
    │   │   └── intra-SCS-federation-setup-description-for-osism-doc-operations.md
    │   ├── kaas
    │   └── operations
    ├── release-notes
    │   ├── Release0.md
    │   ├── Release1.md
    │   ├── Release2.md
    │   ├── Release3.md
    │   ├── Release4.md
    │   ├── ReleaseX.md
    │   ├── home
    │   │   └── runner
    │   │       └── work
    │   │           └── markprompt-data
    │   │               └── markprompt-data
    │   │                   └── repo_to_be_edited
    │   │                       └── release-notes
    │   │                           ├── Release0.md
    │   │                           ├── Release1.md
    │   │                           ├── Release2.md
    │   │                           ├── Release3.md
    │   │                           ├── Release4.md
    │   │                           └── ReleaseX.md
    │   └── repo_to_be_edited
    │       └── release-notes
    │           ├── Release0.md
    │           ├── Release1.md
    │           ├── Release2.md
    │           ├── Release3.md
    │           ├── Release4.md
    │           └── ReleaseX.md
    ├── status-page-openapi
    │   └── docs
    │       ├── components.md
    │       ├── levels_of_consensus.md
    │       └── overview.md
    └── testbed
        ├── cloud-in-a-box
        │   └── doc
        │       ├── images
        │       │   └── broken_disk_setup.png
        │       └── quickstart.md
        └── doc
            ├── LICENSE
            ├── authentication.md
            ├── configuration.md
            ├── contribute.md
            ├── getting_started.md
            ├── images
            │   ├── ara.png
            │   ├── ceph-dashboard.png
            │   ├── grafana.png
            │   ├── homer.png
            │   ├── horizon-login-identity-testbed.png
            │   ├── horizon.png
            │   ├── keycloak.png
            │   ├── logo.png
            │   ├── netbox.png
            │   ├── netdata.png
            │   ├── overview.png
            │   ├── patchman.png
            │   └── stack-topology.png
            ├── important_notes.md
            ├── license.md
            ├── networking.md
            ├── overview.md
            ├── preparations.md
            ├── quickstart.md
            ├── requirements.md
            ├── requirements.txt
            └── usage.md

34 directories, 101 files

**NOTE:** This repository is only a snapshot of the files defined in the `docs.package.json` file for training purposes. Do **not** manually commit to this repository.
.
├── README.md
├── community
│   └── community
│       ├── cloud-resources
│       │   ├── cloud-resources.md
│       │   ├── clouds-public.yaml
│       │   ├── clouds.yaml.sample
│       │   ├── getting-started-openstack.md
│       │   ├── plusserver-gx-scs.md
│       │   └── wavestack.md
│       ├── collaboration.md
│       ├── communication
│       │   ├── jitsi.md
│       │   ├── mailinglists.md
│       │   └── matrix.md
│       ├── contribute
│       │   ├── adding-docs-guide.md
│       │   ├── doc-files-structure-guide.md
│       │   ├── docs-workflow-explanation.md
│       │   ├── linting-guide.md
│       │   ├── local-docusaurus-development-guide.mdx
│       │   └── styleguide.md
│       ├── github
│       │   ├── branchprotection.md
│       │   ├── dco-and-licenses.md
│       │   ├── github-failed-dco.png
│       │   └── tips-and-tricks.md
│       └── license-considerations.md
└── docs
    ├── k8s-cluster-api-provider
    │   └── doc
    │       ├── LoadBalancer-ExtTrafficLocal.md
    │       ├── Maintenance_and_Troubleshooting.md
    │       ├── Upgrade-Guide.md
    │       ├── application-credentials.md
    │       ├── configuration.md
    │       ├── getting-started.md
    │       ├── overview.md
    │       ├── quickstart.md
    │       ├── requirements.md
    │       ├── roadmap.md
    │       ├── teardown.md
    │       └── usage
    │           ├── cluster-mgmt-capi-mgmt-node.md
    │           ├── create-new-cluster.md
    │           ├── managing-many-clusters.md
    │           ├── multi-az-and-multi-cloud-environments.md
    │           ├── testing.md
    │           └── usage.md
    ├── openstack-image-manager
    │   ├── configuration.md
    │   ├── contribute.md
    │   ├── getting_started.md
    │   ├── overview.md
    │   ├── quickstart.md
    │   └── requirements.md
    ├── operations
    │   ├── iaas
    │   │   └── LBaaS
    │   │       ├── Amphora-diagram.drawio
    │   │       ├── Amphora-diagram.png
    │   │       ├── LoadbalancerShema.drawio
    │   │       ├── LoadbalancerShema1.png
    │   │       ├── dsr.drawio
    │   │       ├── dsr.png
    │   │       ├── lbaas.md
    │   │       ├── natbased.drawio
    │   │       ├── natbased.png
    │   │       ├── reverse-proxy.drawio
    │   │       └── reverse-proxy.png
    │   ├── iam
    │   │   └── intra-SCS-federation-setup-description-for-osism-doc-operations.md
    │   ├── kaas
    │   └── operations
    ├── release-notes
    │   ├── Release0.md
    │   ├── Release1.md
    │   ├── Release2.md
    │   ├── Release3.md
    │   ├── Release4.md
    │   ├── ReleaseX.md
    │   ├── home
    │   │   └── runner
    │   │       └── work
    │   │           └── markprompt-data
    │   │               └── markprompt-data
    │   │                   └── repo_to_be_edited
    │   │                       └── release-notes
    │   │                           ├── Release0.md
    │   │                           ├── Release1.md
    │   │                           ├── Release2.md
    │   │                           ├── Release3.md
    │   │                           ├── Release4.md
    │   │                           └── ReleaseX.md
    │   └── repo_to_be_edited
    │       └── release-notes
    │           ├── Release0.md
    │           ├── Release1.md
    │           ├── Release2.md
    │           ├── Release3.md
    │           ├── Release4.md
    │           └── ReleaseX.md
    ├── status-page-openapi
    │   └── docs
    │       ├── components.md
    │       ├── levels_of_consensus.md
    │       └── overview.md
    └── testbed
        ├── cloud-in-a-box
        │   └── doc
        │       ├── images
        │       │   └── broken_disk_setup.png
        │       └── quickstart.md
        └── doc
            ├── LICENSE
            ├── authentication.md
            ├── configuration.md
            ├── contribute.md
            ├── getting_started.md
            ├── images
            │   ├── ara.png
            │   ├── ceph-dashboard.png
            │   ├── grafana.png
            │   ├── homer.png
            │   ├── horizon-login-identity-testbed.png
            │   ├── horizon.png
            │   ├── keycloak.png
            │   ├── logo.png
            │   ├── netbox.png
            │   ├── netdata.png
            │   ├── overview.png
            │   ├── patchman.png
            │   └── stack-topology.png
            ├── important_notes.md
            ├── license.md
            ├── networking.md
            ├── overview.md
            ├── preparations.md
            ├── quickstart.md
            ├── requirements.md
            ├── requirements.txt
            └── usage.md

35 directories, 107 files

**NOTE:** This repository is only a snapshot of the files defined in the `docs.package.json` file for training purposes. Do **not** manually commit to this repository.
