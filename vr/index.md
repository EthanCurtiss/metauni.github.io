# Virtual Reality

One of the reasons we have chosen to build metauni on top of Roblox is the wide accessibility of that platform: it can be accessed on PC, Mac, iOS and Android and also using Virtual Reality (VR) headsets such as the Meta Quest 2. Current headsets have their limitations, but over time we believe that VR will become one of the main ways that people choose to access metauni. To this end, we are in the process of building virtual reality support into all of the metauni tools, such as [metaboard](https://github.com/metauni/metaboard) and [metaorb](https://github.com/metauni/orb).

<iframe width="800" height="450" src="https://www.youtube.com/embed/I97UUnhPC2c" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

## Why VR?

One of the reason that metauni events are more engaging than a Zoom lecture is the sense that the participants are sharing a 3D world. This sense is only heightened in VR. Here are some of the specific benefits we have noticed so far in our experiments:

* **Speakers in VR have more fun**: as a VR speaker you get to use your hands, you can write at the board and then turn to look at the audience, you can see their questions as text bubbles above their head (if they aren't using voice chat) and in general it feels much closer to the energy of an in-person lecture as compared to giving a lecture by writing on an iPad.

* **It's more engaging for audiences** even if they aren't in VR: the avatar of a VR speaker is "alive" in a way that normal avatars aren't, the hands move and the head tilts when the speaker is looking at something. When they are writing on a board you can see the motion of their hand and the pen. All of this adds a rich dynamic and physical layer to the presentation, which beats words simply appearing on a board while the speaker's avatar stands stiffly by.

* **Necks are useful**. A physical classroom is a rich information environment. It isn't unusual in a math lecture to have four or six boards full of mathematics, all visible to the audience; in a difficult calculation or proof this context can be the difference between frustration and enlightenment. While in principle you can turn your camera to look at multiple boards while participating in metauni on a 2D screen, VR comes much closer to replicating the information richness of a physical room - just turn your neck and you can take in many more boards.

We expect that VR will be adopted by speakers first, and later by audiences (as the technology becomes more affordable and convenient).

Some of the current drawbacks of VR:

* While headsets are relatively inexpensive (on the order of AUD$600) compared to their historical prices, it's a significant investment if on top of that you also need to buy a gaming PC (which is currently required to run Roblox in VR, see below).
* Wearing a headset for extended periods is not comfortable for all users.
* Being in VR cuts you off from written notes in a way that using metauni on an iPad does not.

## Notes

So far members of our community have experience only with the [Meta Quest 2](https://store.facebook.com/au/quest/products/quest-2/) so this text will include specific references to Quest 2 hardware, but everything should work with other headsets (such as the Valve Index). 

* At the moment VR support in Roblox is sufficient but not first-class, in the sense that the only way to run Roblox is by tethering your headset to a PC on which Roblox is running. This tethering is either achieved by a [link cable](https://store.facebook.com/au/quest/accessories/quest-2/link-cable/) or by Air Link, which allows your headset to play games running on your PC via a wireless connection.

* There are reports that a native Roblox client is coming for the Meta Quest 2, which would make accessing metauni in VR significantly more convenient, but until then linking to a PC is required. The hardware requirements for the PC are significant (i.e. a decent GPU, I use a NVIDIA GeForce RTX 2080).

* The inbuilt VR for Roblox uses a third person view. We use the [Nexus VR character model](https://thenexusavenger.itch.io/nexus-vr-character-model) which allows us to use VR in first person (and therefore be able to write on metaboards, for example).

* The 2D Roblox GUI appears as an overlay (probably transparent) near the center of your field of view in VR. You should be able to see the Roblox icon in the top left hand corner of this overlay. To activate spatial voice in VR you'll need to press the menu button on your left controller, point the right controller at the Roblox menu icon and find the toggle in the Roblox menu (see [this video](https://youtu.be/4AjUzqqjsGg)).

Currently VR for metaboard is in testing and is only available in the pocket Symbolic Wilds 1 ([link](https://www.roblox.com/games/start?placeId=8165217582&launchData=pocket:Symbolic%20Wilds%201) for iOS and Windows) for those with Scribe permissions.
