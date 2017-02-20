# mDNSFlush for iOS!

mDNSFlush is a system daemon for iOS that flushes the ```mDNSResponder``` and ```discoverd``` cache so that you shouldn't run into any issues with network dropping/disconnecting.

Incorperating this into your hosts file tweak means you can add over 3000 entries without having to worry about slowing down your users connections or dropping them all together. I highly encourage you devs to implement this into your tweaks, it will help to avoid a lot of headaches later. **If you implement mDNSFlush into your tweak. Please give me some credit!**

This will also be released as a standalone tweak on my repo for the developers that do not want to implement this into their tweaks.

**If you don't want to implement mDNSFlush directly into your tweak, you can add it as a dependency.**

**Changelog v1.1:**

1. Made a few small changes to make daemon less battery consuming and faster.
2. Added check for SHB on install to say thanks!
