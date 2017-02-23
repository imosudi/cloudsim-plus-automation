# CloudSimAutomation: A Human Readable Scenario Specification for Automated Creation of Simulations on CloudSim [![Build Status](https://travis-ci.org/manoelcampos/CloudSimAutomation.png?branch=master)](https://travis-ci.org/manoelcampos/CloudSimAutomation)

**CloudSim Plus Automation** is a Java command line tool based on [CloudSim Plus](http://cloudsimplus.org) and [CloudReports](https://github.com/thiagotts/CloudReports) classes that is able to read specifications of CloudSim Plus simulation scenarios from a YAML file, a very human readable data format. Simulation scenarios can be written inside a YAML file and CloudSim Plus Automation reads these simulation scenarios, creates and runs them on CloudSim Plus.  
The tool releases researchers from needing to write Java code just to run simulation scenarios. By this way, the attention can be focused on the problem to be solved, such as creation of new algorithms for load balancing, new virtual machine scheduling policies, VM placement, resource provisioning, workload prediction, server consolidation, energy efficiency, cost reduction and so on. 

The main contributions of this work are:

- to avoid programming on the creation of CloudSim Plus simulation environments;
- to reduce learning curve on creation of CloudSim Plus simulation scenarios;
- to facilitate and to automate CloudSim Plus simulation environments creation;
- to use a human readable file format to specify cloud simulation scenarios and speed up such a simulation process phase;
- to allow reuse, extension and sharing of simulations scenarios.

# How to use the tool 

You can run the tool from a terminal using the following command (check the correct version number of the jar file):

*java -jar [cloudsim-plus-automation-1.2.0-with-dependencies.jar](https://github.com/manoelcampos/CloudSimAutomation/releases/latest) PathToYamlSimulationScenarioFile*

# Published Paper

For more information, read [this paper](paper_cloudsim_automation.pdf), that was published on the [Springer Lecture Notes in Computer Science Volume 8662](http://doi.org/10.1007/978-3-319-11167-4_34). Realize that the paper is for the older version of the tool, which is compatible with CloudSim 3. See the last section for more information.

**If you are using this work for publishing a paper, please cite our paper above.**

# Notice

If you are looking for the **CloudSim Automation**, which is the version compatible with [CloudSim 3](http://github.com/Cloudslab/cloudsim), it is available at [cloudsim-version](https://github.com/manoelcampos/CloudSimAutomation/tree/cloudsim-version) branch. However, that is not an actively maintained version anymore.