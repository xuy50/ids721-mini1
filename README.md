# ids721-mini1

## install zola in Ubuntu system

go to zola website and download a version compressed package from the github page: https://github.com/getzola/zola/releases
for me I use this version package: `zola-v0.18.0-x86_64-unknown-linux-gnu.tar.gz`

unzip: `tar -xzf zola-v0.18.0-x86_64-unknown-linux-gnu.tar.gz`
Move Zola to the bin Directory: `sudo mv zola /usr/local/bin`
if you want to get more information you can go to Zola offical web doc page: https://www.getzola.org/documentation/getting-started/installation/


## theme install
Download the themes you want to your themes directory. Then, you need to tell Zola to use it by setting the `theme` variable in the configuration file. The theme name has to be the name of the directory you cloned the theme in. For example, I cloned the theme in `themes/kita`, the theme name to use in the configuration file is kita. Also make sure to place the variable in the top level of the `.toml` hierarchy and not after a dict like `[extra]` or `[markdown]`. Some themes require additional configuration before they can work properly. Be sure to follow the instructions found on your chosen theme's documentation to properly configure the theme.


