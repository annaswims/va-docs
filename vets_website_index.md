# VA.gov Repository Markdown Index

This index provides links to all markdown files in the vets-website repository with brief summaries.

## Root Level

- [README.md](../vets-website/README.md) - Main documentation for the VA.gov website frontend repository, including setup instructions, build commands, and development workflows.
- [CONTRIBUTING.md](../vets-website/CONTRIBUTING.md) - Guidelines for contributing to the vets-website repository with links to platform documentation and workflow instructions.
- [SECURITY.md](../vets-website/SECURITY.md) - Security policy directing users to report vulnerabilities through the VA's Bugcrowd responsible disclosure program.
- [babel-config-for-ref.md](../vets-website/babel-config-for-ref.md) - Reference documentation showing babel configuration settings for browser support and JavaScript transformation presets.

## GitHub Templates and Prompts

- [.github/CONTRIBUTING.md](../vets-website/.github/CONTRIBUTING.md) - GitHub-specific contribution guidelines (likely duplicate of root CONTRIBUTING.md).
- [.github/PULL_REQUEST_TEMPLATE.md](../vets-website/.github/PULL_REQUEST_TEMPLATE.md) - Standard pull request template with checklist for folder changes, TeamSites updates, and testing requirements.
- [.github/PROD_FLAG_TEMPLATE.md](../vets-website/.github/PROD_FLAG_TEMPLATE.md) - Template for production feature flag deployment requests and documentation.
- [.github/SCO_PR_TEMPLATE.md](../vets-website/.github/SCO_PR_TEMPLATE.md) - Pull request template specifically for School Certifying Official (SCO) features and changes.
- [.github/copilot-instructions.md](../vets-website/.github/copilot-instructions.md) - Development guidelines and conventions for GitHub Copilot when working with the VA.gov monorepo.
- [.github/instructions/mhv-secure-messaging.instructions.md](../vets-website/.github/instructions/mhv-secure-messaging.instructions.md) - Detailed Copilot instructions specific to the MHV Secure Messaging application with patterns, constants, and business logic.
- [.github/prompts/accessibility-review.prompt.md](../vets-website/.github/prompts/accessibility-review.prompt.md) - Accessibility review checklist following WCAG 2.2AA and Section 508 guidelines for form validation.
- [.github/prompts/form-pages-guide.prompt.md](../vets-website/.github/prompts/form-pages-guide.prompt.md) - Comprehensive guide for creating and working with VA.gov form pages, including web component patterns and examples.
- [.github/prompts/create-new-form.prompt.md](../vets-website/.github/prompts/create-new-form.prompt.md) - Instructions for creating new VA.gov forms using the Yeoman generator with proper context gathering.


## Config and Script Documentation
- [config/readme.md](../vets-website/config/readme.md) - Configuration documentation covering TypeScript, Cypress, Mocha, and Webpack configurations within the config folder.
- [config/cy-local-reports/cy-local-reports-template.md](../vets-website/config/cy-local-reports/cy-local-reports-template.md) - Template for generating Cypress test reports with statistics and detailed test results.
- [script/vale/TEST.md](../vets-website/script/vale/TEST.md) - Test file for VA.gov Vale Plain Language Linting rules with examples of contractions, tone, and formatting guidelines.
- [script/eslint-plugin-va/README.md](../vets-website/script/eslint-plugin-va/README.md) - Documentation for custom ESLint plugin specific to VA.gov development standards.
- [script/cypress-testrail-helper/README.md](../vets-website/script/cypress-testrail-helper/README.md) - Helper utilities for integrating Cypress test results with TestRail test management.
- [script/component-migration/README.md](../vets-website/script/component-migration/README.md) - Documentation for migrating components within the VA.gov codebase.
- [script/github-actions/daily-product-scan/tests/mocks/applications/app-1/README.md](../vets-website/script/github-actions/daily-product-scan/tests/mocks/applications/app-1/README.md) - Mock application documentation for testing daily product scan GitHub Actions.

## Site Content
- [src/site/README.md](../vets-website/src/site/README.md) - Documentation for the static content and pages that make up the VA.gov website structure.

## Platform Documentation

### Site-wide Features
- [src/platform/site-wide/helpers/team-sites/README.md](../vets-website/src/platform/site-wide/helpers/team-sites/README.md) - Helper utilities for managing team-specific site configurations.
- [src/platform/site-wide/announcements/README.md](../vets-website/src/platform/site-wide/announcements/README.md) - System for managing site-wide announcements and notifications.
- [src/platform/site-wide/legacy-component-js/README.md](../vets-website/src/platform/site-wide/legacy-component-js/README.md) - Documentation for legacy JavaScript component integration.
- [src/platform/site-wide/mega-menu/README.md](../vets-website/src/platform/site-wide/mega-menu/README.md) - Implementation and configuration of the site-wide mega menu navigation.

### Monitoring and Analytics
- [src/platform/monitoring/Datadog/README.md](../vets-website/src/platform/monitoring/Datadog/README.md) - Datadog integration for application monitoring and analytics.
- [src/platform/monitoring/DowntimeNotification/README.md](../vets-website/src/platform/monitoring/DowntimeNotification/README.md) - System for displaying and managing downtime notifications.

### Testing Infrastructure
- [src/platform/testing/unit/msw-adapter-migration-todo.md](../vets-website/src/platform/testing/unit/msw-adapter-migration-todo.md) - Migration tasks for updating to MSW (Mock Service Worker) adapter.
- [src/platform/testing/e2e/cypress/support/form-tester/README.md](../vets-website/src/platform/testing/e2e/cypress/support/form-tester/README.md) - Cypress form testing utilities and patterns.

### My HealtheVet Platform
- [src/platform/mhv/README.md](../vets-website/src/platform/mhv/README.md) - Platform-level My HealtheVet integration and shared functionality.
- [src/platform/mhv/api/mocks/README.md](../vets-website/src/platform/mhv/api/mocks/README.md) - Mock API responses for My HealtheVet services during development.
- [src/platform/mhv/secondary-nav/README.md](../vets-website/src/platform/mhv/secondary-nav/README.md) - Secondary navigation components for My HealtheVet applications.
- [src/platform/mhv/dod-history/README.md](../vets-website/src/platform/mhv/dod-history/README.md) - Department of Defense history integration for MHV.
- [src/platform/mhv/downtime/README.md](../vets-website/src/platform/mhv/downtime/README.md) - Downtime management specific to My HealtheVet services.
- [src/platform/mhv/self-entered/readme.md](../vets-website/src/platform/mhv/self-entered/readme.md) - Self-entered data management for My HealtheVet applications.

### Forms System
- [src/platform/forms-system/src/js/validate-config/README.md](../vets-website/src/platform/forms-system/src/js/validate-config/README.md) - Configuration validation utilities for the forms system.
- [src/platform/forms-system/src/js/components/ConfirmationView/README.md](../vets-website/src/platform/forms-system/src/js/components/ConfirmationView/README.md) - Confirmation page components for form submissions.
- [src/platform/forms-system/src/js/components/PersonalInformation/README.md](../vets-website/src/platform/forms-system/src/js/components/PersonalInformation/README.md) - Personal information collection components.
- [src/platform/forms-system/src/js/patterns/array-builder/README.md](../vets-website/src/platform/forms-system/src/js/patterns/array-builder/README.md) - Array builder pattern for dynamic form fields.
- [src/platform/forms-system/src/js/patterns/minimal-header/README.md](../vets-website/src/platform/forms-system/src/js/patterns/minimal-header/README.md) - Minimal header pattern for focused form experiences.
- [src/platform/forms-system/docs/reviewErrors.md](../vets-website/src/platform/forms-system/docs/reviewErrors.md) - Documentation for handling and displaying form review errors.

### User Profile and Services
- [src/platform/user/profile/vap-svc/README.md](../vets-website/src/platform/user/profile/vap-svc/README.md) - Veteran Address and Phone (VAP) service integration.

### PDF Services
- [src/platform/pdf/README.md](../vets-website/src/platform/pdf/README.md) - PDF generation and processing utilities.


## Unique/broadly applicable app documentation

### Proxy Rewrite
- [src/applications/proxy-rewrite/README.md](../vets-website/src/applications/proxy-rewrite/README.md) - Documentation for URL rewriting and proxy functionality.

### Mock Form Design Patterns
- [src/applications/_mock-form-ae-design-patterns/README.md](../vets-website/src/applications/_mock-form-ae-design-patterns/README.md) - Mock application demonstrating form design patterns and accessibility enhancements.


### Design System Playground
- [src/applications/ds-v3-playground/README.md](../vets-website/src/applications/ds-v3-playground/README.md) - Playground environment for testing Design System v3 components.
- 
### Application Registry
- [src/applications/registry.json.md](../vets-website/src/applications/registry.json.md) - Documentation for the application registry system.

### Simple Forms
- [src/applications/simple-forms/form-upload/README.md](../vets-website/src/applications/simple-forms/form-upload/README.md) - Documentation for the simple forms upload functionality and patterns.
- [src/applications/simple-forms/20-10207/tests/e2e/fixtures/data/backend-mapping-support/README.md](../vets-website/src/applications/simple-forms/20-10207/tests/e2e/fixtures/data/backend-mapping-support/README.md) - Testing documentation for Form 20-10207 backend mapping and data fixtures.


### Personalization Applications
- [src/applications/personalization/dashboard/README.md](../vets-website/src/applications/personalization/dashboard/README.md) - Documentation for the veteran personalization dashboard application and its features.
- [src/applications/personalization/profile/README.md](../vets-website/src/applications/personalization/profile/README.md) - Documentation for veteran profile management and personal information.
- [src/applications/personalization/profile/components/accredited-representative/README.md](../vets-website/src/applications/personalization/profile/components/accredited-representative/README.md) - Components for managing accredited representative information in profiles.
- [src/applications/personalization/review-information/README.md](../vets-website/src/applications/personalization/review-information/README.md) - Documentation for reviewing and updating personal information.

### Static Pages
- [src/applications/static-pages/README.md](../vets-website/src/applications/static-pages/README.md) - Documentation for static content pages and templates.
- [src/applications/static-pages/mhv-signin-cta/README.md](../vets-website/src/applications/static-pages/mhv-signin-cta/README.md) - My HealtheVet sign-in call-to-action component documentation.
- [src/applications/static-pages/events/helpers/event-generator.md](../vets-website/src/applications/static-pages/events/helpers/event-generator.md) - Event generation helpers for static page functionality.
- [src/applications/static-pages/test-sc-deployment.md](../vets-website/src/applications/static-pages/test-sc-deployment.md) - ServiceConnect deployment testing for static pages.
- [src/applications/static-pages/health-care-manage-benefits/README.md](../vets-website/src/applications/static-pages/health-care-manage-benefits/README.md) - Static page for managing healthcare benefits.
- [src/applications/static-pages/health-care-manage-benefits/components/README.md](../vets-website/src/applications/static-pages/health-care-manage-benefits/components/README.md) - Components for healthcare benefits management pages.
- [src/applications/static-pages/find-forms/README.md](../vets-website/src/applications/static-pages/find-forms/README.md) - Static page documentation for finding VA forms.

## Remaining Application Documentation

### Benefits Optimization Aquia Team
- [src/applications/benefits-optimization-aquia/README.md](../vets-website/src/applications/benefits-optimization-aquia/README.md) - Documentation for the Benefits Intake Optimization team's digital forms for VA benefits claims, focusing on pension, burial, and disability forms.
- [src/applications/benefits-optimization-aquia/21-4192-employment-information/README.md](../vets-website/src/applications/benefits-optimization-aquia/21-4192-employment-information/README.md) - Documentation for VA Form 21-4192 employment information collection.
- [src/applications/benefits-optimization-aquia/21-4192-employment-information/config/submit-transformer/README.md](../vets-website/src/applications/benefits-optimization-aquia/21-4192-employment-information/config/submit-transformer/README.md) - Submit transformer configuration for employment information form.
- [src/applications/benefits-optimization-aquia/21p-530a-interment-allowance/README.md](../vets-website/src/applications/benefits-optimization-aquia/21p-530a-interment-allowance/README.md) - Documentation for VA Form 21P-530A interment allowance application.
- [src/applications/benefits-optimization-aquia/21-0779-nursing-home-information/README.md](../vets-website/src/applications/benefits-optimization-aquia/21-0779-nursing-home-information/README.md) - Documentation for VA Form 21-0779 nursing home information.
- [src/applications/benefits-optimization-aquia/21-2680-house-bound-status/README.md](../vets-website/src/applications/benefits-optimization-aquia/21-2680-house-bound-status/README.md) - Documentation for VA Form 21-2680 house bound status determination.
- [src/applications/benefits-optimization-aquia/shared/README.md](../vets-website/src/applications/benefits-optimization-aquia/shared/README.md) - Shared components and utilities for Benefits Optimization Aquia forms.
- [src/applications/benefits-optimization-aquia/shared/cypress-helpers/README.md](../vets-website/src/applications/benefits-optimization-aquia/shared/cypress-helpers/README.md) - Cypress testing helpers for Benefits Optimization forms.
- [src/applications/benefits-optimization-aquia/shared/components/README.md](../vets-website/src/applications/benefits-optimization-aquia/shared/components/README.md) - Shared React components for Benefits Optimization applications.
- [src/applications/benefits-optimization-aquia/shared/schemas/README.md](../vets-website/src/applications/benefits-optimization-aquia/shared/schemas/README.md) - JSON schemas for Benefits Optimization form validation.
- [src/applications/benefits-optimization-aquia/shared/components/templates/page-template/TEST_FIXES.md](../vets-website/src/applications/benefits-optimization-aquia/shared/components/templates/page-template/TEST_FIXES.md) - Test fixes and known issues for page template components.
- [src/applications/benefits-optimization-aquia/shared/forms/README.md](../vets-website/src/applications/benefits-optimization-aquia/shared/forms/README.md) - Shared form configurations and patterns.
- [src/applications/benefits-optimization-aquia/shared/tests/README.md](../vets-website/src/applications/benefits-optimization-aquia/shared/tests/README.md) - Testing utilities and patterns for Benefits Optimization applications.



### Veterans Affairs Supply Services (VASS)
- [src/applications/vass/README.md](../vets-website/src/applications/vass/README.md) - Documentation for the Veterans Affairs Supply Services application.

### Travel Pay
- [src/applications/travel-pay/README.md](../vets-website/src/applications/travel-pay/README.md) - Documentation for the travel pay reimbursement application for veterans.


### Medical Expense Report
- [src/applications/medical-expense-report/README.md](../vets-website/src/applications/medical-expense-report/README.md) - Documentation for the medical expense reporting application.

### New 28-1900 Form
- [src/applications/new-28-1900/readme.md](../vets-website/src/applications/new-28-1900/readme.md) - Documentation for the VA Form 28-1900 (Disabled Veterans Application for Vocational Rehabilitation).

### Loan Guaranty (LGY) Certificate of Eligibility
- [src/applications/lgy/coe/README.md](../vets-website/src/applications/lgy/coe/README.md) - Documentation for the Certificate of Eligibility application for VA home loans.

### VAOS (VA Online Scheduling)
- [src/applications/vaos/README.md](../vets-website/src/applications/vaos/README.md) - Main documentation for the VA Online Scheduling application for scheduling, requesting, and viewing appointments.
- [src/applications/vaos/referral-appointments/README.md](../vets-website/src/applications/vaos/referral-appointments/README.md) - Documentation for the VAOS referral appointments feature within the VA Online Scheduling system.
- [src/applications/vaos/testing.md](../vets-website/src/applications/vaos/testing.md) - Testing configuration for VAOS application development and validation.

### Virtual Agent
- [src/applications/virtual-agent/README.md](../vets-website/src/applications/virtual-agent/README.md) - Quick guide for developing the VA Virtual Agent including test coverage and local development setup.

### Claims Status
- [src/applications/claims-status/README.md](../vets-website/src/applications/claims-status/README.md) - Documentation for the VA claims status tracking application.
- [src/applications/claims-status/test-sc-deployment.md](../vets-website/src/applications/claims-status/test-sc-deployment.md) - Testing procedures for ServiceConnect deployment of the claims status application.

### Pensions
- [src/applications/pensions/README.md](../vets-website/src/applications/pensions/README.md) - Documentation for the VA pensions application and benefits processing.
- [src/applications/pensions/PULL_REQUEST_TEMPLATE.md](../vets-website/src/applications/pensions/PULL_REQUEST_TEMPLATE.md) - Pull request template specific to pension application development.

### Caregivers
- [src/applications/caregivers/README.md](../vets-website/src/applications/caregivers/README.md) - Documentation for the VA caregivers assistance program application.

### Appeals
- [src/applications/appeals/README.md](../vets-website/src/applications/appeals/README.md) - Documentation for the VA appeals process and application workflows.
- [src/applications/appeals/onramp/constants/display-conditions/README.md](../vets-website/src/applications/appeals/onramp/constants/display-conditions/README.md) - Display condition constants for the appeals onramp process.
- [src/applications/appeals/onramp/tests/cypress/README.md](../vets-website/src/applications/appeals/onramp/tests/cypress/README.md) - Cypress testing documentation for appeals onramp functionality.

### My HealtheVet (MHV) Applications
- [src/applications/mhv/README.md](../vets-website/src/applications/mhv/README.md) - Main documentation for My HealtheVet integration and applications.
- [src/applications/mhv-medications/README.md](../vets-website/src/applications/mhv-medications/README.md) - Documentation for the MHV medications tracking and management application.
- [src/applications/mhv-medical-records/README.md](../vets-website/src/applications/mhv-medical-records/README.md) - Documentation for accessing and managing medical records through MHV.
- [src/applications/mhv-landing-page/README.md](../vets-website/src/applications/mhv-landing-page/README.md) - Documentation for the My HealtheVet landing page and navigation.
- [src/applications/mhv-supply-reordering/README.md](../vets-website/src/applications/mhv-supply-reordering/README.md) - Documentation for medical supply reordering through MHV.
- [src/applications/mhv-secure-messaging/README.md](../vets-website/src/applications/mhv-secure-messaging/README.md) - Documentation for secure messaging between veterans and healthcare providers.
- [src/applications/mhv-secure-messaging/tests/e2e/fixtures/mock-attachments/README.md](../vets-website/src/applications/mhv-secure-messaging/tests/e2e/fixtures/mock-attachments/README.md) - Mock attachment fixtures for testing secure messaging functionality.

### Coronavirus Screener
- [src/applications/coronavirus-screener/README.md](../vets-website/src/applications/coronavirus-screener/README.md) - Documentation for the COVID-19 screening application for VA facilities.

### Burials and Memorials
- [src/applications/burials-ez/README.md](../vets-website/src/applications/burials-ez/README.md) - Documentation for the burial benefits application (VA Form 21P-530EZ).

### PACT Act
- [src/applications/pact-act/constants/display-conditions/README.md](../vets-website/src/applications/pact-act/constants/display-conditions/README.md) - Display condition constants for PACT Act related functionality.
- [src/applications/pact-act/tests/cypress/README.md](../vets-website/src/applications/pact-act/tests/cypress/README.md) - Cypress testing documentation for PACT Act applications.

### Healthcare Applications
- [src/applications/ivc-champva/README.md](../vets-website/src/applications/ivc-champva/README.md) - Documentation for IVC CHAMPVA healthcare benefits application.
- [src/applications/health-care-supply-reordering/README.md](../vets-website/src/applications/health-care-supply-reordering/README.md) - Documentation for reordering healthcare supplies and equipment.
- [src/applications/hca/README.md](../vets-website/src/applications/hca/README.md) - Documentation for the Healthcare Application (VA Form 10-10EZ).

### Third Party and External Services
- [src/applications/third-party-app-directory/README.md](../vets-website/src/applications/third-party-app-directory/README.md) - Documentation for the directory of approved third-party applications.
- [src/applications/third-party-app-directory/TEST_DEPLOY.md](../vets-website/src/applications/third-party-app-directory/TEST_DEPLOY.md) - Testing and deployment procedures for third-party app directory.

### Representative Services
- [src/applications/representative-appoint/README.md](../vets-website/src/applications/representative-appoint/README.md) - Documentation for appointing VA representatives and power of attorney.
- [src/applications/representative-search/README.md](../vets-website/src/applications/representative-search/README.md) - Documentation for searching and finding VA-accredited representatives.

### Survivors Benefits
- [src/applications/survivors-benefits/README.md](../vets-website/src/applications/survivors-benefits/README.md) - Documentation for survivors and dependents benefits applications.

### Disability Benefits
- [src/applications/disability-benefits/view-payments/README.md](../vets-website/src/applications/disability-benefits/view-payments/README.md) - Documentation for viewing disability compensation payments.
- [src/applications/disability-benefits/all-claims/utils/dates/README.md](../vets-website/src/applications/disability-benefits/all-claims/utils/dates/README.md) - Date utility functions for disability claims processing.
- [src/applications/rated-disabilities/README.md](../vets-website/src/applications/rated-disabilities/README.md) - Documentation for viewing and managing rated disabilities.

### Income and Asset Statement
- [src/applications/income-and-asset-statement/README.md](../vets-website/src/applications/income-and-asset-statement/README.md) - Documentation for income and asset reporting for VA benefits.

### Dependents and Family
- [src/applications/dependents/686c-674/README.md](../vets-website/src/applications/dependents/686c-674/README.md) - Documentation for adding or removing dependents (VA Forms 686C and 674).
- [src/applications/dependents/686c-674/documentation/686c.md](../vets-website/src/applications/dependents/686c-674/documentation/686c.md) - Specific documentation for VA Form 686C (dependent claims).
- [src/applications/dependents/686c-674/documentation/674.md](../vets-website/src/applications/dependents/686c-674/documentation/674.md) - Specific documentation for VA Form 674 (school enrollment certification).
- [src/applications/dependents/686c-674/components/picklist/README.md](../vets-website/src/applications/dependents/686c-674/components/picklist/README.md) - Documentation for picklist components in dependent forms.
- [src/applications/dependents/686c-674-old/README.md](../vets-website/src/applications/dependents/686c-674-old/README.md) - Legacy version documentation for dependent forms.
- [src/applications/dependents/686c-674-old/documentation/686c.md](../vets-website/src/applications/dependents/686c-674-old/documentation/686c.md) - Legacy 686C form documentation.
- [src/applications/dependents/686c-674-old/documentation/674.md](../vets-website/src/applications/dependents/686c-674-old/documentation/674.md) - Legacy 674 form documentation.
- [src/applications/dependents/686c-674-old/config/chapters/taskWizard/wizard/wizard.md](../vets-website/src/applications/dependents/686c-674-old/config/chapters/taskWizard/wizard/wizard.md) - Legacy wizard configuration for dependent forms.

### Accreditation
- [src/applications/accreditation/21a/README.md](../vets-website/src/applications/accreditation/21a/README.md) - Documentation for VA Form 21a accreditation application.

### Check-in Services
- [src/applications/check-in/README.md](../vets-website/src/applications/check-in/README.md) - Main documentation for VA appointment check-in system.
- [src/applications/check-in/day-of/README.md](../vets-website/src/applications/check-in/day-of/README.md) - Documentation for day-of-appointment check-in functionality.
- [src/applications/check-in/travel-claim/README.md](../vets-website/src/applications/check-in/travel-claim/README.md) - Documentation for travel claim submission during check-in.
- [src/applications/check-in/pre-check-in/README.md](../vets-website/src/applications/check-in/pre-check-in/README.md) - Documentation for pre-appointment check-in procedures.
- [src/applications/check-in/locales/scripts/README.md](../vets-website/src/applications/check-in/locales/scripts/README.md) - Localization scripts and documentation for check-in applications.

### After Visit Summary
- [src/applications/avs/README.md](../vets-website/src/applications/avs/README.md) - Documentation for After Visit Summary generation and delivery.

### Vocational Rehabilitation and Employment (VR&E)
- [src/applications/vre/25-8832/readme.md](../vets-website/src/applications/vre/25-8832/readme.md) - Documentation for VA Form 25-8832 (VR&E application).
- [src/applications/vre/28-1900/README.md](../vets-website/src/applications/vre/28-1900/README.md) - Documentation for VA Form 28-1900 (VR&E orientation).

### Letters
- [src/applications/letters/README.md](../vets-website/src/applications/letters/README.md) - Documentation for downloading VA letters and benefit verification.

### Ask VA
- [src/applications/ask-va/tests/e2e/fixtures/ask_va_api/v0/contents/subtopics/__temp.md](../vets-website/src/applications/ask-va/tests/e2e/fixtures/ask_va_api/v0/contents/subtopics/__temp.md) - Temporary fixture file for Ask VA subtopics testing.


### Facility Locator
- [src/applications/facility-locator/README.md](../vets-website/src/applications/facility-locator/README.md) - Documentation for finding and locating VA facilities.


---

*This index was automatically generated on November 17, 2025. Total markdown files indexed: 134*