# Program requirements for the WebMCP Polyfill project

This page documents requirements for the [WebMCP Polyfill](https://github.com/w3c-oss/webmcp-polyfill) project. This information is meant to be highly stable for the life of the Project.

**Note**: This is a pilot a W3C Open Source Program. During the pilot, program governance is managed by the W3C staff (referred to as "we" below). In the longer term, the staff expects more community-driven program governance.

## Pilot parameters

### Timeline

* The pilot is expected to start at the end of October 2026 and the first phase would last through August 2027.
  * We expect two status reports during that period: one at the end of February 2027, one at the end of the period.
* If all goes well, the project would become an official W3C OSS project in approximately August 2027.

### Success criteria at the end of the first pilot phase

#### Related to WebMCP incubation and standardization

* Incubation/Standardization of the [WebMCP](https://webmachinelearning.github.io/webmcp/) specification is still ongoing.

#### Related to the Project itself

* The Project remains healthy and aligned with the [WebMCP](https://webmachinelearning.github.io/webmcp/) specification.
* The Project experiences increased community engagement and participation.

#### Related to W3C operations and management

* The Staff has confidence that we have a good evaluation of the project cost.
* The Staff has confidence that we have a good understanding of the staff effort and administrative cost.

### Minimum resource requirements

The Project is expected to satisfy these minimum (community-provided) resource requirements.

* Two or more Owners (not compensated by W3C)
* Five hours a month (from the Project Community) for:
  * Code maintenance
  * npm package maintenance

### Signals that indicate Project health

* Diversity of resource support by having more than one organization providing resources to support the project.
* Diversity of representation by having three Owners from different organizations.
  * Those organizations do not need to be W3C Members.
* Usage of the npm package has increased (number of weekly downloads, number of projects that depend on the polyfill).

### Signals that may lead to Project being archived

#### Related to WebMCP incubation and standardization

* The [WebMCP](https://webmachinelearning.github.io/webmcp/) specification gets standardized and implemented, reducing the need for the polyfill.

#### Related to the Project itself

* There is consensus among the Owners, Supporters, and Project Community to archive the Project.
* The project deviates from the [WebMCP](https://webmachinelearning.github.io/webmcp/) specification.
* The groups that constitute the Project Community have been archived and there are no new groups to replace them.
* The Owners do not fulfill the responsibilities outlined below.
* The Owners no longer respond to input from the community (e.g., via pull requests, issues).

#### Actions to take if archiving the Project

* W3C will archive the repositories and remove permissions.
* W3C will flag the npm package as deprecated.
* W3C will update its list of active/archived Projects (cf. archived Projects.)

## Project governance

### Owners and their responsibilities

For the purposes of this pilot, the staff has the ability to change the list of Owners. The initial list of Owners and Core Committers is:

* François Beaufort (Google LLC)
* Dominic Farolino (Google LLC)
* Kasper Kulikowski (Google LLC)
* Alex Nahas (MCP-B)

**Note**: In the future, management of the list of Owners could be a role for a W3C Open Source Program steering committee or for the project itself.

The Owners are expected to maintain this foundational Project documentation:

* Statement of Purpose
  * Why the project exists
  * Who constitutes the Project Community
* Project Roadmap
  * Scope of work
  * Direction and timeline of the project (ideally for a 1-year period)
* Code contribution management
  * Technical decision-making processes
  * Role definitions

In addition, Owners must provide public reports about the health and activities of the Project whenever there are material changes to the Project Roadmap, and at least once per calendar year.

### Decisions to change Project governance documentation

Decisions regarding changes to the Project documents require consensus (as assessed by the Owners) as follows:

* Statement of Purpose - consensus of Owners, Supporters, Project Community
* Project Roadmap - consensus of Owners, Project Community
* Code contribution management - consensus of Owners

The Owners must provide notice to the groups needed for a consensus decision, and allow sufficient time for feedback on proposed changes.

Disputes regarding donations (e.g., whether a Project deviated significantly from its roadmap) will be managed between Supporters and W3C Staff.

## W3C resources

### Staff resource allocation

Minimal staff resources will be invested in the pilot. During this initial phase, W3C will monitor npm package publications to better estimate guarantees that would need to be made and the required FTE support across different functions to enable them.

### Branding

The Owners will coordinate plans for any communications about the Project involving the W3C name or logo, and W3C will endeavor to support the communications.

It is our expectation that as early as the pilot phase, the project will bear the W3C logo, and that the npm package will adopt a `@w3c/` prefix.

Language in the Project site will make clear that this is a project that is part of a pilot W3C is conducting to better support open source projects that benefit the Web.

### Systems support

The W3C staff will own and make decisions related to the publication of the npm package. Owners and W3C staff are expected to communicate and work together to help ensure the ongoing availability of the package.

W3C staff will have "Admin" access to any GitHub repositories. Owners will retain at least "Maintain" (GitHub permission) access to them.