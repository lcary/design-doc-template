Template instructions:

1. Copy this template to a new file.
2. Replace _PROJECT_ with the system or feature name (e.g. "My Image Classification Service") throughout this document template.
3. Replace all italicized instructions with relevant text as is necessary and useful for the project design to be reviewed.
4. Delete this instruction list as well as any unused sections or instructions.
5. Share the design document with reviewers.

# _PROJECT_ Design Doc

Date: _Add the date when this document is shared with reviewers._

Author(s): _Add the primary author(s) of this document here, comma-separated._

Reviewer(s): _Add the primary reviewers(s) of this document here, comma-separated._

Issue Tracking: _Optionally add a link to a (e.g. Jira) ticket tracking the project status._

## Context

_Add one or more paragraphs describing background information for the project._
_(e.g. what historical events led to the creation of this service?)_

## Scope

_Add a sentence or two describing the scope of the project under development here._

### Goals

1. _Add a numbered list of goals that should be considered in scope for the project here._

### Non-Goals

1. _Add a numbered list of non-goals for the project here, or any tasks that should be considered out of scope._

## Application Components

_Add a sentence or two describing the components of the project which will be described in the below sections._

_A [system context diagram](https://en.wikipedia.org/wiki/System_context_diagram) may be useful to add here_
_in order to demonstrate how the project fits into an existing technology stack._

_The below sub-sections should be filled out as necessary, or deleted otherwise._

### Frontend

_If the project includes the development of a user interface, add information describing the UI here._
_This should be kept as brief as possible, a full list of React components, for example, is likely a waste of time._
_Instead, if a primary use case of the project is to produce a request form that a user must fill out and hit submit,_
_then it would be useful to mention that form, that hitting submit makes a request to the backend, and results in something rendering._
_A simple diagram of how the frontend UI interacts with a given backend API may be useful._
_Detailed wireframes for each frontend view is probably overkill._

### Backend

_If one or more backend services need to be developed for the use case, describe the frameworks used and architecture patterns._
_For each primary API endpoint, briefly describe in plain english the purpose of the endpoint, what it takes as input, and what it returns._

### Storage

_If storage backends (e.g. S3, or an existing, remote database) are used, they should be mentioned here._
_If service accounts or credentials are to be used or created in connecting to a specific backend, mention here._
_If trade-offs have been made in selecting one backend over another, make sure to document that in the "Alternatives" section._

### Configuration

_Outline configuration management for the service. (i.e. how does the service load settings? from where? is it different in dev/stg/prd?)_

### Monitoring

_Document any necessary monitoring and alerting setup for the reliable maintenance of the service._

### Integrations

_Enumerate key integrations with other services, if any._
_(e.g. does a cronjob gather data from an existing DB? does the service depend on a Kakfa topic from an upstream service?)_

## Security

_This section should contain a few sentences on the security and privacy considerations for the project._
_For example, data encryption methods should be documented here, with links to external references as necessary._

### Networking

_Document any endpoints or URLs that need to be exposed to the public, completely locked down, or something in between._
_Document any network firewall rules that need to be created, modified, removed for the new service to operate._

### Data Privacy

_Describe sensitive information stored in the application (e.g. logs on disk) or in a storage backend should be discussed,_
_as well as mechanisms used to secure the data. The level of sensitivity (PHI/PII) should be mentioned here._

### Authentication

_Describe the authentication strategy used to protect the frontend, backend, storage, etc._

### Authorization

_Describe the authorization strategy used to restrict access for certain users logged into the frontend, backend, storage, etc._

## Alternatives

_This section should contain one or more alternatives if necessary, with pros/cons lists or tables for the alternatives._

## Resources

1. _Add a numbered list of references to internal or external resources mentioned in or relevant to the design._
2. _(e.g. link to API Spec for backend service X)_
3. _(e.g. link to architecture diagram for all app components)_
4. _(e.g. link to user story documents motivating a feature)_
5. _(e.g. link to user interface wireframes)_

---

## Credits

This design document was based on [design-doc-template](https://github.com/lcary/design-doc-template),
a Markdown template for development projects inspired by
["Design Docs at Google" by `@cramforce`](https://www.industrialempathy.com/posts/design-docs-at-google/).
