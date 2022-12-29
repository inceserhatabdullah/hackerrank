# hackerrank
This project about all my certificates and badges from HackerRank.

```mermaid
classDiagram

  DataSchemaWithRelations ..> ProjectWithRelations
  DataSchemaWithRelations ..> DataSchemaFieldWithRelations
  DataSchemaWithRelations ..> UIDataStoreWithRelations
  DataSchemaWithRelations ..> UIDataEventWithRelations
  DataSchemaWithRelations ..> DataSchemaEnumDataWithRelations
  ProjectWithRelations ..> TenantWithRelations
  ProjectWithRelations ..> ProjectThemeWithRelations
  ProjectWithRelations ..> PersonWithRelations
  ProjectWithRelations ..> EnvironmentVariableWithRelations
  ProjectWithRelations ..> ProjectSettingWithRelations
  ProjectWithRelations ..> MessageTemplateWithRelations
  ProjectWithRelations ..> ProjectFileWithRelations
  ProjectWithRelations ..> ProjectFolderWithRelations
  ProjectWithRelations ..> ProjectRoleWithRelations
  ProjectWithRelations ..> ProjectVersionWithRelations
  ProjectWithRelations ..> MetadataWithRelations
  ProjectWithRelations ..> ProjectModelWithRelations
  ProjectWithRelations ..> RappiderFunctionWithRelations
  ProjectWithRelations ..> WorkflowWithRelations
  ProjectWithRelations ..> WorkflowStepFunctionWithRelations
  ProjectWithRelations ..> WorkflowEventWithRelations
  ProjectWithRelations ..> ProjectPackageWithRelations
  ProjectWithRelations ..> ModuleWithRelations
  ProjectWithRelations ..> ProjectRequirementWithRelations
  ComponentDefinitionWithRelations ..> ComponentInputDefinitionWithRelations
  ComponentDefinitionWithRelations ..> ComponentOutputDefinitionWithRelations
  ComponentDefinitionWithRelations ..> ComponentSampleWithRelations
  ComponentDefinitionWithRelations ..> CategoryWithRelations
  ComponentDefinitionWithRelations ..> DataSchemaWithRelations
  ComponentDefinitionWithRelations ..> ProjectWithRelations
  CategoryWithRelations ..> MetadataWithRelations
  CategoryWithRelations ..> ComponentDefinitionWithRelations
  PersonWithRelations ..> UserWithRelations
  PersonWithRelations ..> ProjectWithRelations
  PersonWithRelations ..> MetadataWithRelations
  PersonWithRelations ..> TenantWithRelations
  PersonWithRelations ..> ProjectRoleWithRelations
  PersonWithRelations ..> RoleWithRelations
  CommentWithRelations ..> PersonWithRelations
  ComponentConditionWithRelations ..> ComponentWithRelations
  ComponentConditionWithRelations ..> UIDataStoreWithRelations
  ComponentDataSubscriptionWithRelations ..> ComponentWithRelations
  ComponentDataSubscriptionWithRelations ..> UIDataStoreWithRelations
  ComponentDataSubscriptionWithRelations ..> DataSchemaTreeFieldWithRelations
  ComponentDataSubscriptionWithRelations ..> ComponentInputDefinitionWithRelations
  ComponentDataSubscriptionWithRelations ..> DataTransformationWithRelations
  ComponentDefinitionSubCategoryWithRelations ..> CategoryWithRelations
  ComponentDefinitionSubCategoryWithRelations ..> ComponentDefinitionWithRelations
  ComponentInputDefinitionBulkCreate ..> unknown
  BulkUpdateResultDTO ..> unknown
  BulkUpdateResultDTO ..> ErrorDTO
  ComponentInputDefinitionWithRelations ..> ComponentDefinitionWithRelations
  ComponentInputDefinitionWithRelations ..> ComponentDataSubscriptionWithRelations
  ComponentInputDefinitionWithRelations ..> DataSchemaWithRelations
  ComponentInputDefinitionWithRelations ..> DataSchemaFieldWithRelations
  ComponentOutputDefinitionWithRelations ..> ComponentDefinitionWithRelations
  ComponentOutputDefinitionWithRelations ..> DataSchemaWithRelations
  ComponentOutputEventWithRelations ..> ComponentWithRelations
  ComponentOutputEventWithRelations ..> ComponentOutputDefinitionWithRelations
  ComponentOutputEventWithRelations ..> UIDataEventWithRelations
  ComponentOutputEventWithRelations ..> DataTransformationWithRelations
  ComponentSampleWithRelations ..> ComponentDefinitionWithRelations
  ConditionWithRelations ..> UIDataEventWithRelations
  ConditionWithRelations ..> UIWorkflowStepFunctionWithRelations
  UIDataEventWithRelations ..> DataSchemaWithRelations
  UIDataEventWithRelations ..> UIDataStoreWithRelations
  UIDataEventWithRelations ..> UIDataUpdateFunctionWithRelations
  UIDataEventWithRelations ..> UIWorkflowStepFunctionWithRelations
  UIDataEventWithRelations ..> ConditionWithRelations
  ConditionPublishedEventWithRelations ..> ConditionWithRelations
  ConditionPublishedEventWithRelations ..> UIDataEventWithRelations
  ContainerTemplateWithRelations ..> ProjectWithRelations
  DataMappingCreateDTO ..> unknown
  DataMappingCreateDTO ..> RappiderCustomFunction
  DataMappingWithRelations ..> ProjectWithRelations
  DataMappingWithRelations ..> RappiderFunctionWithRelations
  DataMappingWithRelations ..> UIDataUpdateFunctionWithRelations
  DataMappingWithRelations ..> DataSchemaTreeFieldWithRelations
  DataMappingWithRelations ..> RappiderCustomFunctionWithRelations
  DataMappingUpdate ..> RappiderCustomFunction
  DataSchemaEnumData ..> unknown
  NewDataSchemaEnumData ..> unknown
  DataSchemaEnumDataWithRelations ..> unknown
  DataSchemaEnumDataWithRelations ..> DataSchemaWithRelations
  DataSchemaEnumDataPartial ..> unknown
  NewDataSchemaField ..> unknown
  DataSchemaFieldBulkUpdate ..> unknown
  DataSchemaFieldBulkCreate ..> DataSchemaField
  DataSchemaFieldWithRelations ..> DataSchemaWithRelations
  DataSchemaTreeFieldNodeWithRelations ..> DataSchemaTreeFieldWithRelations
  DataSchemaTreeFieldNodeWithRelations ..> DataSchemaFieldWithRelations
  DataSchemaTreeFieldWithRelations ..> DataMappingWithRelations
  DataSchemaTreeFieldWithRelations ..> DataSchemaTreeFieldNodeWithRelations
  DataTransformationItemWithRelations ..> DataTransformationWithRelations
  DataTransformationWithRelations ..> DataTransformationItemWithRelations
  DependentComponentDefinitionWithRelations ..> ComponentDefinitionWithRelations
  EnvironmentVariableWithRelations ..> ProjectWithRelations
  KeyValueWithRelations ..> ProjectWithRelations
  MessageTemplateDataFieldWithRelations ..> MessageTemplateWithRelations
  MessageTemplateWithRelations ..> ProjectWithRelations
  MessageTemplateWithRelations ..> MessageTemplateDataFieldWithRelations
  ModuleWithRelations ..> ProjectWithRelations
  ModuleWithRelations ..> PageWithRelations
  OpenAPIWithRelations ..> OpenAPIEndpointWithRelations
  OpenAPIWithRelations ..> ProjectWithRelations
  OpenAPIEndpointWithRelations ..> OpenAPIEndpointResponse
  OpenAPIEndpointWithRelations ..> OpenAPIWithRelations
  PageWithRelations ..> ComponentWithRelations
  PageWithRelations ..> MetadataWithRelations
  PageWithRelations ..> ModuleWithRelations
  PageCommentWithRelations ..> CommentWithRelations
  PageCommentWithRelations ..> PageWithRelations
  ComponentWithRelations ..> ComponentDefinitionWithRelations
  ComponentWithRelations ..> PageWithRelations
  ComponentWithRelations ..> ComponentDefinitionStyleSheetWithRelations
  ComponentWithRelations ..> ComponentDataSubscriptionWithRelations
  ComponentWithRelations ..> ComponentOutputEventWithRelations
  ComponentWithRelations ..> ComponentConditionWithRelations
  PageComponentWithRelations ..> ComponentWithRelations
  PageComponentWithRelations ..> PageWithRelations
  PersonProjectRoleBulkProcesses ..> PersonProjectRole
  ProjectRoleWithRelations ..> PersonWithRelations
  ProjectRoleWithRelations ..> ProjectWithRelations
  ProjectRoleWithRelations ..> PageWithRelations
  PersonProjectRoleWithRelations ..> ProjectRoleWithRelations
  PersonProjectRoleWithRelations ..> PersonWithRelations
  PersonProjectWithRelations ..> ProjectWithRelations
  PersonProjectWithRelations ..> PersonWithRelations
  PhoneNumberWithRelations ..> PersonWithRelations
  ProjectDocumentWithRelations ..> ProjectWithRelations
  ProjectVersionWithRelations ..> ProjectWithRelations
  ProjectExportWithRelations ..> ProjectWithRelations
  ProjectExportWithRelations ..> ProjectVersionWithRelations
  ProjectFileWithRelations ..> ProjectWithRelations
  ProjectFileWithRelations ..> ProjectFolderWithRelations
  ProjectFileWithRelations ..> MetadataWithRelations
  ProjectExternalScriptWithRelations ..> ProjectWithRelations
  ProjectExternalScriptWithRelations ..> ProjectFileWithRelations
  ProjectFolderWithRelations ..> ProjectFileWithRelations
  ProjectFolderWithRelations ..> ProjectWithRelations
  ProjectFolderWithRelations ..> MetadataWithRelations
  ProjectModelEndpointWithRelations ..> ProjectModelEndpointQueryParamWithRelations
  ProjectModelEndpointWithRelations ..> ProjectModelWithRelations
  ProjectModelEndpointWithRelations ..> ProjectModelEndpointParamWithRelations
  ProjectModelEndpointWithRelations ..> DataSchemaWithRelations
  ProjectModelEndpointWithRelations ..> ProjectModelRelationWithRelations
  ProjectModelEndpointWithRelations ..> ProjectModelFieldWithRelations
  ProjectModelFieldWithRelations ..> ProjectModelWithRelations
  ProjectModelFieldWithRelations ..> DataSchemaFieldWithRelations
  ProjectModelEndpointExcludeFieldWithRelations ..> ProjectModelEndpointWithRelations
  ProjectModelEndpointExcludeFieldWithRelations ..> ProjectModelFieldWithRelations
  ProjectModelEndpointParamWithRelations ..> DataSchemaWithRelations
  ProjectModelEndpointParamWithRelations ..> ProjectModelEndpointWithRelations
  ProjectModelEndpointQueryParamWithRelations ..> DataSchemaWithRelations
  ProjectModelEndpointQueryParamWithRelations ..> ProjectModelEndpointWithRelations
  NewProjectModelEndpoint ..> unknown
  ProjectModelEndpointCreateDTO ..> unknown
  ProjectModelEndpointUpdateDTO ..> unknown
  ProjectModelRelationWithRelations ..> ProjectModelWithRelations
  ProjectModelRelationWithRelations ..> DataSchemaFieldWithRelations
  ProjectModelRelationWithRelations ..> ProjectModelEndpointWithRelations
  ProjectModelWithRelations ..> ProjectWithRelations
  ProjectModelWithRelations ..> ProjectModelFieldWithRelations
  ProjectModelWithRelations ..> ProjectModelRelationWithRelations
  ProjectModelWithRelations ..> ProjectModelEndpointWithRelations
  ProjectModelWithRelations ..> DataSchemaWithRelations
  ProjectModelWithRelations ..> UIDataStoreWithRelations
  ProjectPackageWithRelations ..> ProjectWithRelations
  ProjectRequirementWithRelations ..> ProjectWithRelations
  ProjectRoleAllowedPageWithRelations ..> ProjectRoleWithRelations
  ProjectRoleAllowedPageWithRelations ..> PageWithRelations
  ProjectRoleRestrictedPageWithRelations ..> ProjectRoleWithRelations
  ProjectRoleRestrictedPageWithRelations ..> PageWithRelations
  ProjectSettingWithRelations ..> ProjectWithRelations
  ProjectThemeWithRelations ..> ProjectWithRelations
  ProjectUpdateDTO ..> MetadataCrudDTO
  ProjectUpdateDTOPartial ..> MetadataCrudDTO
  RappiderCustomFunctionParameterWithRelations ..> DataSchemaWithRelations
  RappiderCustomFunctionParameterWithRelations ..> RappiderCustomFunctionWithRelations
  RappiderCustomFunctionWithRelations ..> ProjectWithRelations
  RappiderCustomFunctionWithRelations ..> RappiderCustomFunctionParameterWithRelations
  RoleMappingWithRelations ..> ProjectWithRelations
  RoleMappingWithRelations ..> RoleWithRelations
  TenantWithRelations ..> MetadataWithRelations
  TenantWithRelations ..> PersonWithRelations
  UIDataStoreWithRelations ..> DataSchemaWithRelations
  UIDataStoreWithRelations ..> ProjectWithRelations
  UIDataStoreWithRelations ..> ProjectModelWithRelations
  UIDataStoreWithRelations ..> UIDataEventWithRelations
  UIDataStoreWithRelations ..> UIWorkflowStepFunctionWithRelations
  UIDataUpdateFunctionWithRelations ..> DataMappingWithRelations
  UIDataUpdateFunctionWithRelations ..> UIDataEventWithRelations
  UIWorkflowStepFunctionWithRelations ..> UIDataStoreWithRelations
  UIWorkflowStepFunctionWithRelations ..> WorkflowWithRelations
  UIWorkflowStepFunctionWithRelations ..> ProjectModelEndpointWithRelations
  UIWorkflowStepFunctionWithRelations ..> DataTransformationWithRelations
  UIWorkflowStepFunctionWithRelations ..> UIWorkflowStepFunctionUIDataStoreSubscriptionWithRelations
  UIWorkflowStepFunctionWithRelations ..> UIDataEventWithRelations
  UIWorkflowStepFunctionWithRelations ..> ConditionWithRelations
  UIWorkflowStepFunctionSubscribedEventWithRelations ..> UIWorkflowStepFunctionWithRelations
  UIWorkflowStepFunctionSubscribedEventWithRelations ..> UIDataEventWithRelations
  UIWorkflowStepFunctionUIDataStoreSubscriptionWithRelations ..> UIWorkflowStepFunctionWithRelations
  UIWorkflowStepFunctionUIDataStoreSubscriptionWithRelations ..> UIDataStoreWithRelations
  UIWorkflowStepFunctionUIDataStoreSubscriptionWithRelations ..> DataSchemaTreeFieldWithRelations
  UIWorkflowStepFunctionCreateDTO ..> unknown
  NewUIWorkflowStepFunction ..> unknown
  UIWorkflowStepFunctionUpdate ..> unknown
  UserWithRelations ..> PersonWithRelations
  UserWithRelations ..> RoleMappingWithRelations
  UserInvitationWithRelations ..> UserWithRelations
  WorkflowEventWithRelations ..> ProjectWithRelations
  WorkflowStepFunctionWithRelations ..> WorkflowWithRelations
  WorkflowStepFunctionWithRelations ..> ProjectModelEndpointWithRelations
  WorkflowStepFunctionWithRelations ..> DataTransformationWithRelations
  WorkflowStepFunctionWithRelations ..> ProjectWithRelations
  WorkflowStepFunctionWithRelations ..> WorkflowEventWithRelations
  WorkflowStepFunctionPublishedEventOnFailureWithRelations ..> WorkflowStepFunctionWithRelations
  WorkflowStepFunctionPublishedEventOnFailureWithRelations ..> WorkflowEventWithRelations
  WorkflowStepFunctionPublishedEventOnSuccessWithRelations ..> WorkflowStepFunctionWithRelations
  WorkflowStepFunctionPublishedEventOnSuccessWithRelations ..> WorkflowEventWithRelations
  WorkflowStepFunctionSubscribedEventWithRelations ..> WorkflowStepFunctionWithRelations
  WorkflowStepFunctionSubscribedEventWithRelations ..> WorkflowEventWithRelations
  WorkflowWithRelations ..> WorkflowStepFunctionWithRelations
  WorkflowWithRelations ..> ProjectWithRelations
  class Category{
    +date: createdDate
    +string: createdBy
    +string: createdById
    +date: updatedDate
    +string: updatedBy
    +string: updatedById
    +bool: isUpdatable
    +bool: isDeleted
    +date: deletedDate
    +string: deletedBy
    +string: deletedById
    +bool: isDeletable
    +string: id
    +string: title
    +string: name
    +bool: online
    +string: slug
    +number: order
    +string: type
    +string: description
    +string: parentCategoryId
  }
  class NewCategory{
    +date: createdDate
    +string: createdBy
    +string: createdById
    +date: updatedDate
    +string: updatedBy
    +string: updatedById
    +bool: isUpdatable
    +bool: isDeleted
    +date: deletedDate
    +string: deletedBy
    +string: deletedById
    +bool: isDeletable
    +string: title
    +string: name
    +bool: online
    +string: slug
    +number: order
    +string: type
    +string: description
    +string: parentCategoryId
  }
  class DataSchemaWithRelations{
    +date: createdDate
    +string: createdBy
    +string: createdById
    +date: updatedDate
    +string: updatedBy
    +string: updatedById
    +bool: isUpdatable
    +bool: isDeleted
    +date: deletedDate
    +string: deletedBy
    +string: deletedById
    +bool: isDeletable
    +string: id
    +string: name
    +bool: isPrimitive
    +string: category
    +string: type
    +string: description
    +string: defaultUIDataSelector
    +string: projectId
    +string: uiDataStoreId
    +string: uiDataEventId
    +ProjectWithRelations: project;
    +DataSchemaFieldWithRelations[]: fields;
    +UIDataStoreWithRelations: uiDataStore;
    +UIDataEventWithRelations: uiDataEvent;
    +DataSchemaEnumDataWithRelations: enumData;
  }
  class ProjectWithRelations{
    +date: createdDate
    +string: createdBy
    +string: createdById
    +date: updatedDate
    +string: updatedBy
    +string: updatedById
    +bool: isUpdatable
    +bool: isDeleted
    +date: deletedDate
    +string: deletedBy
    +string: deletedById
    +bool: isDeletable
    +string: id
    +string: name
    +string: key
    +string: cssStyle
    +string: tenantId
    +string: activeProjectThemeId
    +TenantWithRelations: tenant;
    +ProjectThemeWithRelations: activeTheme;
    +ProjectThemeWithRelations[]: themes;
    +PersonWithRelations[]: members;
    +PersonWithRelations[]: people;
    +EnvironmentVariableWithRelations[]: environmentVariables;
    +ProjectSettingWithRelations[]: projectSettings;
    +MessageTemplateWithRelations[]: messageTemplates;
    +ProjectFileWithRelations[]: files;
    +ProjectFolderWithRelations[]: folders;
    +ProjectRoleWithRelations[]: roles;
    +ProjectVersionWithRelations[]: versions;
    +MetadataWithRelations[]: metadata;
    +ProjectModelWithRelations[]: models;
    +RappiderFunctionWithRelations[]: functions;
    +WorkflowWithRelations[]: workflows;
    +WorkflowStepFunctionWithRelations[]: stepFunctions;
    +WorkflowEventWithRelations[]: workflowEvents;
    +ProjectPackageWithRelations[]: packages;
    +ModuleWithRelations[]: modules;
    +ProjectRequirementWithRelations[]: projectRequirements;
  }
  class ComponentDefinitionWithRelations{
    +date: createdDate
    +string: createdBy
    +string: createdById
    +date: updatedDate
    +string: updatedBy
    +string: updatedById
    +bool: isUpdatable
    +bool: isDeleted
    +date: deletedDate
    +string: deletedBy
    +string: deletedById
    +bool: isDeletable
    +string: id
    +string: className
    +string: selector
    +string: moduleName
    +string[]: tags
    +string: title
    +string: description
    +string[]: supportedFrameworks
    +bool: noInputsSupported
    +object: defaultInputs
    +string: explanationImgUrl
    +string[]: previewImgUrls
    +bool: displayInCategoryShowcase
    +bool: isSystemGenerated
    +object: contentTreeItem
    +bool: isDeprecated
    +date: deprecatedDate
    +string: deprecatedBy
    +string: deprecatedById
    +string: categoryId
    +string: inputsTypeId
    +string: projectId
    +ComponentInputDefinitionWithRelations[]: inputDefinitions;
    +ComponentOutputDefinitionWithRelations[]: outputDefinitions;
    +ComponentSampleWithRelations[]: samples;
    +CategoryWithRelations: mainCategory;
    +CategoryWithRelations[]: subCategories;
    +ComponentDefinitionWithRelations[]: dependentComponentDefinitions;
    +DataSchemaWithRelations: inputsType;
    +ProjectWithRelations: project;
  }
  class CategoryWithRelations{
    +date: createdDate
    +string: createdBy
    +string: createdById
    +date: updatedDate
    +string: updatedBy
    +string: updatedById
    +bool: isUpdatable
    +bool: isDeleted
    +date: deletedDate
    +string: deletedBy
    +string: deletedById
    +bool: isDeletable
    +string: id
    +string: title
    +string: name
    +bool: online
    +string: slug
    +number: order
    +string: type
    +string: description
    +string: parentCategoryId
    +CategoryWithRelations: parentCategory;
    +CategoryWithRelations[]: categories;
    +MetadataWithRelations[]: metadata;
    +ComponentDefinitionWithRelations[]: components;
  }
  class CategoryPartial{
    +date: createdDate
    +string: createdBy
    +string: createdById
    +date: updatedDate
    +string: updatedBy
    +string: updatedById
    +bool: isUpdatable
    +bool: isDeleted
    +date: deletedDate
    +string: deletedBy
    +string: deletedById
    +bool: isDeletable
    +string: id
    +string: title
    +string: name
    +bool: online
    +string: slug
    +number: order
    +string: type
    +string: description
    +string: parentCategoryId
  }
  class Comment{
    +date: createdDate
    +string: createdBy
    +string: createdById
    +date: updatedDate
    +string: updatedBy
    +string: updatedById
    +bool: isUpdatable
    +bool: isDeleted
    +date: deletedDate
    +string: deletedBy
    +string: deletedById
    +bool: isDeletable
    +string: id
    +string: content
    +string: status
    +string: parentCommentId
    +string: assignedToPersonId
  }
  class NewComment{
    +date: createdDate
    +string: createdBy
    +string: createdById
    +date: updatedDate
    +string: updatedBy
    +string: updatedById
    +bool: isUpdatable
    +bool: isDeleted
    +date: deletedDate
    +string: deletedBy
    +string: deletedById
    +bool: isDeletable
    +string: content
    +string: status
    +string: parentCommentId
    +string: assignedToPersonId
  }
  class PersonWithRelations{
    +date: createdDate
    +string: createdBy
    +string: createdById
    +date: updatedDate
    +string: updatedBy
    +string: updatedById
    +bool: isUpdatable
    +bool: isDeleted
    +date: deletedDate
    +string: deletedBy
    +string: deletedById
    +bool: isDeletable
    +string: id
    +string: firstName
    +string: middleName
    +string: lastName
    +string: email
    +bool: isVerified
    +string: birthDate
    +string: gender
    +string: timeZone
    +bool: isDefault
    +string: language
    +string: phoneNumber
    +string: userId
    +string: tenantId
    +UserWithRelations: user;
    +ProjectWithRelations[]: projects;
    +MetadataWithRelations[]: metadata;
    +TenantWithRelations: tenant;
    +ProjectRoleWithRelations[]: roles;
    +RoleWithRelations[]: authorities;
  }
  class CommentWithRelations{
    +date: createdDate
    +string: createdBy
    +string: createdById
    +date: updatedDate
    +string: updatedBy
    +string: updatedById
    +bool: isUpdatable
    +bool: isDeleted
    +date: deletedDate
    +string: deletedBy
    +string: deletedById
    +bool: isDeletable
    +string: id
    +string: content
    +string: status
    +string: parentCommentId
    +string: assignedToPersonId
    +CommentWithRelations: parentComment;
    +PersonWithRelations: assignedTo;
  }
  class CommentPartial{
    +date: createdDate
    +string: createdBy
    +string: createdById
    +date: updatedDate
    +string: updatedBy
    +string: updatedById
    +bool: isUpdatable
    +bool: isDeleted
    +date: deletedDate
    +string: deletedBy
    +string: deletedById
    +bool: isDeletable
    +string: id
    +string: content
    +string: status
    +string: parentCommentId
    +string: assignedToPersonId
  }
  class ComponentCondition{
    +date: createdDate
    +string: createdBy
    +string: createdById
    +date: updatedDate
    +string: updatedBy
    +string: updatedById
    +bool: isUpdatable
    +bool: isDeleted
    +date: deletedDate
    +string: deletedBy
    +string: deletedById
    +bool: isDeletable
    +string: id
    +string: componentId
    +string: uiDataStoreId
  }
  class NewComponentCondition{
    +date: createdDate
    +string: createdBy
    +string: createdById
    +date: updatedDate
    +string: updatedBy
    +string: updatedById
    +bool: isUpdatable
    +bool: isDeleted
    +date: deletedDate
    +string: deletedBy
    +string: deletedById
    +bool: isDeletable
    +string: componentId
    +string: uiDataStoreId
  }
  class ComponentConditionWithRelations{
    +date: createdDate
    +string: createdBy
    +string: createdById
    +date: updatedDate
    +string: updatedBy
    +string: updatedById
    +bool: isUpdatable
    +bool: isDeleted
    +date: deletedDate
    +string: deletedBy
    +string: deletedById
    +bool: isDeletable
    +string: id
    +string: componentId
    +string: uiDataStoreId
    +ComponentWithRelations: component;
    +UIDataStoreWithRelations: uiDataStore;
  }
  class ComponentConditionPartial{
    +date: createdDate
    +string: createdBy
    +string: createdById
    +date: updatedDate
    +string: updatedBy
    +string: updatedById
    +bool: isUpdatable
    +bool: isDeleted
    +date: deletedDate
    +string: deletedBy
    +string: deletedById
    +bool: isDeletable
    +string: id
    +string: componentId
    +string: uiDataStoreId
  }
  class CreateComponentDataSubscriptionByDataSchemaFieldIdsDTO{
    +string[]: dataSchemaFieldIds
    +string: componentId
    +string: uiDataStoreId
    +string: componentInputDefinitionId
  }
  class NewComponentDataSubscription{
    +string[]: dataSchemaFieldIds
    +string: componentId
    +string: uiDataStoreId
    +string: componentInputDefinitionId
  }
  class ComponentDataSubscription{
    +date: createdDate
    +string: createdBy
    +string: createdById
    +date: updatedDate
    +string: updatedBy
    +string: updatedById
    +bool: isUpdatable
    +bool: isDeleted
    +date: deletedDate
    +string: deletedBy
    +string: deletedById
    +bool: isDeletable
    +string: id
    +string: componentId
    +string: uiDataStoreId
    +string: dataSchemaTreeFieldId
    +string: componentInputDefinitionId
    +string: dataTransformationId
  }
  class ComponentDataSubscriptionWithRelations{
    +date: createdDate
    +string: createdBy
    +string: createdById
    +date: updatedDate
    +string: updatedBy
    +string: updatedById
    +bool: isUpdatable
    +bool: isDeleted
    +date: deletedDate
    +string: deletedBy
    +string: deletedById
    +bool: isDeletable
    +string: id
    +string: componentId
    +string: uiDataStoreId
    +string: dataSchemaTreeFieldId
    +string: componentInputDefinitionId
    +string: dataTransformationId
    +ComponentWithRelations: component;
    +UIDataStoreWithRelations: uiDataStore;
    +DataSchemaTreeFieldWithRelations: dataSchemaTreeField;
    +ComponentInputDefinitionWithRelations: inputDefinition;
    +DataTransformationWithRelations: dataTransformation;
  }
  class ComponentDataSubscriptionPartial{
    +date: createdDate
    +string: createdBy
    +string: createdById
    +date: updatedDate
    +string: updatedBy
    +string: updatedById
    +bool: isUpdatable
    +bool: isDeleted
    +date: deletedDate
    +string: deletedBy
    +string: deletedById
    +bool: isDeletable
    +string: id
    +string: componentId
    +string: uiDataStoreId
    +string: dataSchemaTreeFieldId
    +string: componentInputDefinitionId
    +string: dataTransformationId
  }
  class ComponentDefinitionStyleSheet{
    +date: createdDate
    +string: createdBy
    +string: createdById
    +date: updatedDate
    +string: updatedBy
    +string: updatedById
    +bool: isUpdatable
    +bool: isDeleted
    +date: deletedDate
    +string: deletedBy
    +string: deletedById
    +bool: isDeletable
    +string: id
    +string: key
    +string: default
    +string: framework
    +string: description
    +string: componentId
  }
  class NewComponentDefinitionStyleSheet{
    +date: createdDate
    +string: createdBy
    +string: createdById
    +date: updatedDate
    +string: updatedBy
    +string: updatedById
    +bool: isUpdatable
    +bool: isDeleted
    +date: deletedDate
    +string: deletedBy
    +string: deletedById
    +bool: isDeletable
    +string: key
    +string: default
    +string: framework
    +string: description
    +string: componentId
  }
  class ComponentDefinitionStyleSheetWithRelations{
    +date: createdDate
    +string: createdBy
    +string: createdById
    +date: updatedDate
    +string: updatedBy
    +string: updatedById
    +bool: isUpdatable
    +bool: isDeleted
    +date: deletedDate
    +string: deletedBy
    +string: deletedById
    +bool: isDeletable
    +string: id
    +string: key
    +string: default
    +string: framework
    +string: description
    +string: componentId
  }
  class ComponentDefinitionStyleSheetPartial{
    +date: createdDate
    +string: createdBy
    +string: createdById
    +date: updatedDate
    +string: updatedBy
    +string: updatedById
    +bool: isUpdatable
    +bool: isDeleted
    +date: deletedDate
    +string: deletedBy
    +string: deletedById
    +bool: isDeletable
    +string: id
    +string: key
    +string: default
    +string: framework
    +string: description
    +string: componentId
  }
  class ComponentDefinitionSubCategory{
    +date: createdDate
    +string: createdBy
    +string: createdById
    +date: updatedDate
    +string: updatedBy
    +string: updatedById
    +bool: isUpdatable
    +bool: isDeleted
    +date: deletedDate
    +string: deletedBy
    +string: deletedById
    +bool: isDeletable
    +string: id
    +string: categoryId
    +string: componentDefinitionId
  }
  class NewComponentDefinitionSubCategory{
    +date: createdDate
    +string: createdBy
    +string: createdById
    +date: updatedDate
    +string: updatedBy
    +string: updatedById
    +bool: isUpdatable
    +bool: isDeleted
    +date: deletedDate
    +string: deletedBy
    +string: deletedById
    +bool: isDeletable
    +string: categoryId
    +string: componentDefinitionId
  }
  class ComponentDefinitionSubCategoryWithRelations{
    +date: createdDate
    +string: createdBy
    +string: createdById
    +date: updatedDate
    +string: updatedBy
    +string: updatedById
    +bool: isUpdatable
    +bool: isDeleted
    +date: deletedDate
    +string: deletedBy
    +string: deletedById
    +bool: isDeletable
    +string: id
    +string: categoryId
    +string: componentDefinitionId
    +CategoryWithRelations: category;
    +ComponentDefinitionWithRelations: component;
  }
  class ComponentDefinitionSubCategoryPartial{
    +date: createdDate
    +string: createdBy
    +string: createdById
    +date: updatedDate
    +string: updatedBy
    +string: updatedById
    +bool: isUpdatable
    +bool: isDeleted
    +date: deletedDate
    +string: deletedBy
    +string: deletedById
    +bool: isDeletable
    +string: id
    +string: categoryId
    +string: componentDefinitionId
  }
  class DataSchemaField{
    +date: createdDate
    +string: createdBy
    +string: createdById
    +date: updatedDate
    +string: updatedBy
    +string: updatedById
    +bool: isUpdatable
    +bool: isDeleted
    +date: deletedDate
    +string: deletedBy
    +string: deletedById
    +bool: isDeletable
    +string: id
    +string: name
    +bool: isArray
    +number: index
    +string: uiDataSelector
    +object: uiDataSelectorSettings
    +bool: isNavigationalProperty
    +string: parentDataSchemaId
    +string: typeId
  }
  class ComponentDefinition{
    +date: createdDate
    +string: createdBy
    +string: createdById
    +date: updatedDate
    +string: updatedBy
    +string: updatedById
    +bool: isUpdatable
    +bool: isDeleted
    +date: deletedDate
    +string: deletedBy
    +string: deletedById
    +bool: isDeletable
    +string: id
    +string: className
    +string: selector
    +string: moduleName
    +string[]: tags
    +string: title
    +string: description
    +string[]: supportedFrameworks
    +bool: noInputsSupported
    +object: defaultInputs
    +string: explanationImgUrl
    +string[]: previewImgUrls
    +bool: displayInCategoryShowcase
    +bool: isSystemGenerated
    +object: contentTreeItem
    +bool: isDeprecated
    +date: deprecatedDate
    +string: deprecatedBy
    +string: deprecatedById
    +string: categoryId
    +string: inputsTypeId
    +string: projectId
  }
  class NewComponentDefinition{
    +date: createdDate
    +string: createdBy
    +string: createdById
    +date: updatedDate
    +string: updatedBy
    +string: updatedById
    +bool: isUpdatable
    +bool: isDeleted
    +date: deletedDate
    +string: deletedBy
    +string: deletedById
    +bool: isDeletable
    +string: className
    +string: selector
    +string: moduleName
    +string[]: tags
    +string: title
    +string: description
    +string[]: supportedFrameworks
    +bool: noInputsSupported
    +object: defaultInputs
    +string: explanationImgUrl
    +string[]: previewImgUrls
    +bool: displayInCategoryShowcase
    +bool: isSystemGenerated
    +object: contentTreeItem
    +bool: isDeprecated
    +date: deprecatedDate
    +string: deprecatedBy
    +string: deprecatedById
    +string: categoryId
    +string: inputsTypeId
    +string: projectId
    +string[]: subCategoryIds
  }
  class ComponentDefinitionCreateDTO{
    +date: createdDate
    +string: createdBy
    +string: createdById
    +date: updatedDate
    +string: updatedBy
    +string: updatedById
    +bool: isUpdatable
    +bool: isDeleted
    +date: deletedDate
    +string: deletedBy
    +string: deletedById
    +bool: isDeletable
    +string: id
    +string: className
    +string: selector
    +string: moduleName
    +string[]: tags
    +string: title
    +string: description
    +string[]: supportedFrameworks
    +bool: noInputsSupported
    +object: defaultInputs
    +string: explanationImgUrl
    +string[]: previewImgUrls
    +bool: displayInCategoryShowcase
    +bool: isSystemGenerated
    +object: contentTreeItem
    +bool: isDeprecated
    +date: deprecatedDate
    +string: deprecatedBy
    +string: deprecatedById
    +string: categoryId
    +string: inputsTypeId
    +string: projectId
    +string[]: subCategoryIds
  }
  class ComponentDefinitionUpdateDTO{
    +string[]: subCategoryIds
    +string: categoryId
    +string: className
    +string: selector
    +string: moduleName
    +string[]: tags
    +string: title
    +string: description
    +string[]: supportedFrameworks
    +bool: noInputsSupported
    +object: defaultInputs
    +string: explanationImgUrl
    +string[]: previewImgUrls
    +bool: displayInCategoryShowcase
    +object: contentTreeItem
    +string: projectId
  }
  class CreateComponentDefinitionFromContainerTreeItemDto{
    +object: contentTreeItem
    +string: componentDefinitionName
    +string: pageId
    +string: categoryId
    +string[]: subCategoryIds
    +string: description
    +string[]: tags
    +bool: isPublic
  }
  class ComponentInputDefinition{
    +date: createdDate
    +string: createdBy
    +string: createdById
    +date: updatedDate
    +string: updatedBy
    +string: updatedById
    +bool: isUpdatable
    +bool: isDeleted
    +date: deletedDate
    +string: deletedBy
    +string: deletedById
    +bool: isDeletable
    +string: id
    +string: description
    +string: category
    +string: title
    +string[]: supportedFrameworks
    +string: fieldName
    +string: uiDataSelector
    +number: index
    +bool: isArray
    +string: componentDefinitionId
    +string: typeId
    +string: fieldId
  }
  class ComponentInputDefinitionBulkCreate{
    +string: componentDefinitionId
    +unknown[]: inputDefinitions;
  }
  class ErrorDTO{
  }
  class BulkUpdateResultDTO{
    +unknown[]: updated;
    +ErrorDTO[]: notUpdated;
  }
  class ApiResultDTO{
    +bool: success
    +object: error
  }
  class NewComponentInputDefinition{
    +date: createdDate
    +string: createdBy
    +string: createdById
    +date: updatedDate
    +string: updatedBy
    +string: updatedById
    +bool: isUpdatable
    +bool: isDeleted
    +date: deletedDate
    +string: deletedBy
    +string: deletedById
    +bool: isDeletable
    +string: description
    +string: category
    +string: title
    +string[]: supportedFrameworks
    +string: fieldName
    +string: uiDataSelector
    +number: index
    +bool: isArray
    +string: componentDefinitionId
    +string: typeId
    +string: fieldId
  }
  class ComponentInputDefinitionWithRelations{
    +date: createdDate
    +string: createdBy
    +string: createdById
    +date: updatedDate
    +string: updatedBy
    +string: updatedById
    +bool: isUpdatable
    +bool: isDeleted
    +date: deletedDate
    +string: deletedBy
    +string: deletedById
    +bool: isDeletable
    +string: id
    +string: description
    +string: category
    +string: title
    +string[]: supportedFrameworks
    +string: fieldName
    +string: uiDataSelector
    +number: index
    +bool: isArray
    +string: componentDefinitionId
    +string: typeId
    +string: fieldId
    +ComponentDefinitionWithRelations: componentDefinition;
    +ComponentDataSubscriptionWithRelations: dataSubscription;
    +DataSchemaWithRelations: type;
    +DataSchemaFieldWithRelations: field;
  }
  class ComponentInputDefinitionPartial{
    +date: createdDate
    +string: createdBy
    +string: createdById
    +date: updatedDate
    +string: updatedBy
    +string: updatedById
    +bool: isUpdatable
    +bool: isDeleted
    +date: deletedDate
    +string: deletedBy
    +string: deletedById
    +bool: isDeletable
    +string: id
    +string: description
    +string: category
    +string: title
    +string[]: supportedFrameworks
    +string: fieldName
    +string: uiDataSelector
    +number: index
    +bool: isArray
    +string: componentDefinitionId
    +string: typeId
    +string: fieldId
  }
  class ComponentOutputDefinition{
    +date: createdDate
    +string: createdBy
    +string: createdById
    +date: updatedDate
    +string: updatedBy
    +string: updatedById
    +bool: isUpdatable
    +bool: isDeleted
    +date: deletedDate
    +string: deletedBy
    +string: deletedById
    +bool: isDeletable
    +string: id
    +string: title
    +string: fieldName
    +string: description
    +number: index
    +string: componentDefinitionId
    +string: typeId
  }
  class NewComponentOutputDefinition{
    +date: createdDate
    +string: createdBy
    +string: createdById
    +date: updatedDate
    +string: updatedBy
    +string: updatedById
    +bool: isUpdatable
    +bool: isDeleted
    +date: deletedDate
    +string: deletedBy
    +string: deletedById
    +bool: isDeletable
    +string: title
    +string: fieldName
    +string: description
    +number: index
    +string: componentDefinitionId
    +string: typeId
  }
  class ComponentOutputDefinitionWithRelations{
    +date: createdDate
    +string: createdBy
    +string: createdById
    +date: updatedDate
    +string: updatedBy
    +string: updatedById
    +bool: isUpdatable
    +bool: isDeleted
    +date: deletedDate
    +string: deletedBy
    +string: deletedById
    +bool: isDeletable
    +string: id
    +string: title
    +string: fieldName
    +string: description
    +number: index
    +string: componentDefinitionId
    +string: typeId
    +ComponentDefinitionWithRelations: componentDefinition;
    +DataSchemaWithRelations: type;
  }
  class ComponentOutputDefinitionPartial{
    +date: createdDate
    +string: createdBy
    +string: createdById
    +date: updatedDate
    +string: updatedBy
    +string: updatedById
    +bool: isUpdatable
    +bool: isDeleted
    +date: deletedDate
    +string: deletedBy
    +string: deletedById
    +bool: isDeletable
    +string: id
    +string: title
    +string: fieldName
    +string: description
    +number: index
    +string: componentDefinitionId
    +string: typeId
  }
  class ComponentOutputEvent{
    +date: createdDate
    +string: createdBy
    +string: createdById
    +date: updatedDate
    +string: updatedBy
    +string: updatedById
    +bool: isUpdatable
    +bool: isDeleted
    +date: deletedDate
    +string: deletedBy
    +string: deletedById
    +bool: isDeletable
    +string: id
    +string: componentId
    +string: componentOutputDefinitionId
    +string: uiDataEventId
    +string: dataTransformationId
  }
```
This file was generated by the [openapi-mermaid](https://www.npmjs.com/package/openapi-mermaid) tool.
