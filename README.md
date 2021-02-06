# P2C-Example
P2C Example for KeyAuth authentication system

People were asking for this, so here. In c++.

**Help?**

You should not own a P2C if you cannot figure out how to read basically. You won't be helped, this basic programming is not covered by KeyAuth.

**Setup:**

part1.rar is the loader. This contains the KeyAuth login and injects the dll compiled from part2.rar

part2.rar is injected into a random windows process. The dll from part2.rar should be packed with VMP, make sure memory protection is on.

part3.rar is another dll which is put inside part2.rar. it is an injector. download https://mh-nexus.de/en/downloads.php?product=HxD20, drag your cheat dll into hxd, do select all, then I believe edit, copy as C, paste that into DLL.h of part3.rar. Then, compile part3.rar. take that dll, and put it in hxd, do select, copy as C, paste into Injector.h of part2.rar, and rename `rawData` to `injector`.

Enjoy
