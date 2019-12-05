# cygwin-package-installer

### This project is licensed under the GNU GPLv3.
##### You can read more about the GNU GPLv3 <a href="https://www.gnu.org/licenses/gpl-3.0.en.html">here</a>.

<b>Feel Free to contribute, fork and submit pull requests.</>

This script aims to provide a simple and easy way to install packages in Cygwin within the Cygwin terminal itself.
If you want to learn more about Cygwin, please visit the Cygwin homepage <a href="https://cygwin.com/">here</a>.

Currently the script is very simple and supports only installation of packages.

## How To
You can use the following commands in the script.

<table>
  <tr>
    <td>
    <td>Option
    <td>Description
  </tr>
  <tr>
   <td>1
   <td>-h <b>OR</b> --help
   <td>Displays a help message on how to use the script.
  </tr>
  <tr>
   <td>2
   <td>-i <b>OR</b> --i <i>packages</i>
   <td>Installs the packages specified following this command. Separate the package names with a space. <p>Example: <pre><code>cygwin --install vim nano</code></pre></p><p><b>OR</b><pre><code>cygwin -i vim nano</code></pre><p>Both of these commands would install the packages vim and nano to your Cygwin environment.
  </tr>
</table>

## Installation
There is no specific way to install this script, so long as the script's directory is in the `PATH` and is executable.
You can even use something like this in the terminal with curl: <br>
`curl https://raw.githubusercontent.com/DaniAsh551/cygwin-package-installer/master/cygwin > /usr/bin/cygwin && chmod +x /usr/bin/cygwin` <br>
or with wget in the terminal: <br>
`wget https://raw.githubusercontent.com/DaniAsh551/cygwin-package-installer/master/cygwin -O /usr/bin/cygwin && chmod +x /usr/bin/cygwin`<br>
That is all.

## Dependencies
1.  <i>curl</i> <b>OR</b> <i>wget</i>
