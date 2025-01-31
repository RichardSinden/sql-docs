---
title: "Delete Method (ADO Fields Collection)"
description: "Delete Method (ADO Fields Collection)"
author: rothja
ms.author: jroth
ms.date: "01/19/2017"
ms.prod: sql
ms.technology: ado
ms.topic: reference
f1_keywords:
  - "Fields20::Delete"
  - "Fields20::raw_Delete"
helpviewer_keywords:
  - "Delete method [ADO]"
apitype: "COM"
---
# Delete Method (ADO Fields Collection)
Deletes an object from the [Fields](../../../ado/reference/ado-api/fields-collection-ado.md) collection.  
  
## Syntax  
  
```  
  
Fields.Delete Field  
```  
  
#### Parameters  
 *Field*  
 A **Variant** that designates the [Field](../../../ado/reference/ado-api/field-object.md) object to delete. This parameter can be the name of the **Field** object or the ordinal position of the **Field** object itself.  
  
## Remarks  
 Calling the **Fields.Delete** method on an open [Recordset](../../../ado/reference/ado-api/recordset-object-ado.md) causes a run-time error.  
  
## Applies To  
 [Fields Collection (ADO)](../../../ado/reference/ado-api/fields-collection-ado.md)  
  
## See Also  
 [Delete Method (ADO Parameters Collection)](../../../ado/reference/ado-api/delete-method-ado-parameters-collection.md)   
 [Delete Method (ADO Recordset)](../../../ado/reference/ado-api/delete-method-ado-recordset.md)   
 [DeleteRecord Method (ADO)](../../../ado/reference/ado-api/deleterecord-method-ado.md)
