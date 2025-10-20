### MD FILE EDITOR
https://pandao.github.io/editor.md/en.html

### LINARO SOURCE
[https://releases.linaro.org/components/toolchain/binaries/7.5-2019.12/arm-linux-gnueabihf/]
gcc-linaro-7.5.0-2019.12-x86_64_arm-linux-gnueabihf.tar.xz

### Add Linaro to path
Store Linaro unzip folder at a location
Open .bashrc file add the following at the end
export PATH=$PATH/:<location of the Linarofoler/bin>
Save and exit.
Verify by opening cmd and type gcc and press tab. should see linaro gcc distributions.
