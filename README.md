# runuo-extended
RunUO Extended, based on RunUO 2.0 FINAL

This is a third party extension to [http://www.runuo.com/ Run UO] and do not involve the original team. The logo at the top of this page is stolen from them too :)

You can checkout the svn to get an empty server running with all the modifications we made to the original RunUO 2.0 Final version. You can use the .sln with Visual Studio 2010, but you can't compile and run, you must use RunUO.exe for that.

----
_For specific changes and to help you modify them, here's a summary:_

 * *Farming System:*
  * [Eggs & legs from chicken](https://github.com/Ericmas001/runuo-extended/commit/68758bc7b52f22101624d10bf3ec3733e1515955)
 * *Utils:*
  * [Change Command Handler](https://github.com/Ericmas001/runuo-extended/commit/6e8d2880b5065ae41b8a5e358be03f87a7f22576) because "." is better than "["
  * [Change Server Name](https://github.com/Ericmas001/runuo-extended/commit/3ff0686a5273c0ab30a6655854c5af2219bfd33e) because "RunUO RT" is probably not what you want
  * [Change Starting Location](https://github.com/Ericmas001/runuo-extended/commit/8b2942f51676d6db1fd94c07abe11597ea7b2cc7) because Malas is the only cool map :)
  * [Autosave 15min instead of 5min](https://github.com/Ericmas001/runuo-extended/commit/0ebbc5f96cefeb0e81175a77f3872a859065172c) because 5min is SPAM :p
  * [SaveGump instead of TextMessage](https://github.com/Ericmas001/runuo-extended/commit/39799c19868d716e9b8edddee60495eb3c0653cf) because it looks pretty
  * [Translation Center](https://github.com/Ericmas001/runuo-extended/commit/6123a30178253e82ec956461b999c7edd7721be5) because french is cool too
 * *Commands:*
  * [Commands for GMs](https://github.com/Ericmas001/runuo-extended/blob/master/RunUOExtended/trunk/RunUOExtended/Scripts/Commands/StaffCommands.cs): !HearAll Clone !CloneMe Control !GmMe Refresh !SayThis (needs [AI_None](https://github.com/Ericmas001/runuo-extended/commit/effdc8ca3d4888cc4fa9522422ba161f6b218c65))
  * [.who for players + regions](https://github.com/Ericmas001/runuo-extended/commit/7df41d3a6b9bb03921cc18fc11a27c2e28e4f0d8) because players like to know who is online too !
 * *Crafting:*
  * [Some ML Items](https://github.com/Ericmas001/runuo-extended/commit/dab21f5ae78952af88783872ece14fb15c67d452): Some ML items for balcksmith that was not craftable but available in game.
 * *Items:*
  * [Horse Pole](https://github.com/Ericmas001/runuo-extended/blob/master/RunUOExtended/trunk/RunUOExtended/Scripts/Items/Misc/HorsePole.cs): To keep your horses yours between connections (needs [AI_None](https://github.com/Ericmas001/runuo-extended/commit/effdc8ca3d4888cc4fa9522422ba161f6b218c65))
 * *AI:*
  * [AI_None](https://github.com/Ericmas001/runuo-extended/commit/effdc8ca3d4888cc4fa9522422ba161f6b218c65), an easy way to have non-movable, non-agressive creatures (Dolls !)
  * [Animal fear](https://github.com/Ericmas001/runuo-extended/commit/14ede304dd17be2caabdb264ff5e842857117d0a) is making small animals running away when you're approaching
 * *Vendors:*
  * [Barber](https://github.com/Ericmas001/runuo-extended/blob/master/RunUOExtended/trunk/RunUOExtended/Scripts/Mobiles/Vendors/NPC/Barber.cs) will keep your hair and beard up to date !
