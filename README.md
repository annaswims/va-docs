## Platform Documentation
https://depo-platform-documentation.scrollhelp.site/

[Atlas - list of products and people](https://www.va.gov/atlas/)

## Admin or Dev Links

[BIO-Aquia links](BIO-Aquia.md)

### Deploys
- [Deploy status](https://department-of-veterans-affairs.github.io/veteran-facing-services-tools/frontend-support-dashboard)
- [Deploy Schedule](https://depo-platform-documentation.scrollhelp.site/developer-docs/deployments#Deployments-Automateddeploymentschedule)
  
### Feature toggle
- http://localhost:3000/flipper/features
- https://sandbox-api.va.gov/flipper/features
- https://staging-api.va.gov/flipper/features
- https://dev-api.va.gov/flipper/features
- https://api.va.gov/flipper/features
  
### Mocked Authentication
[Mocked Authentication Docs](https://github.com/department-of-veterans-affairs/va.gov-team/blob/master/products/identity/Products/Mocked%20Authentication/readme.md )
- http://dev.va.gov/sign-in/mocked-auth
- http://localhost:3001/sign-in/mocked-auth

### API Status
- https://dev-api.va.gov/v0/status
- https://staging-api.va.gov/v0/status
- https://api.va.gov/v0/status

### API Docs 
- http://localhost:3000/v0/swagger/index.html?urls.primaryName=VA.gov%20Swagger%20Docs%20(v2)
  - http://localhost:3000/v0/swagger 
  - http://localhost:3000/v0/apidocs  
- https://dev-api.va.gov/v0/swagger/index.html?urls.primaryName=VA.gov%20Swagger%20Docs%20(v2)
  - https://dev-api.va.gov/v0/swagger 
  - https://dev-api.va.gov/v0/apidocs  
  
- https://department-of-veterans-affairs.github.io/va-digital-services-platform-docs/api-reference/#/

### Analytics Opt-out
https://www.va.gov/analytics-opt-out.html

### TestRail
https://dsvavsp.testrail.io/index.php?/auth/login/ (edited) 


## Front end links:

[VA Forms Library Overview](https://depo-platform-documentation.scrollhelp.site/developer-docs/va-forms-library-overview)

[Explore Pattern Demonstrations in Our Sample Form](https://staging.va.gov/mock-form-patterns/introduction )

[VA.gov Form Pages Complete Guide](https://github.com/department-of-veterans-affairs/vets-website/blob/main/.github/prompts/form-pages-guide.prompt.md) - Written for AI, just as good for people 😢.

[Forms Library standards](https://depo-platform-documentation.scrollhelp.site/developer-docs/va-forms-library-overview#VAFormsLibraryOverview-FormsLibrarystandards)


## Schema Links
Read all 3 before going down the wrong road:

[VA Forms Library - About schema and uiSchema](https://depo-platform-documentation.scrollhelp.site/developer-docs/va-forms-library-about-schema-and-uischema)

[using vets-json-schema](https://depo-platform-documentation.scrollhelp.site/developer-docs/va-forms-library-using-forms-in-production)

[Creating a schema](https://github.com/department-of-veterans-affairs/va.gov-team/blob/master/platform/engineering/frontend/vets-website/creating-form-schema.md#creating-a-form-schema-in-vets-json-schema)


## Design Docs
https://design.va.gov/

# Anna's docs

[Back End Overview](back_end_overview.md)

[New Form Formula](new_form_formua.md)

[Improvement Ideas](improvement_ideas.md)

[vets-website Index](vets_website_index.md) - an AI generated index of all of the markdown files in vets-website

[vets-api Index](vets_website_index.md) - an AI generated index of all of the markdown files in vets-api

## Relevant Repositories
### Documentation and tickets
- https://github.com/department-of-veterans-affairs/va.gov-team  
  _Public resources for building on and in support of VA.gov. Visit complete Knowledge Hub: depo-platform-documentation.scrollhelp.site/index.html_


### Front End
- https://github.com/department-of-veterans-affairs/vets-website  
  _Frontend for VA.gov_

- https://github.com/department-of-veterans-affairs/content-build  
  _The scripts necessary for building content for vets-website_

- https://github.com/department-of-veterans-affairs/vagov-content  
  _The VA.gov Interim CMS_ **Interim** is a lie.

### Back End
- https://github.com/department-of-veterans-affairs/vets-api  
  _API powering VA.gov_

- https://github.com/department-of-veterans-affairs/vets-api-mockdata  
  _Mock Data, private so VA security scanners stop flagging test data_

### Shared
- https://github.com/department-of-veterans-affairs/vets-json-schema  
  _JSON Schema for all VA.gov projects_


### Dependencies
These are relevant, but not touched by most devs. 
- https://github.com/department-of-veterans-affairs/veteran-facing-services-tools  
  _Packages for formation.js (design.va.gov) and the VA.gov Client Documentation Site_

- https://github.com/department-of-veterans-affairs/vets-design-system-documentation  
  _Repository for design.va.gov website_

- https://github.com/department-of-veterans-affairs/component-library  
  _This module contains reusable components for the VA.gov design system published as an NPM package for use in the vets-website frontend codebase._

- https://github.com/department-of-veterans-affairs/apivore  
  _Modified version of 1.6.2 to support rails 6_