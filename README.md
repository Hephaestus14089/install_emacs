## Install Emacs
_On Debian based systems._
<br/><br/>
A simple shell script which contains commands to install GNU Emacs in debian.
<br/>
But there are some steps to be followed before running this script.
<br/><br/>
_Checking out the official documentation is highly recommended before proceeding with this short-cut._

## Steps :-
* Fetch the source code (the how of it is mentioned in the official docs)
```
git clone -b master git://git.sv.gnu.org/emacs.git
```
* If you have clone the git repository, checkout to the desired function (or stay unstable, your wish)<br/>Example:-
```
git checkout emacs-28.2
```
* If needed, edit the install_emacs.sh file and change the _make -j_ option<br/>Example:-
```
make -j 4
```
and allot your desired number of threads
* Run the script

## Most importantly, Enjoy!
Thank you.
