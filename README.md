Welcome.

This is a maintained technical guide that aims to provide introduction to various online tracking techniques, online id verification techniques and guidance to creating and maintaining (truly) anonymous online identities including social media accounts safely and legally.

This guide is an open-source non-profit initiative, [licensed] under Creative Commons Attribution 4.0 International ([cc-by-4.0]) and is not sponsored/endorsed by any commercial/governmental entity.

The latest version is **0.7.3**, See the CHANGELOG here: <https://anonymousplanet.github.io/thgtoa/CHANGELOG.html>

- The Online version of the guide is available at <https://anonymousplanet.github.io/thgtoa/guide.html>

All PDF files in this guide have been checked by VirusTotal (see links) but you can always double check them using PDFID which you can download at <https://blog.didierstevens.com/programs/pdf-tools/>
Install Python, Download PDFID and run "python pdfid.py file-to-check.pdf" and you should see these at 0:

'''
/JS                    0
/JavaScript            0
/AA                    0
/OpenAction            0
/AcroForm              0
/JBIG2Decode           0
/RichMedia             0
/Launch                0
/EmbeddedFile          0
/XFA                   0
'''

Note that this guide does not endorse VirusTotal at all and it should be used with extreme caution and never with any sensitive documents.

- A PDF version of this guide is available at <https://anonymousplanet.github.io/thgtoa/guide.pdf> ([VirusTotal guide.pdf])
- A Dark Themed PDF version of this guide is available at <https://anonymousplanet.github.io/thgtoa/guide-dark.pdf> ([VirusTotal guide-dark.pdf])
- A weak password protected PDF version of this guide is available at <https://anonymousplanet.github.io/thgtoa/guide-p.pdf> and password is **thgtoa** ([VirusTotal guide-p.pdf])

SHA56 Checksums of all the files are available within <https://github.com/AnonymousPlanet/thgtoa/raw/main/sha256sum.txt>

All the files of this project are also signed using GPG (see the .sig files in the repository).

If you don't know how to verify files with GGP signatures, you should first install gpg on your system:
- Windows: Install gpg4win from <https://www.gpg4win.org/download.html>
- MacOS: Install GPG Tools from <https://gpgtools.org/>
- Linux: gpg should be installed by default

Import the GPG key using the following command from a command prompt or terminal: "gpg --auto-key-locate nodefault,wkd --locate-keys 0xEB16B6AB4AB7BA61F33E2DFD0051E9A589DAB601" 

If it doesn't work, you can also download/view it directly from here: <https://github.com/AnonymousPlanet/thgtoa/raw/main/AnonymousPlanet_0x89DAB601_public.asc>

And then import it manually by issuing the following command: "gpg --import AnonymousPlanet_0x89DAB601_public.asc" (or any other file you saved it to). Or if you're using indows, just use the import function within the Kleopatra app.

Finally verify the files by issuing the following commands: "gpg --verify guide.md.sig guide.md" and "gpg --verify guide.pdf.sig guide.pdf".

Alternatively on Windows if you installed gpg4win, just double click any sig file and it will automatically check the file in question for validity using Kleopatra.
The result should show a good signature for each file.

You can also verify the authenticity of this gpg signature using my Keybase.io profile <https://keybase.io/anonymousplanet> and the PGP key is also published on <http://keys.gnupg.net/>, <https://pgp.mit.edu/> and <https://keyserver.ubuntu.com/> using the following PGP fingerprint: 0xEB16B6AB4AB7BA61F33E2DFD0051E9A589DAB601

All commits on this repository are signed and verified using the same key.

For safety, an automated mirror of this repository is also located at GitLab here: <https://gitlab.com/AnonymousPlanet/thgtoa>

Feel free to submit issues using Github Issues or discuss using Github Discussions.

If you'd like to make a donation to this project, you can do so from <https://anonymousplanet.github.io/thgtoa/donations.html>.

Follow me on Twitter <https://twitter.com/AnonyPla> (can't guarantee this account will stay up)

Have a good read.

[cc-by-4.0]: https://creativecommons.org/licenses/by/4.0/
[licensed]: https://anonymousplanet.github.io/thgtoa/LICENSE.html
[VirusTotal guide.pdf]: https://www.virustotal.com/gui/file/868b09657f8a3d47e94c9c4899ebb3aa0fc4ae5a3ea48a62df417fdb0aed77f0/detection
[VirusTotal guide-dark.pdf]: https://www.virustotal.com/gui/file/6bf1285e24baeac6a5efc6c03778a9fba61316198068d52774c74497d6ddfe40/detection
[VirusTotal guide-p.pdf]: https://www.virustotal.com/gui/file/8342d83834551b49c300f4075fd9f6f1e940434255175a318a74ac67b1060ee4/detection
