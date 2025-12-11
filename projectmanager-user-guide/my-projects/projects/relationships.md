# Project Relationships
Associate related entities to the project and define how they are related. It is possible to relate Changes, Releases, Service Requests, Services and Configuration Items if the Service Manager Application is also installed on your instance. It is possible to relate Suppliers if the Supplier Manager Application is also installed on your instance. Project Stakeholders will only be able to search for and relate Request, Assets and Services they have the rights to view from Service Manager Project Stakeholders will only be able to search for and relate Suppliers they have the rights to view from Supplier Manager 

## Define a New Relationship

Select the **+** Icon to define a new relationship.

* Select the entity type and search for the entity/s you wish to relate to the project.

* Define how the entity is related to the project by selecting a **Relationship** type against each entity you are adding

Selected Project Relationships will be displayed in the list, but at this stage have not been added to the project. 

Repeat the above process to add more entities from any of the entity types and define their **Relationships** to the project.

When finished and happy with the entities in the **Selected Project Relationships** list select the **Add** button to add them to the Project

## Related Entities List

View all related entities to the project, including the name of the entity, the entity type, which application the entity belongs too, it's relationship type and who last modified the project relationship for the entity.

* Search for specific entities using the **Search** field
* Filter the displayed related entities by **Entity** and or **Relationship Type**
  
  
## Managing Related Entities

Edit or delete a entity from the Project by selecting the entity name, from the list.

* Change the relationship type and select **Update** to apply the change
* Remove the entity and it's relationship to the project using the **Trash Can** icon

## Raise Projects From Service Manager Business Processes

Use the Hornbill Integration Bridge (iBridge) in the business processes supporting requests in Service Manager to automate the creation of new Projects in Project Manager. Once a new Project has been created in the Service Manager business process linked to a request, the request the process is running against will automatically be related to the new project in the Project Relationships list. Read more about the Project Manager iBridge options from the link in the related articles section above.

## Administration

All entities added to or removed from the project, or any changes to their relationship type are automatically audited and available to view in the audit trail tab on the project. 

Manage the available **Relationship Types** in the admin console and simple lists

* Project Relationship Type Assets
* Project Relationship Type Requests
* Project Relationship Type Services
  