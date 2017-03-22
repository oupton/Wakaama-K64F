##### Wakaaama-K64F

This is an implementation of the Wakaama client for the NXP FRDM-K64F running mbed. This library should be compatible with any mbed device by replacing these platform-specific libraries:

    - EthernetInterface
    - mbed-rtos
    - mbed

To compile for the K64F, import this project into the [mbed Compiler](https://developer.mbed.org/compiler "mbed Compiler") as a project for the FRDM-K64F. Then, add the following macros under the 'Compile' menu:

    - LWM2M_EMBEDDED_MODE
    - LWM2M_CLIENT_MODE

This project contains a simple main that will register the device over CoAP with an LWM2M server.

Original credit to the Eclipse Foundation and Julien Vermillard (http://github.com/jvermillard) for this project.
