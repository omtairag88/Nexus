# Tosca Guidelines

This page contains instructions on how to create robust automation scripts, execute them effectively, and analyze the results. You'll also learn how to maintain and update your automation assets to keep pace with the evolving software landscape.

 **[Best practices for test automation](./tosca-best-practices.md).**

## Naming Conventions

### Modules

The following convention is recommended by Tricentis:

- Folder name
    - named according to transaction(s) + business description
    - E.g.: ME21N | Purchase Order
- Subfolder name
    - named according to containing parts
- Module subname
    - Modules should be logically named for the screen each represents, or the control group on a screen if the control group appears in more than one (1) screen instance.  Where practical, modules will be grouped in folders for ease of reference. This is critical as the volume of test assets, especially modules grow, and as the team of Tosca test engineers expands.
    - E.g.: Everything within the TAB "Org. Data"
- ModuleAttribute name
    - business name of the control to be steered

<center>
![example of module structure](./images/module-structure.png)

--

![naming convention - modules](./images/naming-convention-modules.png)
</center>

### Test Scenarios

Test scenarios encapsulate a functional workflow with a known outcome that is validated. A test scenario name should be a summary of its intention, i.e., summary of the actions performed by its components to steer the AUT to desired outcome.

![naming convention - test scenarios](./images/naming-convention-test-scenarios.png)

## Folder structure of Project workspace in Tosca 

### Project Structure

![folder structure - project structure](./images/folder-structure-project-structure.png)

### Requirement Structure

The requirement structure should be replicated from the qtest BPML hierarchy.

![folder structure - Requirement Structure](./images/folder-structure-Requirement-Structure.png)

### Module Structure

Standard Modules for SAP GUI and Fiori applications.

![Folder structure - module structure](./images/folder-structure-module-structure.png)

Standard Modules under Sap folder can be used for automation of SAP GUI application. Eg: SAP Menu, SAP Logon etc.

![folder structure - sap folder](./images/folder-structure-sap-folder.png)

In Tosca commander 16.0 onwards standard modules also have fiori modules which can be used for fiori application automation. Eg: SAP Tile and SAP WaitForBusyIndicator.

![folder structure - fiori](./images/folder-structure-fiori.png)

### Test Case Structure

![test case structure 1](./images/test-case-structure1.png)

![test case structure 2](./images/test-case-structure2.png)

![test case structure 3](./images/test-case-structure3.png)

### Execution List Structure

![execution list structure](./images/execution-list-structure.png)