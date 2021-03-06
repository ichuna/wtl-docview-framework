# WTL Docview Framework
Implemetation of a simple DocView framework like MFC.

![DocView Framework](/images/DocView_framework.jpg)

##Introduction
This article explains the implementation of a simple Doc View framework in a WTL (version 7.5) MDI application. The sample project included with this article is a wizard-generated MDI application enhanced with my framework classes.

I enhanced code from Gabriel Kniznik with a little bit closer to the MFC DocView approach, and there exists only one kind of document template - MDI Document template. This framework was written in a week, so I apologize for mistakes and unfinished solutions :).

In this library is also participating Rodrigo Pinho Pereira de Souza, who made great enhancements to this framework (see the History section).

###Implementation
In the demo project, you can see how to integrate the framework to your own project. You have to make changes to CMainFrame, CChildFrame, CYourView, and create a new class CYourDoc. Do not forget to change the IDR_CHILDFRAME string to the form for MFC:

```\nDocument\nDVF\n\n\nDVFSimple.Document\nDVF Document.```

Below is a simplified class diagram of the framework:

![Class Diagram](/images/fw_class_diagram_simple.JPG)

