# EDK II Project

See also <https://www.contrib.andrew.cmu.edu/~somlo/OSXKVM/> and <https://www.contrib.andrew.cmu.edu/~somlo/OSXKVM/index_old.html>.

Gabriel L. Somlo

FINAL UPDATE (2018-10-21): 
I no longer have the cycles to work on this project. At this point QEMU and KVM are mostly capable of supporting OS X (up to Sierra), and the largest portion of the effort still required lies with edk2/ovmf (start with my fork on github as indicated below, and go from there).

NOTE: Installer .iso images prepared based on Sierra 10.12.4 or later will hang during boot. However, guest images installed with 10.12.3 or earlier can successfully be upgraded, assuming the applesmc fix mentioned above is applied. The cause for this is as of yet unknown (to me, at least).

OS X High Sierra (10.13) doesn't boot at this time. 
*So, use Clover EFI loader instead.*

`PKGBUILD.edk2-ovmf-macboot-git` is from <https://aur.archlinux.org/packages/edk2-ovmf-macboot-git/>.
Last Updated: 	2018-04-22 12:53

------

A modern, feature-rich, cross-platform firmware development environment
for the UEFI and PI specifications from www.uefi.org.

Contributions to the EDK II open source project are covered by the
[TianoCore Contribution Agreement 1.1](Contributions.txt)

The majority of the content in the EDK II open source project uses a
[BSD 2-Clause License](License.txt).  The EDK II open source project contains
the following components that are covered by additional licenses:
* [AppPkg/Applications/Python/Python-2.7.2/Tools/pybench](AppPkg/Applications/Python/Python-2.7.2/Tools/pybench/LICENSE)
* [AppPkg/Applications/Python/Python-2.7.2](AppPkg/Applications/Python/Python-2.7.2/LICENSE)
* [AppPkg/Applications/Python/Python-2.7.10](AppPkg/Applications/Python/Python-2.7.10/LICENSE)
* [BaseTools/Source/C/BrotliCompress](BaseTools/Source/C/BrotliCompress/LICENSE)
* [MdeModulePkg/Library/BrotliCustomDecompressLib](MdeModulePkg/Library/BrotliCustomDecompressLib/LICENSE)
* [OvmfPkg](OvmfPkg/License.txt)
* [CryptoPkg/Library/OpensslLib/openssl](CryptoPkg/Library/OpensslLib/openssl/LICENSE)

The EDK II Project is composed of packages.  The maintainers for each package
are listed in [Maintainers.txt](Maintainers.txt).

# Resources
* [TianoCore](http://www.tianocore.org)
* [EDK II](https://github.com/tianocore/tianocore.github.io/wiki/EDK-II)
* [Getting Started with EDK II](https://github.com/tianocore/tianocore.github.io/wiki/Getting-Started-with-EDK-II)
* [Mailing Lists](https://github.com/tianocore/tianocore.github.io/wiki/Mailing-Lists)
* [TianoCore Bugzilla](https://bugzilla.tianocore.org)
* [How To Contribute](https://github.com/tianocore/tianocore.github.io/wiki/How-To-Contribute)
