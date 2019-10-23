# Libreoffice config extension
Example extension adding a custom config schema to LibreOffice

## Files

* `config.xcs` contains the config schema
* `config.xcu` contains the default values
* `META-INF/manifest.xml` and `description.xml` are necessary to register the extension in LibreOffice.

## Usage

* Adapt configuration to your needs
* Run `./createoxt.sh`
* Install `libreoffice-config-extension.oxt` via the LibreOffice Extension Manager
* You'll find the new config items via <i>Tools->Options->Advanced->Open Expert Configuration</i>
  * Search for 'org.libreoffice.example.settings'
* You can also access the config items via the UNO API
  * https://wiki.openoffice.org/wiki/Documentation/DevGuide/Config/Reading_Configuration_Data
  * https://wiki.openoffice.org/wiki/Documentation/DevGuide/Config/Updating_Configuration_Data
