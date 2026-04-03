To the 0x0002 community.

I am stepping away for a while. Everything you need to know is inside this file. 
Before I go, I leave you with one final exam. 

Do not expect this to be easy. Standard tools will lie to you. Debuggers will blind you. Disassemblers will show you a maze with no exit. 

If you get lost, read these field notes carefully:

[ FIELD NOTES & HINTS ]

01. The Phantom Seat
If you try to attach your debugger, the kernel will reject you. Ask yourself why. A process can only have one master. If the seat is already taken, who is sitting in it?

02. The Puppet and the Master
There are two actors on this stage. If you spend all your time watching the child dance, you will never see who is pulling the strings. Look for the split.

03. The Screaming Child
The payload is not decrypted by the code you are reading. The child knows nothing—it only knows how to panic and freeze (INT3). The knowledge you seek lives entirely outside its mind.

04. The Answer to Everything
The master key is 0x42. But do not bother searching for it in the payload's memory space. It never crosses the boundary until the exact microsecond it is needed.

Good luck. 
Never give up.

-- 0x0002 
