# New Repository Process

The SimPEG ecosystem is a set of repositories that are each in a GitHub repository with a development team 
that follows the SimPEG governance, licensing, and contribution model. Supported and maintained subprojects are hosted 
under the [SimPEG](http://github.com/simpeg) GitHub organization. 

## Criteria for subprojects
   
The following criteria will be used in evaluating subprojects for incorporation into the SimPEG organization. 
These apply to any Subproject, regardless of who is developing the Subproject. Subprojects should:

- Have an active developer community that offers a sustainable model for future development.
- Have an active user community.
- Use solid software engineering with documentation and tests hosted with appropriate technologies (Read The Docs and Travis are examples of technologies that can be used). See the [contributor guide](repo_docs/CONTRIBUTING.md)
- Demonstrate continued growth and development.
- Integrate well with other SimPEG subprojects.
- Be developed according to the SimPEG governance and contribution model that is documented here.
- Have a well-defined scope.
- Be packaged using appropriate technologies such as pip, conda, docker, etc.
- As a general guideline, we support improving existing Subprojects over incorporating competing Subprojects.

The most important question in evaluating Subprojects for incorporation as official Subprojects is this: is there broad agreement in the community and Steering Council that we are going to develop and maintain the Subproject in an official capacity?

## Creating a subproject or incorporating a subproject

If a suggestion to create a project is clearly in-scope, the process is minimal and informal: Steering Council members should be informed and come to concensus about the subproject's creation and notify the [SimPEG mailing list](https://groups.google.com/forum/#!forum/simpeg) of its creation. 
Within the [repo_docs](/repo_docs/) directory of this repository, there are several documents that can be used for licensing, code of conduct, etc
in setting up the repository. 

To suggest an exsisting project for incorporation into the SimPEG ecosystem, contact the steering committee to discuss the scope, development and maintenance of the subproject. 
Once it is decided that the subproject be adopted into the SimPEG ecosystem, the following steps will be taken: 

1. The repository will be transfered over to one of the main SimPEG GitHub organizations.
2. A GitHub team will be created for the Subproject, with the Subproject team having read/write permissions on the Subproject repository.
3. The team will send an email to the main [SimPEG mailing list](https://groups.google.com/forum/#!forum/simpeg) with an announcement about the new Subproject.
4. The standard [SimPEG License](projectlicense.md) file that is maintained in this governance repository will be added to the repository.
5. Copyright notices in individual files should be updated to the standard form described in our [SimPEG License](projectlicense.md).
