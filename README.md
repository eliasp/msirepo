Repository of OpenSource MSIs
=============================

The long-term goal of this repository is, to provide as many MSIs for OpenSource applications as
possible.
MSIs can be way easier distributed to Windows servers and clients than any _silenced_ installers in
GPO or SCCM driven environments as they don't require any additional scripting effort and properly
handle version upgrades etc. All this is still far from being a perfect package manager like Portage
but it's a drastical improvement over just using regular installers.

The idea of a OpenSource MSI repository is driven by the fact, that there is now a full toolchain to
build MSIs based on the WiX specification called [msitools](https://live.gnome.org/msitools) which
doesn't require WINE, Mono or any other hacks and works in a headless Linux build-server
environment.

For now, only OpenVPN will be packaged. If this attempt is successful, further applications might be
added to the repository.
