# GitHub Guidance
This is guidance developed for how the Marine Mammal Laboratory (aka MML, formerly NMML) uses GitHub in support of open science and management of scientific code. We are using GitHub to share code and content in the spirit of collaboration, open government, open science and reproducibility. Other agencies and organizations may use GitHub and other social media differently. While this guidance is a fork from @CommerceGov, this guidance only covers the @NMML GitHub organization and accounts of @NMML team members.

Remember that your official activities online are subject to applicable Federal law, ethics regulations, and agency policies. Existing policies and guidance for accessibility, privacy, external site links, cookies, and writing style apply to social media tools as well.

##SCIENTIFIC PRODUCTS
The NOAA Scientific Integrity Policy defines a Scientific Product as "Presentation of the results of scientific activities including the analysis, synthesis, compilation, or translation of scientific information and data into formats for the use of NOAA, the Department of Commerce, or the Nation."

Activity on github related to @NMML science and research should be limited to scientific products.

##NO SENSITIVE DATA
Repositories should not include any sensitive data or information. The majority (if not all) of information and research at the Marine Mammal Laboratory is not considered sensitive and is intended for, eventual, public release. Please confirm you do not store any account passwords or user logins as part of any scripts. Instead, you should store that information outside of version controled files or as environment variables on your local system.

##What is GitHub?
GitHub is a third-party website that offers code repositories that developers can use to collaborate on software development projects in real-time. Many users also use GitHub to publish and track documents, such as style guides and policies. In addition, GitHub provides social networking features that allow developers to follow open source projects, share code, and learn how code changes are made throughout the development process. The public can submit suggested changes to a developer’s content that the developer can accept and integrate. GitHub is so named because it uses the open source version control system called Git. [Learn more about GitHub and how to use it](https://github.com/about).

##Marine Mammal Laboratory Accounts on GitHub
GitHub offers free public repositories for open source projects as well as subscription-based private repositories for closed projects. MML has created an organization account with GitHub (@NMML) with unlimited public repositories. @NMML staff interested in using GitHub to post content should consider creating a repository in the @NMML account if applicable to the project. Project documents are grouped by GitHub repositories. If your project is a @NMML-wide project, then you should create a repository on http://www.github.com/nmml. If your project is a single-user project or only involves a subset of @NMML scientists, then you can consider creating the project under the lead scientists's account. Questions can be directed to one of the @NMML GitHub administrators.

##Basics for GitHub Users
All @NMML users should 
1. Use a real picture as their GitHub profile pic.
2. Enable two-factro authentication for their Github account. 


##Who May Have Administrative and Write Access to the NMML Github Organization account? Who may be team members?
NMML civil service staff may be account owners and team leaders with administrative level rights, giving them the ability to create repositories and assign team members to their GitHub projects. Both NMML civil service staff and authorized contractors may be team members able to contribute content to existing repositories. Under no circumstances may non-Department of Commerce staff, unauthorized contractors, or members of the public become team members. NMML uses GitHub in the spirit of [Open Government](http://www.whitehouse.gov/open). The public can make [pull requests](https://help.github.com/articles/using-pull-requests/), comment, and make content suggested edits to your content. Pull requests are the heart of collaboration on GitHub. When GitHub members make a pull request, they are proposing their changes to your content and requesting that you pull in their contribution. They will not be allowed to make actual changes until you review and approve those changes.

##Getting Started
###Approval Steps
1.	Get approval from your supervisor to proceed.
2.	Login to the [DOC Social Media Application Tracking System](https://socmed.my.commerce.gov/) and apply for permission to create a Github account. You must register with your work email, which should be independent from any personal account you may have on Github. 
3.	Get approval from the information owner of the NMML software or code that you want to put on GitHub (in most cases, you are the information owner). Permission from the information owner ensures that DOC or the DOC bureau allows the information to be placed on on GitHub public repositories for internal collaboration, public comment, and public use.

#Posting NMML Content to GitHub Public Repositories
The @NMML GitHub account can be used to publish @NMML software, design patterns, style guides, documents, and code related to scientific products and research as open source, making the content available for developers to [fork](https://help.github.com/articles/fork-a-repo/) and build upon for their own projects. Or, developers can help you by commenting on your content with suggested improvements and questions. In order to follow the [Department of Commerce’s Social Media Policy](http://ocio.os.doc.gov/ITPolicyandPrograms/Policy___Standards/PROD01_009476), data and software code posted in a public repository on GitHub must be available on DOC’s public website or a DOC bureau’s public website. If you are publishing to a public repository on NMML's main GitHub account, and this will be the only source of the code, then you must download a quarterly copy of that content from the GitHub repository and publish it on your agency or bureau official website (see below for information regarding use of the AFSC GitLab server). Before posting content, an employee must ensure that any content created by a DOC contractor has been released to DOC or a DOC bureau and the contractor does not claim any rights to the content. It is your responsibility to ensure your code contains no proprietary code or information. Failure to do so could lead to legal ramifications for your project and the Department. Your project plan must include quarterly download and publication for every quarter that there are changes made to the GitHub repository. Each project published on a GitHub repository must be recorded in the [DOC Social Media Application Tracking System](https://socmed.my.commerce.gov/). 

All projects posted to a DOC or DOC bureau GitHub public repository must include a link to the location where the project code resides on the DOC or DOC bureau public website, as well as the following disclaimer in a [README file](http://www.wikihow.com/Write-a-Read-Me): 

> “The United States Department of Commerce (DOC) GitHub project code is provided on an ‘as is’ basis and the user assumes responsibility for its use. DOC has relinquished control of the information and no longer has responsibility to protect the integrity, confidentiality, or availability of the information. Any claims against the Department of Commerce stemming from the use of its GitHub project will be governed by all applicable Federal law. Any reference to specific commercial products, processes, or services by service mark, trademark, manufacturer, or otherwise, does not constitute or imply their endorsement, recommendation or favoring by the Department of Commerce. The Department of Commerce seal and logo, or the seal and logo of a DOC bureau, shall not be used in any manner to imply endorsement of any commercial product or activity by DOC or the United States Government.”

###DUAL ORIGIN PUSH REPOSITORIES

All repositories should be setup to push to both the github.com and the AFSC gitlab repository. Detailed instructions will be added here. This insures that a master copy of the repository exists on an AFSC controlled server that only NOAA users have access to.

###NOTIFY GITHUB ADMINSTRATORS
After you have published your content to a @NMML GitHub repository, you should notify one the @NMML admin users so we can “watch” your repository and be notified of updates in our dashboards.  @NMML administrators will do this by selecting the “Watch” button at the top of your repository.  All @NMML public repositories should be “watched” by @NMML GitHub administrators so that they appear on the administrators’ dashboards.  

##Licensing and Making Available to the Public
When new code is posted to a NMML GitHub public repository, they should be accompanied by the following statement, in a LICENSE file in the repository:

>“Software code created by U.S. Government employees is not subject to copyright in the United States (17 U.S.C. §105). The United States/Department of Commerce reserve all rights to seek and obtain copyright protection in countries other than the United States for Software authored in its entirety by the Department of Commerce.  To this end, the Department of Commerce hereby grants to Recipient a royalty-free, nonexclusive license to use, copy, and create derivative works of the Software outside of the United States.”

By publishing your government content to a public GitHub repository, you are making it freely available to the public for download and use. It is your responsibility to ensure your code contains no proprietary code or information. Failure to do so could lead to legal ramifications for your project and the Department.

##What Not to Post on GitHub, Publically or Privately
When considering what content to post on GitHub, no distinction should be made between the public and private GitHub repositories. The private repositories are only meant to provide a closed environment for working projects not yet ready for public use and should never contain sensitive code. All NMML projects hosted on GitHub should be suitable for eventual public access. For questions about NMML's GitHub account or this guidance document, please contact Josh London at josh.london@noaa.gov

##Follow Federal Requirements
###Section 508
Social Media tools, like other web-based applications, whether inside the DOC network or in the other areas of the Web, must make every effort to comply with Section 508 and other policies on accessibility, privacy, and record keeping. In some rare instances, it's not possible to redesign an outside system to be accessible, but it's usually possible to link back to equivalent information on a DOC website. A DOC email address must always be visible on a DOC or DOC bureau GitHub site for users who require alternative methods of accessing the information posted.

###Privacy Policy
The [Department of Commerce’s Privacy Policy](http://www.commerce.gov/privacy-policy) applies to any DOC or DOC bureau GitHub site or repository.

###Plain Language Policy
When applicable, GitHub publications made by DOC should comply with [The Plain Writing Act of
2010](http://www.commerce.gov/plain-language), which requires federal agencies to write "clear Government communication that the public can understand and use." President Obama also emphasized the importance of establishing "a system of transparency, public participation, and collaboration," in his January 21, 2009, [Memorandum on Transparency and Open Government](http://www.whitehouse.gov/the_press_office/TransparencyandOpenGovernment).

###Comment Policy
GitHub comments from and to the public will adhere to [DOC’s Comment Policy](http://www.commerce.gov/comment-policy).

##Department of Commerce GitHub Accounts
If you do not see your official DOC GitHub account listed, please contact Mike Kruger at
mkruger@doc.gov. 

[CommerceGov](www.github.com/commercegov)

[USPTO](www.github.com/uspto)

[NOAAORRERD](www.github.com/NOAAORRERD)

[NMML](www.github.com/NMML)

[InternationalTradeAdministration](https://github.com/InternationalTradeAdministration/developerportal)
