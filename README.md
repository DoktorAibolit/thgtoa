Welcome.

This is a maintained technical guide that aims to provide introduction to various online tracking techniques, online id verification techniques and guidance to creating and maintaining (truly) anonymous online identities including social media accounts safely and legally.

This guide is an open-source non-profit initiative, [licensed] under Creative Commons Attribution 4.0 International ([cc-by-4.0]) and is not sponsored/endorsed by any commercial/governmental entity.

The latest version is **0.7.6**, See the CHANGELOG at <https://anonymousplanet.github.io/thgtoa/CHANGELOG.html>

- The Online version of the guide is available at <https://anonymousplanet.github.io/thgtoa/guide.html>

All PDF files in this guide have been checked by VirusTotal (see links) but you can always double check them using PDFID which you can download at <https://blog.didierstevens.com/programs/pdf-tools/>

- Install Python, Download PDFID and run:

```python pdfid.py file-to-check.pdf```

And you should see these at 0:

```
/JS                    0 #This indicates the presence of Javascript
/JavaScript            0 #This indicates the presence of Javascript
/AA                    0 #This indicates the presence of automatic action on opening
/OpenAction            0 #This indicates the presence of automatic action on opening
/AcroForm              0 #This indicates the presence of AcroForm which could contain JavaScript
/JBIG2Decode           0 #This indicates the PDF uses JBIG2 compression which could be used for obfuscating malicious content
/RichMedia             0 #This indicates the presence rich media within the PDF such as Flash
/Launch                0 #This counts the launch actions
/EmbeddedFile          0 #This indicates there are embedded files within the PDF
/XFA                   0 #This indicates the presence of XML Forms within the PDF
```

**Note that this guide does not endorse VirusTotal at all and it should be used with extreme caution and never with any sensitive documents due to their "privacy policy".**

- A PDF version of this guide is available at <https://anonymousplanet.github.io/thgtoa/guide.pdf> ([VirusTotal guide.pdf])
- A Dark Themed PDF version of this guide is available at <https://anonymousplanet.github.io/thgtoa/guide-dark.pdf> ([VirusTotal guide-dark.pdf])
- A weak password protected PDF version of this guide is available at <https://anonymousplanet.github.io/thgtoa/guide-p.pdf> and password is **thgtoa** ([VirusTotal guide-p.pdf])

SHA256 Checksums of all the PDFs are available within <https://github.com/AnonymousPlanet/thgtoa/raw/main/sha256sum.txt>
SHA256 Checksums of the release files are available within the checksum file at <https://github.com/AnonymousPlanet/thgtoa/releases/latest>

To check the SHA256 Checksums please do the following:

Windows:
- From a command prompt, run ```certutil -hashfile filename.txt sha256```
- Compare the result with the hash in the checksum files.

MacOS:
- From a terminal, run ```shasum -a 256 /full/path/to/your/file```
- Compare the result with the hash in the checksum files.

Linux: 
- From a terminal, ```run sha256sum /full/path/to/your/file```
- Compare the result with the hash in the checksum files.

All commits and releases on this repository are signed and verified using the same key. Check for the "Verified" tags.

PDFs, Images and release files are also signed separately using GPG (see the .asc files on the release page and within the repository).

If you don't know how to verify files with GGP signatures, you should first install gpg on your system:
- Windows: Install gpg4win from <https://www.gpg4win.org/download.html>
- MacOS: Install GPG Tools from <https://gpgtools.org/>
- Linux: gpg should be installed by default

Import the GPG key using the following command from a command prompt or terminal:

```gpg --auto-key-locate nodefault,wkd --locate-keys 0xEB16B6AB4AB7BA61F33E2DFD0051E9A589DAB601```

If it doesn't work, you can also download/view it directly from here: <https://github.com/AnonymousPlanet/thgtoa/raw/main/AnonymousPlanet_0x89DAB601_public.asc>

And then import it manually by issuing the following command:

```gpg --import AnonymousPlanet_0x89DAB601_public.asc```

Finally verify the files by issuing the following commands: 

```gpg --verify guide.pdf.asc guide.pdf"```

```gpg --verify guide-p.pdf.asc guide-p.pdf"```

```gpg --verify guide-dark.pdf.asc guide-dark.pdf"```

You can also verify the authenticity of this GPG signature using my Keybase.io profile <https://keybase.io/anonymousplanet> and the PGP key is also published on <http://keys.gnupg.net/>, <https://pgp.mit.edu/> and <https://keyserver.ubuntu.com/> using the following PGP fingerprint: 0xEB16B6AB4AB7BA61F33E2DFD0051E9A589DAB601

For safety, an automated mirror of this repository is also located at GitLab here: <https://gitlab.com/AnonymousPlanet/thgtoa>

Feel free to submit issues using Github Issues or discuss using Github Discussions.

If you'd like to make a donation to this project, you can do so from <https://anonymousplanet.github.io/thgtoa/donations.html>.

Follow me on Twitter <https://twitter.com/AnonyPla> (can't guarantee this account will stay up)

Have a good read.

[cc-by-4.0]: https://creativecommons.org/licenses/by/4.0/
[licensed]: https://anonymousplanet.github.io/thgtoa/LICENSE.html
[VirusTotal guide.pdf]: https://www.virustotal.com/gui/file/076e82bdc7da37449d3f50e3f70b9a23842605e54fb4aaa61341196e7552f724/detection
[VirusTotal guide-dark.pdf]: https://www.virustotal.com/gui/file/adc8f5af6ea320d046ec1e8404444ddcbbb929398cea2680bb36764096691fb3/detection
[VirusTotal guide-p.pdf]: https://www.virustotal.com/gui/file/309e7e22b5601b78621b7e115502bbb9632be4cc473e92e4c162b77f0113fbfe/detection
