# Anna's Index of Markdown Files

This index contains links to all markdown files in the vets-api repository with one-sentence summaries.

## Files

### Root Level Documentation
- [README.md](../vets-api/README.md) - Main project documentation providing common APIs for applications that live on VA.gov.
- [CONTRIBUTING.md](../vets-api/CONTRIBUTING.md) - Guidelines for contributing to vets-api projects with links to developer documentation.
- [LICENSE.md](../vets-api/LICENSE.md) - License information stating this project is in the public domain as a work of the United States Government.
- [SECURITY.md](../vets-api/SECURITY.md) - Security policy directing users to report security issues through the Department of Veterans Affairs Bugcrowd program.

### Documentation Directory
- [docs/index.md](../vets-api/docs/index.md) - Documentation index providing common APIs for applications that live on VA.gov with project overview.
- [docs/HISTORY.md](../vets-api/docs/HISTORY.md) - Document tracking removal and deprecation of API resources and functionality in vets-api.

### GitHub Configuration
- [.github/copilot-instructions.md](../vets-api/.github/copilot-instructions.md) - GitHub Copilot configuration and development guidelines for the vets-api repository.
- [.github/PULL_REQUEST_TEMPLATE.md](../vets-api/.github/PULL_REQUEST_TEMPLATE.md) - Template for pull request descriptions and checklists with CI requirements.
- [.github/instructions/my-health-messaging.instructions.md](../vets-api/.github/instructions/my-health-messaging.instructions.md) - Path-specific Copilot instructions for My Health Secure Messaging features.
- [.github/instructions/my-health-prescriptions.instructions.md](../vets-api/.github/instructions/my-health-prescriptions.instructions.md) - Path-specific Copilot instructions for My Health Prescriptions features.
- [.github/instructions/my-health-medical-records.instructions.md](../vets-api/.github/instructions/my-health-medical-records.instructions.md) - Path-specific Copilot instructions for My Health Medical Records features.
- [.github/scripts/validate-datadog-yaml/README.md](../vets-api/.github/scripts/validate-datadog-yaml/README.md) - Documentation for validating Datadog YAML configuration files.

### Setup Documentation
- [docs/setup/running_natively.md](../vets-api/docs/setup/running_natively.md) - Instructions for running vets-api natively with Redis and PostgreSQL dependencies.
- [docs/setup/running_docker.md](../vets-api/docs/setup/running_docker.md) - Instructions for running the application with Docker including ClamAV antivirus configuration.
- [docs/setup/mhv.md](../vets-api/docs/setup/mhv.md) - Setup instructions for MHV (MyHealtheVet) prescriptions and secure messaging configuration.
- [docs/setup/mpi.md](../vets-api/docs/setup/mpi.md) - Setup documentation for Master Patient Index integration.
- [docs/setup/mailer.md](../vets-api/docs/setup/mailer.md) - Configuration instructions for email delivery systems.
- [docs/setup/facilities_locator.md](../vets-api/docs/setup/facilities_locator.md) - Setup guide for VA facilities locator service integration.
- [docs/setup/evss.md](../vets-api/docs/setup/evss.md) - Configuration documentation for External Veterans Services System integration.
- [docs/setup/edu_benefits.md](../vets-api/docs/setup/edu_benefits.md) - Setup instructions for education benefits functionality.
- [docs/setup/betamocks.md](../vets-api/docs/setup/betamocks.md) - Documentation for beta mocking services configuration.
- [docs/setup/rswag_setup.md](../vets-api/docs/setup/rswag_setup.md) - Setup instructions for RSwag API documentation generation.
- [docs/setup/binstubs.md](../vets-api/docs/setup/binstubs.md) - Documentation for binary stub configuration and usage.
- [docs/setup/setup_with_binstubs.md](../vets-api/docs/setup/setup_with_binstubs.md) - Setup instructions using binary stubs for development.
- [docs/setup/running_binstubs.md](../vets-api/docs/setup/running_binstubs.md) - Instructions for running the application using binary stubs.
- [docs/setup/codespaces.md](../vets-api/docs/setup/codespaces.md) - Setup guide for running vets-api in GitHub Codespaces.
- [docs/setup/local_network_access.md](../vets-api/docs/setup/local_network_access.md) - Configuration for local network access during development.
- [docs/setup/local-openresty.md](../vets-api/docs/setup/local-openresty.md) - Setup instructions for local OpenResty reverse proxy.
- [docs/setup/local-traefik.md](../vets-api/docs/setup/local-traefik.md) - Configuration guide for local Traefik reverse proxy.
- [docs/setup/virtual_machine_access.md](../vets-api/docs/setup/virtual_machine_access.md) - Instructions for accessing vets-api from virtual machines.
- [docs/setup/new_machine.md](../vets-api/docs/setup/new_machine.md) - Complete setup guide for configuring vets-api on a new development machine.
- [docs/setup/native.md](../vets-api/docs/setup/native.md) - Native installation and configuration instructions.
- [docs/setup/docker.md](../vets-api/docs/setup/docker.md) - Docker-based development environment setup guide.
- [docs/setup/hybrid.md](../vets-api/docs/setup/hybrid.md) - Hybrid development setup combining native and containerized components.

### Module Documentation
- [modules/appeals_api/README.md](../vets-api/modules/appeals_api/README.md) - Appeals API module for automating the appeals process and reducing claim backlog through API integration.
- [modules/claims_api/README.md](../vets-api/modules/claims_api/README.md) - Benefits Claims API module with instructions for connecting to upstream services locally.
- [modules/my_health/README.md](../vets-api/modules/my_health/README.md) - MyHealth API endpoints for My Health features on VA.gov.
- [modules/mobile/README.md](../vets-api/modules/mobile/README.md) - Mobile API module for VA mobile applications.
- [modules/decision_reviews/README.md](../vets-api/modules/decision_reviews/README.md) - Decision Reviews module for processing appeal decisions.
- [modules/simple_forms_api/README.md](../vets-api/modules/simple_forms_api/README.md) - Simple Forms API module for handling form submissions and processing.
- [modules/vba_documents/README.md](../vets-api/modules/vba_documents/README.md) - VBA Documents module for document upload and management functionality.
- [modules/pensions/README.md](../vets-api/modules/pensions/README.md) - Pensions module for handling pension-related claims and processing.
- [modules/burials/README.md](../vets-api/modules/burials/README.md) - Burials module for burial benefits and claims processing.
- [modules/check_in/README.md](../vets-api/modules/check_in/README.md) - Check-in module for appointment and visit check-in functionality.
- [modules/meb_api/README.md](../vets-api/modules/meb_api/README.md) - MEB API module for Montgomery GI Bill education benefits.
- [modules/ivc_champva/README.md](../vets-api/modules/ivc_champva/README.md) - IVC CHAMPVA module for Civilian Health and Medical Program processing.
- [modules/income_and_assets/README.md](../vets-api/modules/income_and_assets/README.md) - Income and Assets module for financial information processing.
- [modules/income_limits/README.md](../vets-api/modules/income_limits/README.md) - Income Limits module for determining benefit eligibility thresholds.
- [modules/travel_claims/README.md](../vets-api/modules/travel_claims/README.md) - Travel Claims module for veteran travel reimbursement processing.
- [modules/va_notify/README.md](../vets-api/modules/va_notify/README.md) - VA Notify module for notification services and messaging.
- [modules/vass/README.md](../vets-api/modules/vass/README.md) - VASS module for VA Scheduling System integration.
- [modules/mocked_authentication/README.md](../vets-api/modules/mocked_authentication/README.md) - Mocked Authentication module for development and testing environments.

### Library Documentation
- [lib/common/README.md](../vets-api/lib/common/README.md) - Common library utilities and shared functionality across the application.
- [lib/common/client/README.md](../vets-api/lib/common/client/README.md) - Common client library for HTTP service integrations and API calls.
- [lib/flipper/README.md](../vets-api/lib/flipper/README.md) - Flipper feature flag library configuration and usage documentation.
- [lib/logging/README.md](../vets-api/lib/logging/README.md) - Logging library for structured application logging and monitoring.
- [lib/lighthouse/benefits_intake/README.md](../vets-api/lib/lighthouse/benefits_intake/README.md) - Lighthouse Benefits Intake API client library documentation.
- [lib/lighthouse/benefits_claims/README.md](../vets-api/lib/lighthouse/benefits_claims/README.md) - Lighthouse Benefits Claims API client library documentation.
- [lib/carma/README.md](../vets-api/lib/carma/README.md) - CARMA integration library for case management functionality.
- [lib/chip/README.md](../vets-api/lib/chip/README.md) - CHIP library for healthcare integration services.
- [lib/vetext/README.md](../vets-api/lib/vetext/README.md) - VEText library for veteran text messaging services.
- [lib/vets/README.md](../vets-api/lib/vets/README.md) - Core Vets library with shared veteran-specific utilities.
- [lib/unified_health_data/README.md](../vets-api/lib/unified_health_data/README.md) - Unified Health Data library for health record integration.
- [lib/veteran_facing_services/README.md](../vets-api/lib/veteran_facing_services/README.md) - Veteran Facing Services library for public-facing API functionality.
- [lib/forms/submission_statuses/README.md](../vets-api/lib/forms/submission_statuses/README.md) - Form submission status tracking and management library.
- [lib/persistent_attachments/README.md](../vets-api/lib/persistent_attachments/README.md) - Persistent Attachments library for file upload and storage management.
- [lib/pdf_fill/forms/field_mappings/readme.md](../vets-api/lib/pdf_fill/forms/field_mappings/readme.md) - PDF field mappings generator for populating VA form templates with data.

### Application Documentation
- [app/sidekiq/education_form/README.md](../vets-api/app/sidekiq/education_form/README.md) - Education form background job processing documentation.
- [app/swagger/readme.md](../vets-api/app/swagger/readme.md) - Swagger API documentation configuration and setup instructions.
- [bin/lib/vets-api/README.md](../vets-api/bin/lib/vets-api/README.md) - Binary utilities and command-line tools for vets-api development.

### Configuration Documentation
- [config/ca-trust/README.md](../vets-api/config/ca-trust/README.md) - Certificate authority trust configuration for secure connections.
- [rakelib/prod/README.md](../vets-api/rakelib/prod/README.md) - Production-specific Rake tasks and deployment utilities.

### Script and Tool Documentation
- [script/vcr_inspector/README.md](../vets-api/script/vcr_inspector/README.md) - VCR cassette inspection tool for analyzing HTTP interaction recordings.
- [script/vcr_inspector/QUICKSTART.md](../vets-api/script/vcr_inspector/QUICKSTART.md) - Quick start guide for using the VCR inspector tool.

### Testing Documentation
- [spec/lib/rx/RECORDING_RX_CASSETTES.md](../vets-api/spec/lib/rx/RECORDING_RX_CASSETTES.md) - Instructions for recording VCR cassettes for prescription (RX) API testing.

### Deployment Documentation
- [docs/deployment/information.md](../vets-api/docs/deployment/information.md) - Deployment information and procedures for vets-api environments.

### Module-Specific Documentation

#### Appeals API Module
- [modules/appeals_api/docs/index.md](../vets-api/modules/appeals_api/docs/index.md) - Appeals API module index and overview documentation.
- [modules/appeals_api/app/swagger/appeals_api/v1/api_description.md](../vets-api/modules/appeals_api/app/swagger/appeals_api/v1/api_description.md) - Appeals API v1 Swagger documentation description.
- [modules/appeals_api/app/swagger/appeals_api/v1/put_description.md](../vets-api/modules/appeals_api/app/swagger/appeals_api/v1/put_description.md) - Appeals API v1 PUT endpoint documentation.
- [modules/appeals_api/app/swagger/appeals_status/v1/api_description.md](../vets-api/modules/appeals_api/app/swagger/appeals_status/v1/api_description.md) - Appeals Status API v1 documentation.
- [modules/appeals_api/app/swagger/appeals_status/v1/api_description_dev.md](../vets-api/modules/appeals_api/app/swagger/appeals_status/v1/api_description_dev.md) - Appeals Status API v1 development documentation.
- [modules/appeals_api/app/swagger/decision_reviews/v2/api_description.md](../vets-api/modules/appeals_api/app/swagger/decision_reviews/v2/api_description.md) - Decision Reviews API v2 documentation.
- [modules/appeals_api/app/swagger/decision_reviews/v2/api_description_dev.md](../vets-api/modules/appeals_api/app/swagger/decision_reviews/v2/api_description_dev.md) - Decision Reviews API v2 development documentation.
- [modules/appeals_api/app/swagger/decision_reviews/v2/put_description.md](../vets-api/modules/appeals_api/app/swagger/decision_reviews/v2/put_description.md) - Decision Reviews API v2 PUT endpoint documentation.
- [modules/appeals_api/app/swagger/higher_level_reviews/v0/api_description.md](../vets-api/modules/appeals_api/app/swagger/higher_level_reviews/v0/api_description.md) - Higher Level Reviews API documentation.
- [modules/appeals_api/app/swagger/higher_level_reviews/v0/api_description_dev.md](../vets-api/modules/appeals_api/app/swagger/higher_level_reviews/v0/api_description_dev.md) - Higher Level Reviews API development documentation.
- [modules/appeals_api/app/swagger/legacy_appeals/v0/api_description.md](../vets-api/modules/appeals_api/app/swagger/legacy_appeals/v0/api_description.md) - Legacy Appeals API documentation.
- [modules/appeals_api/app/swagger/legacy_appeals/v0/api_description_dev.md](../vets-api/modules/appeals_api/app/swagger/legacy_appeals/v0/api_description_dev.md) - Legacy Appeals API development documentation.
- [modules/appeals_api/app/swagger/notice_of_disagreements/v0/api_description.md](../vets-api/modules/appeals_api/app/swagger/notice_of_disagreements/v0/api_description.md) - Notice of Disagreements API documentation.
- [modules/appeals_api/app/swagger/notice_of_disagreements/v0/api_description_dev.md](../vets-api/modules/appeals_api/app/swagger/notice_of_disagreements/v0/api_description_dev.md) - Notice of Disagreements API development documentation.
- [modules/appeals_api/app/swagger/notice_of_disagreements/v0/put_description.md](../vets-api/modules/appeals_api/app/swagger/notice_of_disagreements/v0/put_description.md) - Notice of Disagreements API PUT endpoint documentation.
- [modules/appeals_api/app/swagger/supplemental_claims/v0/api_description.md](../vets-api/modules/appeals_api/app/swagger/supplemental_claims/v0/api_description.md) - Supplemental Claims API documentation.
- [modules/appeals_api/app/swagger/supplemental_claims/v0/api_description_dev.md](../vets-api/modules/appeals_api/app/swagger/supplemental_claims/v0/api_description_dev.md) - Supplemental Claims API development documentation.
- [modules/appeals_api/app/swagger/supplemental_claims/v0/put_description.md](../vets-api/modules/appeals_api/app/swagger/supplemental_claims/v0/put_description.md) - Supplemental Claims API PUT endpoint documentation.
- [modules/appeals_api/app/swagger/appealable_issues/v0/api_description.md](../vets-api/modules/appeals_api/app/swagger/appealable_issues/v0/api_description.md) - Appealable Issues API documentation.
- [modules/appeals_api/app/swagger/appealable_issues/v0/api_description_dev.md](../vets-api/modules/appeals_api/app/swagger/appealable_issues/v0/api_description_dev.md) - Appealable Issues API development documentation.

#### Claims API Module
- [modules/claims_api/docs/index.md](../vets-api/modules/claims_api/docs/index.md) - Claims API module index and overview documentation.
- [modules/claims_api/app/swagger/claims_api/description/v1.md](../vets-api/modules/claims_api/app/swagger/claims_api/description/v1.md) - Claims API v1 Swagger description documentation.
- [modules/claims_api/app/swagger/claims_api/description/v2.md](../vets-api/modules/claims_api/app/swagger/claims_api/description/v2.md) - Claims API v2 Swagger description documentation.

#### VBA Documents Module
- [modules/vba_documents/app/swagger/vba_documents/v1/description.md](../vets-api/modules/vba_documents/app/swagger/vba_documents/v1/description.md) - VBA Documents API v1 description documentation.
- [modules/vba_documents/app/swagger/vba_documents/document_upload/v1/status_description.md](../vets-api/modules/vba_documents/app/swagger/vba_documents/document_upload/v1/status_description.md) - VBA Documents upload status description for v1.
- [modules/vba_documents/app/swagger/vba_documents/document_upload/status_description.md](../vets-api/modules/vba_documents/app/swagger/vba_documents/document_upload/status_description.md) - VBA Documents upload status description.
- [modules/vba_documents/app/swagger/vba_documents/document_upload/put_description.md](../vets-api/modules/vba_documents/app/swagger/vba_documents/document_upload/put_description.md) - VBA Documents PUT endpoint description.
- [modules/vba_documents/app/swagger/vba_documents/document_upload/status_code_description.md](../vets-api/modules/vba_documents/app/swagger/vba_documents/document_upload/status_code_description.md) - VBA Documents status code descriptions.
- [modules/vba_documents/app/swagger/vba_documents/document_upload/validate_document_error_details.md](../vets-api/modules/vba_documents/app/swagger/vba_documents/document_upload/validate_document_error_details.md) - VBA Documents validation error details.
- [modules/vba_documents/app/swagger/vba_documents/document_upload/validate_document_description.md](../vets-api/modules/vba_documents/app/swagger/vba_documents/document_upload/validate_document_description.md) - VBA Documents validation description.
- [modules/vba_documents/postman_tests/Benefits_Intake_Postman.md](../vets-api/modules/vba_documents/postman_tests/Benefits_Intake_Postman.md) - Postman test documentation for Benefits Intake functionality.

#### Apps API Module
- [modules/apps_api/app/swagger/apps_api/v0/description.md](../vets-api/modules/apps_api/app/swagger/apps_api/v0/description.md) - Apps API v0 Swagger description documentation.

#### My Health Module
- [modules/my_health/docs/README.md](../vets-api/modules/my_health/docs/README.md) - My Health module documentation overview and API specifications.

#### Mobile Module
- [modules/mobile/docs/README.md](../vets-api/modules/mobile/docs/README.md) - Mobile API module documentation for VA mobile applications.

#### ADR and Architecture Documentation
- [modules/claims_evidence_api/documentation/readme.md](../vets-api/modules/claims_evidence_api/documentation/readme.md) - Claims Evidence API documentation overview and architecture.
- [modules/claims_evidence_api/documentation/adr/0001-record-architecture-decisions.md](../vets-api/modules/claims_evidence_api/documentation/adr/0001-record-architecture-decisions.md) - ADR for recording architecture decisions in Claims Evidence API.
- [modules/claims_evidence_api/documentation/adr/0002-use-modules-folder-for-claims-evidence-api-code.md](../vets-api/modules/claims_evidence_api/documentation/adr/0002-use-modules-folder-for-claims-evidence-api-code.md) - ADR for using modules folder structure in Claims Evidence API.
- [modules/claims_evidence_api/documentation/adr/0003-initial-development-will-focus-on-file-upload.md](../vets-api/modules/claims_evidence_api/documentation/adr/0003-initial-development-will-focus-on-file-upload.md) - ADR for focusing initial development on file upload functionality.
- [modules/claims_evidence_api/documentation/adr/0004-upload-validation-will-use-json-schema.md](../vets-api/modules/claims_evidence_api/documentation/adr/0004-upload-validation-will-use-json-schema.md) - ADR for using JSON schema for upload validation.
- [modules/claims_evidence_api/documentation/adr/0005-database-models-will-inherit-submission-and-submissionattempt.md](../vets-api/modules/claims_evidence_api/documentation/adr/0005-database-models-will-inherit-submission-and-submissionattempt.md) - ADR for database model inheritance structure.
- [modules/claims_evidence_api/documentation/adr/0006-change-service-timeout-to-30-seconds.md](../vets-api/modules/claims_evidence_api/documentation/adr/0006-change-service-timeout-to-30-seconds.md) - ADR for changing service timeout configuration.

#### BPDS Module ADRs
- [modules/bpds/documentation/readme.md](../vets-api/modules/bpds/documentation/readme.md) - BPDS module documentation overview and architecture.
- [modules/bpds/documentation/adr/0001-record-architecture-decisions.md](../vets-api/modules/bpds/documentation/adr/0001-record-architecture-decisions.md) - ADR for recording architecture decisions in BPDS module.
- [modules/bpds/documentation/adr/0002-initial-research-and-findings.md](../vets-api/modules/bpds/documentation/adr/0002-initial-research-and-findings.md) - ADR documenting initial research and findings for BPDS integration.
- [modules/bpds/documentation/adr/0003-received-credentials.md](../vets-api/modules/bpds/documentation/adr/0003-received-credentials.md) - ADR documenting receipt of BPDS credentials.
- [modules/bpds/documentation/adr/0004-successfully-connected-to-bpds.md](../vets-api/modules/bpds/documentation/adr/0004-successfully-connected-to-bpds.md) - ADR documenting successful connection to BPDS service.
- [modules/bpds/documentation/adr/0005-created-service-class.md](../vets-api/modules/bpds/documentation/adr/0005-created-service-class.md) - ADR for creating BPDS service class architecture.
- [modules/bpds/documentation/adr/0006-db-schema-changes.md](../vets-api/modules/bpds/documentation/adr/0006-db-schema-changes.md) - ADR documenting database schema changes for BPDS.
- [modules/bpds/documentation/adr/0007-adding-new-submission-and-attempt-models.md](../vets-api/modules/bpds/documentation/adr/0007-adding-new-submission-and-attempt-models.md) - ADR for adding new submission and attempt models.
- [modules/bpds/documentation/adr/0008-adding-sidekiq-job.md](../vets-api/modules/bpds/documentation/adr/0008-adding-sidekiq-job.md) - ADR for adding Sidekiq background job integration.
- [modules/bpds/documentation/adr/0009-adding-user-identifier-to-bpds-request.md](../vets-api/modules/bpds/documentation/adr/0009-adding-user-identifier-to-bpds-request.md) - ADR for adding user identifier to BPDS requests.

#### Pensions Module ADRs
- [modules/pensions/documentation/readme.md](../vets-api/modules/pensions/documentation/readme.md) - Pensions module documentation overview and architecture.
- [modules/pensions/documentation/adr/0001-record-architecture-decisions.md](../vets-api/modules/pensions/documentation/adr/0001-record-architecture-decisions.md) - ADR for recording architecture decisions in Pensions module.
- [modules/pensions/documentation/adr/0002-use-modules-folder-for-pensions-code.md](../vets-api/modules/pensions/documentation/adr/0002-use-modules-folder-for-pensions-code.md) - ADR for using modules folder structure in Pensions.
- [modules/pensions/documentation/adr/0003-stub-classes-and-proxy-calls.md](../vets-api/modules/pensions/documentation/adr/0003-stub-classes-and-proxy-calls.md) - ADR for implementing stub classes and proxy calls.
- [modules/pensions/documentation/adr/0004-saved-claims-and-sidekiq-jobs.md](../vets-api/modules/pensions/documentation/adr/0004-saved-claims-and-sidekiq-jobs.md) - ADR for saved claims and Sidekiq job integration.
- [modules/pensions/documentation/adr/0005-testing-and-factories.md](../vets-api/modules/pensions/documentation/adr/0005-testing-and-factories.md) - ADR for testing strategies and factory implementation.
- [modules/pensions/documentation/adr/0006-the-complexity-of-migrations.md](../vets-api/modules/pensions/documentation/adr/0006-the-complexity-of-migrations.md) - ADR discussing database migration complexity.
- [modules/pensions/documentation/adr/0007-pdf-filler-library.md](../vets-api/modules/pensions/documentation/adr/0007-pdf-filler-library.md) - ADR for PDF filler library implementation.
- [modules/pensions/documentation/adr/0008-update-the-kms-context.md](../vets-api/modules/pensions/documentation/adr/0008-update-the-kms-context.md) - ADR for updating KMS context configuration.
- [modules/pensions/documentation/adr/0009-vets-json-schema-versioning.md](../vets-api/modules/pensions/documentation/adr/0009-vets-json-schema-versioning.md) - ADR for vets JSON schema versioning strategy.
- [modules/pensions/documentation/adr/0010-investigate-pension-ipf-callback.md](../vets-api/modules/pensions/documentation/adr/0010-investigate-pension-ipf-callback.md) - ADR for investigating pension IPF callback functionality.
- [modules/pensions/documentation/adr/0011-db-schema-changes.md](../vets-api/modules/pensions/documentation/adr/0011-db-schema-changes.md) - ADR documenting database schema changes for Pensions.
- [modules/pensions/documentation/adr/0012-replace-pdftk-with-hexapdf.md](../vets-api/modules/pensions/documentation/adr/0012-replace-pdftk-with-hexapdf.md) - ADR for replacing pdftk with hexapdf library.

#### Burials Module ADRs
- [modules/burials/documentation/readme.md](../vets-api/modules/burials/documentation/readme.md) - Burials module documentation overview and architecture.
- [modules/burials/documentation/adr/0001-record-architecture-decisions.md](../vets-api/modules/burials/documentation/adr/0001-record-architecture-decisions.md) - ADR for recording architecture decisions in Burials module.
- [modules/burials/documentation/adr/0002-use-modules-folder-for-burials-code.md](../vets-api/modules/burials/documentation/adr/0002-use-modules-folder-for-burials-code.md) - ADR for using modules folder structure in Burials.
- [modules/burials/documentation/remediation/persisent_attachments.md](../vets-api/modules/burials/documentation/remediation/persisent_attachments.md) - Documentation for persistent attachments remediation in Burials.
- [modules/burials/lib/burials/pdf_fill/pdfs/CHANGELOG.md](../vets-api/modules/burials/lib/burials/pdf_fill/pdfs/CHANGELOG.md) - Changelog for PDF fill functionality in Burials module.

#### Dependents Benefits Module
- [modules/dependents_benefits/documentation/flows.md](../vets-api/modules/dependents_benefits/documentation/flows.md) - Documentation of data flows in the Dependents Benefits module.
- [modules/dependents_benefits/documentation/legacy_flow.md](../vets-api/modules/dependents_benefits/documentation/legacy_flow.md) - Documentation of legacy data flow patterns.
- [modules/dependents_benefits/documentation/vocabulary.md](../vets-api/modules/dependents_benefits/documentation/vocabulary.md) - Vocabulary and terminology documentation for Dependents Benefits.
- [modules/dependents_benefits/documentation/class_diagrams.md](../vets-api/modules/dependents_benefits/documentation/class_diagrams.md) - Class diagram documentation for Dependents Benefits architecture.
- [modules/dependents_benefits/documentation/adr/001_move_claim_generators.md](../vets-api/modules/dependents_benefits/documentation/adr/001_move_claim_generators.md) - ADR for moving claim generator functionality.
- [modules/dependents_benefits/documentation/adr/002_shared_claim_validation.md](../vets-api/modules/dependents_benefits/documentation/adr/002_shared_claim_validation.md) - ADR for implementing shared claim validation.
- [modules/dependents_benefits/documentation/adr/003_handle_shared_proc_id.md](../vets-api/modules/dependents_benefits/documentation/adr/003_handle_shared_proc_id.md) - ADR for handling shared procedure ID functionality.
- [modules/dependents_benefits/lib/dependents_benefits/generators/README.md](../vets-api/modules/dependents_benefits/lib/dependents_benefits/generators/README.md) - Documentation for Dependents Benefits claim generators.

#### Simple Forms API Module
- [modules/simple_forms_api/docs/form_upload_tool_README.md](../vets-api/modules/simple_forms_api/docs/form_upload_tool_README.md) - Documentation for the form upload tool in Simple Forms API.
- [modules/simple_forms_api/docs/rfcs/README.md](../vets-api/modules/simple_forms_api/docs/rfcs/README.md) - RFC documentation index for Simple Forms API.
- [modules/simple_forms_api/docs/rfcs/0001-monitoring-s3-pdf-service.md](../vets-api/modules/simple_forms_api/docs/rfcs/0001-monitoring-s3-pdf-service.md) - RFC for monitoring S3 PDF service.
- [modules/simple_forms_api/docs/rfcs/0002-async-s3-pdf-upload.md](../vets-api/modules/simple_forms_api/docs/rfcs/0002-async-s3-pdf-upload.md) - RFC for asynchronous S3 PDF upload functionality.
- [modules/simple_forms_api/docs/rfcs/0003-form-submission-purge-plan.md](../vets-api/modules/simple_forms_api/docs/rfcs/0003-form-submission-purge-plan.md) - RFC for form submission purging strategy.
- [modules/simple_forms_api/app/services/simple_forms_api/form_remediation/docs/aws_s3_bucket_setup.md](../vets-api/modules/simple_forms_api/app/services/simple_forms_api/form_remediation/docs/aws_s3_bucket_setup.md) - AWS S3 bucket setup documentation for form remediation.
- [modules/simple_forms_api/app/services/simple_forms_api/form_remediation/docs/form_remediation_archiving.md](../vets-api/modules/simple_forms_api/app/services/simple_forms_api/form_remediation/docs/form_remediation_archiving.md) - Form remediation archiving process documentation.
- [modules/simple_forms_api/app/services/simple_forms_api/form_remediation/docs/form_submission_pdf_backups.md](../vets-api/modules/simple_forms_api/app/services/simple_forms_api/form_remediation/docs/form_submission_pdf_backups.md) - Form submission PDF backup documentation.

#### Other Module Documentation
- [modules/representation_management/app/sidekiq/representation_management/README.md](../vets-api/modules/representation_management/app/sidekiq/representation_management/README.md) - Representation Management Sidekiq job documentation.
- [modules/accredited_representative_portal/docs/BENEFITS_INTAKE_CLAIMS.md](../vets-api/modules/accredited_representative_portal/docs/BENEFITS_INTAKE_CLAIMS.md) - Benefits Intake Claims documentation for Accredited Representative Portal.
- [modules/decision_reviews/lib/decision_reviews/notification_callbacks/va_notify_local_testing_readme.md](../vets-api/modules/decision_reviews/lib/decision_reviews/notification_callbacks/va_notify_local_testing_readme.md) - VA Notify local testing documentation for Decision Reviews.
- [modules/vaos/reporting/README.md](../vets-api/modules/vaos/reporting/README.md) - VAOS reporting module documentation.

#### Library-Specific Documentation
- [lib/veteran_facing_services/adr/vanotify_default_callback_concerns.md](../vets-api/lib/veteran_facing_services/adr/vanotify_default_callback_concerns.md) - ADR for VA Notify default callback concerns in Veteran Facing Services.

---

*This index was generated automatically and contains 167 markdown files from the vets-api repository.*
