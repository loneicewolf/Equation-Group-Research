Equation Group's full hacking cycle


Stage 1: Target Selection

    • Normal attackers aren’t comparable, and usually even APTs only have a few focuses. Such include selling information acquired (dox, blueprints, copyrighted, top secret files, etc)
    • The reasons the NSA may pursue are too various to list, but their tradecraft leaked through documents by Snowden and some contained within the Shadow Brokers leak should give a decent idea.

Stage 2: Target Research / Recon

    • Fuzzbunch touches the machine

Stage 3: Target Penetration (Exploitation or possible MitM attack)

    • Going into exploit choosing it usually goes for doublepular

Stage 4: Command and Control (Establishing persistence)

    • FuzzBunch Framework now offers different implants, such as PeddleCheap
    • Peddlecheap is usually loaded as the implant from double pulsar exploit 

Method 2: (Loud)

    • Using credentials from recon, then
    • mount admin share and push peddlecheap.exe
    • schedule task to run it, then delete

Method 3: (Loud)

    • mount admin share and push configured peddlecheap
    • abuse WMI remote exec to run exe

Method 4: (Loud)

    • Generate Peddlecheap implant triggered via WinSockHelper
    • Reboot Machine

Method 5:(Quiet)

    • Use "packetdirect" command,  it is a tool that drops a kernel level driver that goes past the tcp/ip stack and allows for raw command injection
    • configure fuzzbunch with planted target as a redirector
    • smb/namepiped touch (tells you what exploits to use)
    • exploit
    • DoublePulsar loads Peddlecheap

Stage 5: Target Discovery

    • peddlecheap then talks to the LP which is Danderspritz

Stage 6: Data Exfiltration

    • Optional Proxying between this, this then communicates to DanderSpritz 
    • Danderspritz can CoC over the network as needed,  General Ops
    • “docsurvey" identifies interesting documents and sharepoint sites
    • use the command "sharepoint" to recursively pull files
	
Stage 7: Intelligence dissemination (or general ops in this case, further implanting, spying, etc)

    • Notes after Ops, make report summary 

Stage 8: Information Exploitation (Aka wrapping up Ops for recon, or pivoting  in  the network)

    • Cleanup, lessons learned or data gained etc, move on.
