# Open Targets release snapshots
This repo contains snapshots for all the components used to generate a release
of the Open Targets Platform.

To get the latest release, use the following command:

```bash
git clone git@github.com:opentargets/ot-snapshots.git --recurse-submodules
```

To get a particular release, use the following command:

```bash
git clone git@github.com:opentargets/ot-snapshots.git
cd ot-snapshots
git checkout <release-tag>
git submodule update --init --recursive
```

## Components
### Data schemas
- [json_schema](https://github.com/opentargets/json_schema) — Schemas of the Open Targets Platform data models
- [ot_croissant](https://github.com/opentargets/ot_croissant) — Croissant File exporter

### Data generation
- [curation](https://github.com/opentargets/curation) — Curation repository
- [OnToma](https://github.com/opentargets/OnToma) — Python module which maps the disease or phenotype terms to EFO
- [gentropy](https://github.com/opentargets/gentropy) — Open Targets' Genomics Toolkit
- [clinical_mining](https://github.com/opentargets/clinical_mining) — Clinical mining pipeline

### Pipeline
- [orchestration](https://github.com/opentargets/orchestration) — Pipeline orchestrator
- [pis](https://github.com/opentargets/platform-input-support) — Pipeline Input Stage
- [pts](https://github.com/opentargets/ontoform) — Pipeline Transformation Stage
- [platform-output-support](https://github.com/opentargets/platform-output-support) — Output data generation application

### Platform web applicationd
- [ot-ui-apps](https://github.com/opentargets/ot-ui-apps) — Web App
- [ot-ai-api](https://github.com/opentargets/ot-ai-api) — AI API
- [platform-api](https://github.com/opentargets/platform-api) — API
- [platform-deployment-nextgen](https://github.com/opentargets/platform-deployment-nextgen) — Kubernetes infrastructure definition

## Copyright

Copyright 2014-2025 EMBL - European Bioinformatics Institute, Genentech, GSK,
MSD, Pfizer, Sanofi and Wellcome Sanger Institute

This software was developed as part of the Open Targets project. For more
information please see: http://www.opentargets.org

Licensed under the Apache License, Version 2.0 (the "License");
you may not use this file except in compliance with the License.
You may obtain a copy of the License at

http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.
