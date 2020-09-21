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

## Scope

_Add a sentence or two describing the scope of the project under development here._

### Goals

1. _Add a numbered list of goals that should be considered in scope for the project here._

### Non-Goals

1. _Add a numbered list of non-goals for the project here, or any tasks that should be considered out of scope._

## Design

_Add a sentence or two describing the components of the project which will be described in the below sections._

_A [system context diagram](https://en.wikipedia.org/wiki/System_context_diagram) may be useful to add here_
_in order to demonstrate how the project fits into an existing technology stack._

_The below sub-sections should be filled out as necessary, or deleted otherwise._

### APIs

_Add a sentence or paragraph for each of the primary API endpoints exposed by the service, if any._
_Avoid pasting API schemas, instead use a descriptive phrase to define each endpoint if possible, e.g. "Annotations Endpoint:"._
_For each primary API endpoint, briefly describe in plain english the purpose of the endpoint, what it takes as input, and what it returns._

### Storage

_If storage backends (e.g. S3, or an existing, remote database) are used, they should be mentioned here._
_If service accounts or credentials are to be used or created in connecting to a specific backend, mention here._
_If trade-offs have been made in selecting one backend over another, make sure to document that in the "Alternatives" section._

### User Interface

_If the project includes the development of a user interface, add information describing the UI here._
_This should be kept as brief as possible, a full list of React components, for example, is likely a waste of time._
_Instead, if a primary use case of the project is to produce a request form that a user must fill out and hit submit,_
_then it would be useful to mention that form, that hitting submit makes a request to the backend, and results in something rendering._
_A simple diagram of how the frontend UI interacts with a given backend API may be useful._
_Detailed wireframes for each frontend view is probably overkill._

### Networking

_Document any endpoints or URLs that need to be exposed to the public, completely locked down, or something in between._

## Alternatives

_This section should contain one or more alternatives if necessary, with pros/cons lists for each alternative._

## Security

_This section should contain one or more paragraphs on the security and privacy considerations for the project._
_Any sensitive information stored in the application (e.g. logs on disk) or in a storage backend should be discussed,_
_as well as mechanisms used to secure the data._
_For example, data encryption methods should be documented here, with links to external references as necessary._

## Resources

1. _Add a numbered list of references to internal or external resources mentioned in the design._

## Credits

This design document was based on [design-doc-template](https://github.com/lcary/design-doc-template),
a Markdown template for development projects inspired by
["Design Docs at Google" by `@cramforce`](https://www.industrialempathy.com/posts/design-docs-at-google/).
