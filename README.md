# TPM2.0-TSS

*This site contains the code for the TPM (Trusted Platform Module) 2.0 Software Stack (TSS).*

This stack consists of the following layers from top to bottom:
* _Feature API (FAPI):  specification in progress and unimplemented_
* _Enhanced System API (ESAPI):  specification in progress and unimplemented_
* System API (SAPI) 1.0 specification public, 0.97 implementation complete
* TPM Command Transmission Interface (TCTI):  Used by SAPI to communicate with next lower layer (either the TAB/RM or TPM 2.0 device driver)
* Trusted Access Broker/Resource Manager (TAB/RM):  
* TCTI:  this send TCTI layer is used to communicate with the TPM 2.0 driver.

Since the FAPI and ESAPI haven't been implemented yet, this repository only contains the SAPI and layers below it, plus a test application for excercising the SAPI.

For more details on this code and how to install and use it, the readme.pdf file is a good place to start.

For release details, review the TPM 2.0 library release notes.pdf document.

*TPM 2.0 specifications can be found at [Trusted Computing Group](http://www.trustedcomputinggroup.org/)*
