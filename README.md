# bov.cpp
Simple Vanilla Buffer Overflow Testing Application for Windows 10+

Required compilation options (MS Visual Studio Community 2019):

- Disable Security Check /GS-
- Data Execution Prevention (DEP): NO /NXCOMPAT:NO
- Randomized Base Address: NO /DYNAMICBASE:NO
- Base Address: 0x40400000

During execution it may also be neccessary to Ignore warnings using button Ignore.

Author: Marcin Wolak

https://www.linkedin.com/in/marcinwolak/

https://marcin-wolak.medium.com/

Link to article: OSCP Stack Buffer Overflow — Four ways to completely get rid of NOP (\x90\x90\x90) Slides from your Payloads

https://marcin-wolak.medium.com/oscp-stack-buffer-overflow-four-ways-to-completely-get-rid-of-nop-x90-x90-x90-slides-from-f01868b2fd34
