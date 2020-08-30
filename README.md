# GSoC2020
This github page describes the work done on Eclipse APP4MC Project which is part of Eclipse Foundation Organization during the GSoC 2020.

# Proposal

This project aims at developing a tracing framework based on the BTF specification to generate trace
on Real Time Parallella Framework. The generated trace file can be viewed on external tools such as
Eclipse Trace Compass to analyse task events occurring on the processor core. It also aims at extending
the CDGen application to include the tracing functionality. The implementation is realized on Adapteva
Parallella hardware and will be integrated to the Eclipse APP4MC project.

This [link](https://summerofcode.withgoogle.com/dashboard/project/6611880795176960/details/) provides the details about the Project proposal and scope.

## Project Details

Contributor    : Anand Prakash ([@anand2901](https://twitter.com/anand2901), Gmail - anandprakaas@gmail.com, [LinkedIn](https://www.linkedin.com/in/anand-prakash-93470721/))

Project Name : BTF (Best Trace Format) generation on RTFParallella (Real Time Framework Parallella)

Organization : The Eclipse Foundation

Mentor       : Lukas Krawczyk

# Contributions

* Added BTF Trace Framework to existing RTFParallella framework.
* Feature extension of CdGen tool to support code generation of tracing framework.

## Source Code

The changes specific to this project has been made on github link as well as Eclipse APP4MC project.

### GitHub
In case of github, the source code changes has been done on the branch forked from the master.

Below are the details:
* RTFParallella - [BTF Trace Framework repository](https://github.com/anand6105/RTFParallella.git) forked from [RTFParallella repository](https://github.com/mahmood1994ha/RTFParallella.git).

* CdGen Application - [CDGen feature extension repository](https://github.com/anand6105/cdgen.git) forked from [CDGen repository](https://github.com/rprasathg/cdgen.git).


### Eclipse Repository

The Eclipse repository link which consists of the project specific code changes are as below:
* RTFParallella - [Eclipse APP4MC Example](https://git.eclipse.org/c/app4mc/org.eclipse.app4mc.examples.git/tree/RTFParallella).
* CdGen Tool - [Eclipse APP4MC Tools](https://git.eclipse.org/c/app4mc/org.eclipse.app4mc.tools.git/tree/eclipse-tools/cdgen)


### Gerrit 
The links to the project specific code changes can be found in the below Gerrit code review links:
* RTFParallella - [Gerrit Link RTFParallella](https://git.eclipse.org/r/c/app4mc/org.eclipse.app4mc.examples/+/168068)
* CdGen Tools - [Gerrit Link CdGen](https://git.eclipse.org/r/c/app4mc/org.eclipse.app4mc.tools/+/168074)


## Documentation

The documentation of the complete project can be found at [BTF Trace Framework documentation](https://btfdoc.readthedocs.io/en/latest/).
