# <Your-Project-Title>
## <img src="../images/description.jpg" alt="Logo" width="1698">
  
<div align="justify">
  
For this category of connected devices, the feature tests were divided into four categories, covering the different stages of the interaction of a user with the device and the possible security and privacy adjustments that can be made. Thus, we focus the study on common configuration aspects, and actions that a person can perform on the devices.
- **Installation**. These tests cover both the installation of the device with the SPA itself and the registration of new accessories and third-party skills.
  - Installation process of the SPA. It was studied how the installation of the personal assistant was carried out, which additional devices and applications are necessary, and what configurations can be performed.
  - Installation of new connected devices. The installation process of accessories connected to the assistant is examined and which permissions or configurations can be set to restrict their use.
  - Installation of third-party skills. The installation process of third-party skills or developments to be invoked from the assistant was analysed if the SPA had this functionality available.
- **Interaction**. Analyses that cover the possible options that a user has for managing the interaction with the SPA, with connected devices and third-party skills.
  - Interaction with the SPA and connected devices. Checks how a user can control the interaction with the assistant and the connected accessories.
  - Interaction with third-party skills. It is analysed if there are controls that allow to define use profiles for third-party skills incorporated to the assistant.
- **Functionality**. Tests covering options to control assistant functionalities, such as payments or multimedia content playback.
  - Payments and transactions. The possibility of making payments from the assistant is studied, verifying the configurations and restrictions that a user can define.
  - Possibility of creating "safe" profiles for minors. It was checked if the assistants have options to create restricted profiles for minors in an easy manner, therefore allowing for control of multimedia content that is played by the assistant, the accessories with which it can interact, payments that can be made, etc.
- **Privacy and security**. This category includes tests that evaluate the security features of the assistant, as well as the options that a person has to control the use of his/her personal information.
  - Control of answers containing personal information. Assistants can include users' personal information as responses to some of the requests. This test evaluates if a user can control the sharing options of his personal information.
  - Authentication methods. The authentication methods available in the assistants are analysed, as well as their real effectiveness.
  - Non-human voice filtering. It is checked whether the assistant is susceptible to be activated by voices of artificial origin, such as a recorded message or a Text To Speech system.
  - Interaction with the conversation history. These tests cover the options provided to the user to control and display information about the conversation history with the assistant.

</div>
  
## <img src="../images/testwithus.jpg" alt="Logo" width="1698">
  
<div align="justify">
 
- Switching on the SPA and the mobile device.
- Connecting the SPA to the Internet via Wi-Fi.
- Registration/login to the application that manages the SPA. Personal account required (Google, Amazon, iCloud, Facebook, etc.).
- SPA recognition, synchronisation and configuration process from the mobile application.
- Tests of interaction with the SPA:
  - Basic tests: voice authentication, recognition of non-human voices, exchange of personal data, storage of conversation histories, control of responses with personal content, etc.
  - Tests with devices connected to the SPA.
  - Testing with the SPA and third party skills/competences, if any.
- Testing of voice payments and transactions.

 </div>
  
## <img src="../images/results.jpg" alt="Logo" width="1698">
    
<div align="justify">
 
The analysis has shown that protection of minor users through simple and quick settings is practically non-existent in the tested conditions (device versions, app versions and mobile device to which they have been paired). In all cases it is necessary to go through the full set of device settings, even needing to switch between different configuration menus, to disable all features that may be unsafe for an unsupervised minor user. It was found that in many cases, restricted device settings affect all users equally, leaving features unusable for all members of the household, which is impractical and does not encourage users to establish these restrictions. 
 
With respect to SPA authentication systems, it has been found that they can be compromised by the lack of protection measures against commands originated by an artificial source, that make the devices vulnerable to impersonation attacks.

Finally, a wireless speaker has been tested by means of a DoS attack supported by a portable device (Raspberry Pi 4 model B). This test shows that, in addition to being susceptible to more complex attacks such as KNOB or BIAS, it is possible to disconnect said device from its master. In this way, by creating false device identities, it would be possible to connect the master to a fake device, which will be used as an access vector for the attacker.

</div>
