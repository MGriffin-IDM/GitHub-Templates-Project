# MSE Test Project
# github-repository-templates-project

Project tracking repository. Primarily for issues and a GitHub project to manage them. _Maybe_ some sample files and code.

# **Landscape**

**Key Problem(s):**  
  * Individuals across IDM create GitHub repositories frequently, and interface is overly complex, and time-consuming. 

**Why Fixing this is important to IDM:**  
  * People want a better user experience and we have the technology and experience to provide this.

**The Opportunity:** 
  * Leverage technology to provide users a streamlined, easy-to-use interface for creating repositories.

********************************************************************************************************************************
# **Scope**
* **In:** Prototype the 3 most commonly types of repo used at IDM (python, R, Website.)
* **In:** Must allow users to make public
* **In:** Must include clearly defined maintenance costs and long-term ownership.

|Milestone|Deliverable(s)|Owner|Target Date|Questions & Comments|
|---|---|---|---|---|
|Complete Project Proposal|Project Plan|CL + CC
|Landscape Analysis|User Survey <br> List of Requirements| | |CL: Research partner test cases?|
|Propose Solution|Workflow & Template Proposal
|Create Prototypes|Workflow(s)<br>Template(s)|
|Complete Prototype Testing|Testing completed| | |CL: Rolling existing work into the templates is fundamentally different from starting from scratch with a template|
|Solution Roll-out|Communication plan<br>Communications completed| | | |Teams, All-hands, reviews, etc.|
|Retrospective|

# **Risks** 
|Risk|Severity|Liklihood|Mitigation|Comments|
|---|---|---|---|---|
|Limited bandwidth, especially for managers, as we move into E++ model|

# **Target Finish** 
 * tbd

# **Resources**

* Sponsor(s): Charles, Research?
* Oversight Team:  Christopher L, Clinton, Jen S? Research? 
* Delivery Team: Engineers?  Peter?



********************************************************************************************************

# **User Landscape Analysis** (in development)

Types of Projects to Support:

* Python - eventually a package
* Python - targeted scripts for an investigation, not a package
  * differentiate between command line scripts and notebook based?
* R - eventually a package
* R - targeted scripts for an investigation, not a package
* website – templates for website exist but we are in transition.  Discuss new tools to unify behind on web.
* research publication templates?
* tool specific templates(emodpy project)?
* other?
* suggestion: include Codespace configuration with each template
  * how far should we take this, Josh Herbeck just asked for help with a project with a mixture of Python and R
  * how far should we take this, I have recently been looking at a project using Rust + Python
* suggestion: include GitHub actions for running linter(s) on [ commit | PR | release | other? ] (TBD)
* suggestion: include GitHub actions for running tests (and build documentation?)
  * optionally include GitHub actions for promoting packages (Python and R) to a staging server (production server?)

********************************************************************************************************
# **Requirements** (in development)
|User/Group|Requirements|Details|
|---|---|---|
|All|Simple|# steps?| 
|All|Quick|Duration?|
|?|Ability to go public|When does this step need to happen?<br>Default setting or optional?|

********************************************************************************************************
**Questions/Comments to Discuss & Resolve**
1. Christian Wiswell - Ensuring that system accounts (for example, bamboouser-IDM) are included with read permissions to all of these would be really nice.  _Related: I'm still a little salty that we call it "bamboo user," so this might be a good time for renaming that account to something like "IDM automation" or something like that._



