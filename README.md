# Ethos-OCR
EthosProject - OCR Telegram Messages and Pictures Store Into A Database


### Before Anything
Always remember that ```PLANNING.md``` needs to be read through and used as guidelines and guardrails for building out Ethos Modules.  Then follow the instructions in the ```README.md```.  Both of these files will reference other files and diagrams in this repository and it's important to get a sound understanding of what is being requested to be built.


### Ethos-OCR Image Processing Functionality Explained
The Ethos-OCR module should be built upon the information provided within the Markdown files in this repository.  The detailed guidelines file ```OCR-PROCESSING.md``` in this repository should be thoroughly read through first and used as planning to build out the Ethos-OCR module.


### Ethos-OCR Summary
- Ethos-OCR is a utility that will be used to add text into a database either by using the Ethos-OCR GUI interface as mentioned below, or by an Ethos-OCR Bot within a group chat channel that has been switched into LEARN mode where all text messages are sent to a Database to be referenced by other Ethos Modules.  This module is simply to create a database, and so far, two different methods of getting text and OCR'ed text into a database.

There will be other utilities, such as Ethos-Botswarm and Ethos-Honeypot, which will use this data to match posts and determine if it is spam, a scam, or a bot swarm attack.  These other Modules will be built separately and later on and this Ethos-OCR module should be created in a way that other modules will interact with, request information from, and pulling information easily from other modules.  

#### Ethos-OCR Functionality
- The first way it can be used will be through the GUI utility from EthosProject's interface.  There will be an interface where screenshots containing text can be pasted into a dialog window from your clipboard.  This same dialog window will allow for navigation to your device where you can select one, multiple, or a folder of screenshots to be sent into the Ethos-OCR module for processing.
  - The GUI interface mockup diagram, which is located in ```Ethos-OCR-Database-layout-OCR-Repocrds-Visualization```, which will be described within the ```OCR-PROCESSING.md``` file should be heavily analyzed as a model to use.  Particularly, the OCR Visualization section at the bottom of the screen as it explains what fields should be visualized and how they should behave and be filled out.
  - This GUI process by an Ethos operator will take the screenshots of telegram comments and OCR them and store that information into a database.  The database will store the channel ID, the channel name, the person's name posting the message, the body of the message, and a field for tag names (SPAM, SCAM, CRYPTO, BOTSWARM, etc).
    - This database of posts turned into text will become searchable and allow for other Ethos modules to reference the data for pattern matching and tracking purposes.
