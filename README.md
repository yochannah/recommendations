# Open Source Recommendations for Research Software

Research software is crucial infrastructure that underpins and enables modern scientific endeavour, yet software is not always developed following standard engineering practices that ensure quality and sustainability. This manuscript does not aim to propose or endorse software development best practices but rather to provide simple recommendations that encourage adoption of existing best practices. These recommendations are designed around Open Source values providing practical suggestions of how to make research software and its source code more accessible, discoverable, reusable and transparent. This manuscript targets developers, but more importantly, it also targets organisations, projects, journals and funders that by adopting the recommendations will contribute to increasing quality and sustainability of research software.

## Recommendations

1. Develop publicly accessible open source code from day one  
Start a project as open source from the very first day, in a publicly accessible, version controlled repository (e.g., github.com and bitbucket.org). The longer a project is run in a closed manner, the harder it is to open source it later (Fogel 2005). Opening code and exposing the software development life cycle publicly from day one:
  - Promotes trust in the software and broader project
  - Facilitates the discovery of existing software development projects
  - Provides a historical public record of contributions from the start of the project and helps to track recognition
  - Encourages contributions from the community 
  - Increases opportunities for  collaboration and reuse
  - Exposes work for community evaluation, suggestions and validation
  - Increases transparency through community scrutiny
  - Encourages developers to think about and showcase good coding practices
  - Facilitates reproducibility of scientific results generated by all prior versions of the software
  - Encourages developers to provide documentation, both detailed user manual and clear in-code comments

  Some common doubts and questions about making software Open Source are discussed in the attached appendix, “Fears of open-sourcing your software project”.
2. Make software easy to discover by providing software metadata via a popular community registry  
Facilitate the discoverability of the open source software projects by registering metadata related to the software in a popular community registry, making your source code more discoverable. Metadata might, include information like the source code location, contributors, license, references and how to cite the software. Metadata registration:

  - Increases the visibility of the project, the software, its use, its successes, its references, and its contributors
  - Provides easy access for software packagers to deploy your software, thus increasing visibility
  - Encourages software providers to think about the metadata that describes software as well as how to expose such metadata.
  - Increases the chances of collaboration, reuse, and improvement.

  Examples of community registries of software metadata are bio.tools (Ison et al. 2016),(Ison et al. 2016) biojs.io (Gómez et al. 2013)(Corpas et al. 2014) and Omic Tools (Henry et al, 2014  http://database.oxfordjournals.org/content/2014/bau069) in the life sciences and DataCite (Brase, n.d.) as a generic metadata registry not just for data but software.  
3. Adopt a license and comply with the licence of third-party dependencies
Provide instructions and guidelines for other projects and software to use, modify and redistribute the software and the source code. Adopt a suitable Open Source license, include it in a publicly accessible source code repository, and ensure the software complies with the licenses of all third party dependencies. Providing a license: 
  - Clarifies the responsibilities and rights placed on third parties wishing to use, copy, redistribute, modify and/or reuse your source code
  - Enables using the code in jurisdictions where “code with no license” means it cannot be used at all
  - Protects the software’s intellectual property
  - Provides a model for long-term sustainability by enabling legally well-founded contributions and reuse
  We advise choosing a OSI-approved Open Source License following these guidelines unless your institution or project requires a different license. For reusability reasons, authors should disclose any patents and pending patent applications known to them affecting the software.  
4. Have a clear and transparent contribution, governance and communication processes
Open sourcing your software does not mean the software has to be developed in a publicly collaborative manner. Although it is desirable, the OSS recommendations do not mandate a strategy for collaborating with the community. However projects should be clear and transparent about how to contribute to them as well as, their governance model, and their communication channels. Clarity on the project structure as well as its communication channels and ways to contribute:
  - Increase transparency on how the project and the software is being managed
  - Helps to define responsibilities and how decision are made in the software project
  - Helps the community know how to collaborate, communicate and contribute to the project

