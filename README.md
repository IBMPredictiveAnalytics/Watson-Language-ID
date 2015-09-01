# Watson Language ID

This node allows you to use the Watson Language Translation service on the Bluemix platform from within SPSS Modeler.   This extension identifies the language of the input text and provides a two letter language ID for the source language.  The output for this node is a new data table that contains a new column with the language identification of the input text.    

![Dialog](https://raw.githubusercontent.com/IBMPredictiveAnalytics/Watson-Language-ID/master/Screenshot/Illustration1.png)
![Output](https://raw.githubusercontent.com/IBMPredictiveAnalytics/Watson-Language-ID/master/Screenshot/Illustration2.png)
![Stream](https://raw.githubusercontent.com/IBMPredictiveAnalytics/Watson-Language-ID/master/Screenshot/Illustration3.png)

---
Requirements
----
- IBM SPSS Modeler v16 or later
- ‘R Essentials for SPSS Modeler’ plugin: [Download here][7]
 -  R 2.15.x or R 3.1
- A Bluemix account with Watson Language Translation Service activated


---
Installation instructions
----
1. Download the extension: [Download][3] 
2. Close IBM SPSS Modeler. Save the .cfe file in the CDB directory, located by default on Windows in "C:\ProgramData\IBM\SPSS\Modeler\16\CDB" or under your IBM SPSS Modeler installation directory.
3. Restart IBM SPSS Modeler, the node will now appear in the Model palette.

---
R Packages used
----
The R packages will be installed the first time the node is used as long as an Internet connection is available.
- [httr][4]
- [XML][9]
 
---
Documentation and samples
----
- Find a PDF with the documentation of this extension in the [Documentation][5] directory
- There is a sample available in the [example][6] directory


---
License
----

[Apache 2.0][1]


Contributors
----

  - Armand Ruiz ([armand_ruiz](https://twitter.com/armand_ruiz))
  - Greg Filla ([gdfilla](https://twitter.com/gdfilla))


[1]: http://www.apache.org/licenses/LICENSE-2.0.html
[2]:https://www.ibm.com/smarterplanet/us/en/ibmwatson/developercloud/doc/personality-insights/overview.shtml
[3]: https://github.com/IBMPredictiveAnalytics/Watson-Language-ID/blob/master/Source%20code/WatsonLanguageID.cfe
[4]:https://cran.r-project.org/web/packages/httr/
[5]:https://github.com/IBMPredictiveAnalytics/Watson-Language-ID/tree/master/Documentation
[6]:https://github.com/IBMPredictiveAnalytics/Watson-Language-ID/tree/master/Example
[7]:https://developer.ibm.com/predictiveanalytics/downloads/#tab2
[8]: https://developer.ibm.com/predictiveanalytics/downloads/
[9]: https://cran.r-project.org/web/packages/XML/