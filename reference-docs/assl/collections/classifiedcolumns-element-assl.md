---
title: "ClassifiedColumns Element (ASSL) | Microsoft Docs"
ms.date: 07/25/2018
ms.prod: sql
ms.technology: analysis-services
ms.custom: assl
ms.topic: reference
ms.author: owend
ms.reviewer: owend
author: minewiskan
manager: kfile
---
# ClassifiedColumns Element (ASSL)

  Contains the collection of related columns that are classified by the [ScalarMiningStructureColumn](../data-type/scalarminingstructurecolumn-data-type-assl.md) element.  
  
## Syntax  
  
```xml  
  
<MiningStructureColumn xsi:type="ScalarMiningStructureColumn">  
   ...  
   <ClassifiedColumns>  
      <ClassifiedColumnID>...</ClassifiedColumnID>  
   </ClassifiedColumns>  
   ...  
</MiningStructureColumn>  
```  
  
## Element Characteristics  
  
|Characteristic|Description|  
|--------------------|-----------------|  
|Data type and length|None|  
|Default value|None|  
|Cardinality|0-1: Optional element that can occur once and only once.|  
  
## Element Relationships  
  
|Relationship|Element|  
|------------------|-------------|  
|Parent elements|[MiningStructureColumn](../data-type/miningstructurecolumn-data-type-assl.md) of type[ScalarMiningStructureColumn](../data-type/scalarminingstructurecolumn-data-type-assl.md)|  
|Child elements|[ClassifiedColumnID](../properties/classifiedcolumnid-element-assl.md)|  
  
## Remarks  
 The element that corresponds to the parent of **ClassifiedColumns** in the Analysis Management Objects (AMO) object model is <xref:Microsoft.AnalysisServices.ScalarMiningStructureColumn>.  