1. Found a thrid party library name A
2. Clone it to company github
3. Change the source code of the libray on company github A2

On xcode project, install the library from company github, without change project name and version

like: pod :git '{github link}'
// default is master branch


Issue:
Once deintegrate the pods then reinstall all pods,
pod used the cached A version but not the modified version A2.

Practice:
Move the modificed version A2 to company private git with private git spec repo and git code repo B with new name and version

