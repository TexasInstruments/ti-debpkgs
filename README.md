# ti-debpkgs - Apt repository for Texas Instruments

## Usage 
To add this repository to your existing sources list, download and copy the ``ti-debpkgs.sources`` file to ``/etc/apt/sources.list.d/``.

Make sure to replace Suites with your host's suite.

```sh
wget https://raw.githubusercontent.com/TexasInstruments/ti-debpkgs/main/ti-debpkgs.sources
# edit the Suites in ti-debpkgs.sources if required
sudo cp ti-debpkgs.sources /etc/apt/sources.list.d/
```
