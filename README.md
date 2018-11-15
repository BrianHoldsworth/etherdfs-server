# etherdfs-server
Migrated from source forge. MIT License.
Copyright © 2017, 2018 Mateusz Vistelink

### EtherDFS - The Ethernet DOS File System

EtherDFS is an 'installable filesystem' TSR for DOS. It maps a drive from a remote computer (typically Linux-based) to a local drive letter, using raw ethernet frames to communicate. For years, I was using LapLink to transfer files between my various "retro" computers. It works, yes, but it's also annoyingly slow and requires constant attention. One day I thought, "Wouldn't it be amazing if all my DOS PCs could share a common network drive, similarly to how NFS operates in the *nix world?*". _This day EtherDFS was born. I clearly didn't invent anything - the concept has been around almost as long as the first IBM PC, and several commercial products addressed that need in the past. I am not aware, however, of any free and open-source solution. Besides, all the commercial solutions I know require to set up a pretty complex network environment first, while EtherDFS doesn't need anything more than just a packet driver_.
