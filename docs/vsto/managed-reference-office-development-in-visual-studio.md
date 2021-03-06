---
title: "Managed Reference (Office Development in Visual Studio) | Microsoft Docs"
ms.custom: ""
ms.date: "02/02/2017"
ms.reviewer: ""
ms.suite: ""
ms.technology: 
  - "office-development"
ms.tgt_pltfrm: ""
ms.topic: "article"
dev_langs: 
  - "VB"
  - "CSharp"
helpviewer_keywords: 
  - "reference [Office development in Visual Studio], 2007 Microsoft Office system"
  - "Office development in Visual Studio, reference"
ms.assetid: 1fa66da0-9d90-4524-ba4f-4da13aab73b5
caps.latest.revision: 22
author: "gewarren"
ms.author: "gewarren"
manager: ghogen
---
# Managed Reference (Office Development in Visual Studio)
  This section contains API reference documentation for namespaces and types that are used in Office projects that target the [!INCLUDE[net_v40_short](../sharepoint/includes/net-v40-short-md.md)] or the [!INCLUDE[net_v45](../vsto/includes/net-v45-md.md)]. For API reference documentation about the namespaces and types that are used in Office projects that target the .NET Framework 3.5, see the following reference section in the Visual Studio documentation: [http://go.microsoft.com/fwlink/?LinkId=160658](http://go.microsoft.com/fwlink/?LinkId=160658).  
  
> [!NOTE]  
>  Interested in developing solutions that extend the Office experience across [multiple platforms](https://dev.office.com/add-in-availability)? Check out the new [Office Add-ins model](https://dev.office.com/docs/add-ins/overview/office-add-ins). Office Add-ins have a small footprint compared to VSTO add-ins and solutions, and you can build them by using almost any web programming technology, such as HTML5, JavaScript, CSS3, and XML.  
  
## In This Section  
 <xref:Microsoft.Office.Tools>  
 Contains classes common to programming Office solutions. These include the base class for VSTO Add-ins, classes for creating custom task panes in VSTO Add-ins, classes for creating smart tags in Excel and Word solutions, and classes for creating actions panes in document-level customizations.  
  
 <xref:Microsoft.Office.Tools.Excel>  
 Contains host controls and host items that can be used in solutions for Excel.  
  
 <xref:Microsoft.Office.Tools.Excel.Controls>  
 Contains Excel controls and Windows Forms controls that can be used in solutions for Excel.  
  
 <xref:Microsoft.Office.Tools.Outlook>  
 Contains classes used by VSTO Add-ins for Outlook, including classes that are used to create custom form regions.  
  
 <xref:Microsoft.Office.Tools.Ribbon>  
 Contains classes that are used to programmatically modify Ribbon customizations created by using the Ribbon designer.  
  
 <xref:Microsoft.Office.Tools.Word>  
 Contains host controls and host items that can be used in solutions for Word.  
  
 <xref:Microsoft.Office.Tools.Word.Controls>  
 Contains Word controls and Windows Forms controls that can be used in solutions for Word.  
  
 <xref:Microsoft.VisualStudio.Tools.Applications>  
 Contains the <xref:Microsoft.VisualStudio.Tools.Applications.ServerDocument> class and a set of related cached data classes. These classes can be used to modify some aspects of document-level customizations on computers that do not have Microsoft Office installed.  
  
 <xref:Microsoft.VisualStudio.Tools.Applications.Deployment>  
 Contains the <xref:Microsoft.VisualStudio.Tools.Applications.Deployment.IAddInPostDeploymentAction> interface (which you can implement to create a *post deployment action* for an Office solution), exceptions that can be thrown when installing an Office solution, and other APIs that are part of the Visual Studio infrastructure.  
  
 <xref:Microsoft.VisualStudio.Tools.Applications.Runtime>  
 Contains most of the exceptions that can be thrown by the [!INCLUDE[vsto_runtime](../vsto/includes/vsto-runtime-md.md)], several classes that can be used to cache data in document-level customizations, and other APIs that are part of the Visual Studio infrastructure.  
  
 <xref:Microsoft.VisualStudio.Tools.Office.BuildTasks>  
 Contains MSBuild task classes that are used to build Office projects.  
  
## See Also  
 [Visual Studio Tools for Office Runtime Overview](../vsto/visual-studio-tools-for-office-runtime-overview.md)   
 [Getting Started &#40;Office Development in Visual Studio&#41;](../vsto/getting-started-office-development-in-visual-studio.md)   
 [Office Development Samples and Walkthroughs](../vsto/office-development-samples-and-walkthroughs.md)   
 [Designing and Creating Office Solutions](../vsto/designing-and-creating-office-solutions.md)  
  
  