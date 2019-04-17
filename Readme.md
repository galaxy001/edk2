# EDK II Project

Forked from [kholia/edk2](https://github.com/kholia/edk2). Since the [offical](https://github.com/tianocore/edk2) one changed to use readonly pagetables on 2018, we have to revert the 2 commit to boot macOS.

See [https://github.com/kholia/edk2/commit/071595106dceb2b19fca4399b8eec9886f43bb31](https://github.com/galaxy001/edk2/commit/071595106dceb2b19fca4399b8eec9886f43bb31) for the commit of "Revert readonly pagetables introduced by 2ac1730 and 147fd35".

My [commit](https://github.com/galaxy001/edk2/commit/e4f38c358d2c218a95926660f2a8f32cde9cb64f) added *more 16:10 HiDPI(2x) resolution modes*. And this have been [merged](https://github.com/kholia/edk2/pull/1) to *kholia/edk2*.



For Arch Linux users:

See `PKGBUILD.ovmf-git`, which is from <https://aur.archlinux.org/packages/ovmf-git/>.
Last Updated: 	2019-01-14 01:15

See also `PKGBUILD.edk2-ovmf-macboot-git` of <https://aur.archlinux.org/packages/edk2-ovmf-macboot-git/>.
Last Updated: 2018-04-22 12:53

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
* [Release Planning](https://github.com/tianocore/tianocore.github.io/wiki/EDK-II-Release-Planning)
* [UDK2017](https://github.com/tianocore/edk2/releases/tag/vUDK2017)
* [UDK2018](https://github.com/tianocore/edk2/releases/tag/vUDK2018)
* [edk2-stable201811](https://github.com/tianocore/edk2/releases/tag/edk2-stable201811)
