THM{I_CAUGHT_ALL_THE_PHISH}- Alternate Data Stream is an NTFS file attribute and was designed to provide compatibility with MacOS's Heirarchial file system.
- Any file created on the NTFS will have two data streams:
	- Data Stream : Default stream that contails the file data
	- Resource Stream : Typically contains the metadata of the file
- Attackers use ADS to hide malicious code or executables in the file attribute in order to evade detection
- This can be done by storing the malicious code or executables in the file attribute resource stream (metadata) of a legitimate file.