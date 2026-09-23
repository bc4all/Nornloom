# Release notes

What changed in Nornloom, newest first. The site at [nornloom.com](https://nornloom.com) always
runs the latest; the Android app is released in numbered versions, and each version's section says
what it carries. Bugs you report through the [issue forms](https://github.com/bc4all/Nornloom/issues/new/choose)
are listed here when they are fixed.

## On the site since 0.3.1 (21 September 2026)

New:

- **The Skald's Road, a walkthrough of every saga.** [QUESTS.md](https://github.com/bc4all/Nornloom/blob/main/QUESTS.md)
  in the public repository walks the whole story step by step with a screenshot of each: where to
  go and which way from the step before, who is waiting there and what they say, what to fight,
  every riddle with its answer folded away, and the reward. The prologue, the thirteen main sagas,
  the five side sagas, the village jobs and a table of every hamlet's two jobs.

- **The hero's record.** A fifth tab in the backpack, Record, keeps the tally: fights won, lost
  and fled and the share won, the best streak, the strongest foe beaten and the best upset,
  the beast you have slain most, named foes and strongboxes, duels and sparring, gold won and
  spent, XP, Rune-dust, cards won and lost and how many of the set you hold, gear found, quests
  done, deaths. It counts from now on; what a hero did before this release is not on it.

- **A world map.** The Map button in the world's toolbar opens the whole overworld at a glance:
  every land with its name and the levels of its beasts, a house on every village and hamlet, mist
  over the lands your level does not open yet, and a gold dot where you stand. Press a land to read
  about it: what roams there, the level the rune stone asks for, and whether you are there now.
- **Mist over the lands beyond your level.** In the world itself, a land you cannot enter yet is
  drawn under a pale haze, so you see where the rune stones stand before you walk into one.
- **Hrafn's lesson for newcomers online.** A hero new to a world is offered the guided first bout
  the moment it arrives, the way a solo hero is offered it after the cold open; online there is no
  cold open, so the offer stands on its own. It is made once, and the world remembers the answer
  whichever device you play on. The lesson is still there whenever you want it: at Hrafn's yard in
  Eikthorp, and from the title screen under Learn to play.
- **Who is online, in the chat.** A third tab in the chat, Online, lists every hero in your world
  now with its level; press a name to open a private thread with them.
- **Fold the toolbar.** The world's toolbar (Bag, Quests, Decks and the rest) has a Hide button,
  as the chat does, and folds to a single Menu button, so a phone has more of the map. It stays
  folded until you open it again.
- **Only the cards you can add.** In the deck editor, Can be added shows only the cards this deck
  can still take a copy of, with the count shown beside it.

Fixed:

- **A card that shows the opponent's hand showed nothing.** Heimdallr's Watch and every card that
  says your opponent plays with their hand revealed now do: the Hand count on the opponent's plate
  becomes a button that lays their hand out, and a tap on a card opens it to read.
- **A Berserk Warrior could be kept home.** End turn ended the turn even when a Berserk Warrior
  could still raid. Now End turn opens the raid with the Berserk chosen and says why, and online
  the world refuses the turn's end too.
- **The deck editor cut the collection short on a phone.** The last rows of your collection hid
  under the deck; now the whole collection shows.
- **Card rules that did less or more than the card says.** Frost-grip now holds the Warrior it
  wounds, whether it raids or blocks. Gear that gives Swift (Gullfaxi, Sleipnir) lets a Warrior
  raid the turn it gets it. A card that returns an opposing Warrior returns one, the one you aim
  at, no longer all of them, and Hallowed Warriors are safe from it. A debuff chanted on the
  opponent's turn ends with that turn instead of lasting through yours. A God loses one Devotion
  for five Thread lost in a turn, not two. Oath Broken answers a Seiðr only, as it says. Counters
  the forge made as Seiðr, which could never be played, are Galdr now. Surtr's fire at the fifth
  step of the Doom lets a Ward's "when it is destroyed" happen (Bifröst Breaking burns as it
  should). Gleipnir goes to the Helheim of whoever bound with it. Raiding with a Gjallarbrú Warrior
  shows the raid's outcome again. Cold Grasp, Rain of Sparks and Tiwaz say exactly what they do.
- **Four gods left nothing behind.** Týr, Odin, Freyja and Surtr promised a Legacy and left
  none when they departed. Now they do: opposing Berserk Warriors get -1 Might after Týr, an
  extra card at each Dawn after Odin, 1 Thread at each Dawn after Freyja, and 1 damage to your
  opponent's Thread at each Dawn after Surtr.
- **Duels: the clock and the blocks.** When the turn time ran out on a defender facing a
  Gjallarbrú raider, or on a player with a Berserk Warrior, the duel was lost on the spot; the
  clock now makes the move the rules demand. And only the defender may set the blocks.

- **Walking online on a phone could pull you back to where you set out from.** When the line
  stalled or was replaced (a phone changing networks, a tab woken up), the world either refused
  the burst of steps that arrived at once or put you back where it had last saved you, and the
  app only showed it when you stopped. Now the world takes such a burst, a hero coming straight
  back stands where it stood, the app does not walk at all while the line is down, and when the
  world does take a step back you are set right at the next tile, not at the end of the walk.
- **The beast you walked into ran off before the fight.** A timid beast (two or more levels below
  you) kept backing away while you read the challenge, so pressing Fight found nothing to fight.
  Now a beast you walk into turns to you and holds still until you step away, so the fight you are
  offered can be started.
- **A pack could box you in.** Beasts chasing you would gather on every side, and since a living
  beast blocks a step you could not move until you had fought each of them in turn. Now at most one
  beast stands beside you at a time: the rest keep roaming while it does, and a beast that ends up
  beside you all the same backs away and never attacks. You fight one beast at a time, alone and
  online alike, and always have a way out.

## 0.3.1 (20 September 2026, Android version code 11)

Fixed:

- **Online, beasts no longer walk up while you play a hand.** During a fight or a duel they kept
  coming, gathered on every side, and you rose from the table unable to move. Now nothing hunts a
  hero at a table, and whatever stands beside it backs away, so there is room to leave when the
  cards are put down.
- **The trader sells what the counter shows.** The world drew the counter without minding the
  peoples you play, so a card on the counter could be refused at the sale.

## 0.3.0 (20 September 2026, Android version code 10)

New:

- **Solo heroes follow your sign-in.** Signed in, your solo heroes are kept for your account, so
  the same heroes stand on the title screen of every device and on nornloom.com. Nothing is sent
  until you sign in.
- **The app turns with the phone.** A phone on its side gets the wide battle table: each shieldwall
  beside its plate, the hand in a column at the right.
- **Every screen speaks the seven tongues.** The last strings joined the dictionaries, and a test
  now holds every screen to them. Card text is English still.
- **The Android build is made by a workflow**, so a release no longer depends on one machine.

Fixed:

- **A world's restart no longer drops you.** The world says goodbye with a code the app comes back
  on; before, a restart left the world screen saying the line could not be kept.
- **Every online fight hung at "The world is dealing".** The opening frame carried more card ids than
  the app's guard allowed, so the table never appeared.
- **Back to the world from the dealing screen left the table set**, and the next fight was refused
  as "at the table already".
- **Continue after the world's report dealt the same fight again.**
- **Leaving a duel said "only sparring".** It now says it is a loss, and on an Open PvP world that a
  tenth of your gold goes with it.
- **A whisper could not find a name of two or three words.**
- **A hero's doings went to the wrong world.** Quests, the market and parcels of a Jotunheim hero
  reached Midgard.
- **Walking away from a challenge landed on "There is nothing here to fight".**

## 0.2.0 (20 September 2026, Android version code 8): the first release on Google Play

The whole game, on the site since the day before and now in the app: the cold open, Hrafn's lesson,
Eikthorp and the roads beyond, every fight a hand of Bindrune, and the shared worlds with chat,
parcels, trade, duels and the market. In the app, sign-in goes through the site and is kept for
thirty days.

New around the release:

- **First steps.** A new hero opens the first fights in the wild with a few Thread in hand, one
  less each level, so the first bouts are not the hardest.
- **Roll a name.** The name form offers a first name and a patronymic from thousands of
  combinations, for a world where each name is borne once.
- **Hrafn's lesson is fully scripted**: every move of the pupil and of the straw wolf is written
  down, and one framed control at a time is all there is to press, in seven tongues.
- **The help book** answers the questions players ask, about the story and about playing online,
  and links this repository, the issue forms and the credits. The [FAQ](FAQ.md) and the
  [Bindrune handbook](BINDRUNE.md) are printed from the game itself.
- **Dialogue, quests, the prologue and the sagas in six more tongues**: Polish, German, Spanish,
  Danish, Swedish and Norwegian, beside English.
- **Sign in with Google**, beside GitHub and Microsoft.
- **The table on a phone**: a card sheet that says the card in words, and a d-pad that is held and
  slid rather than tapped.
- **A tap moves a blocker**: a Warrior standing before one raider steps over to the chosen one.

Fixed:

- Two engine bugs found in the code audit, a world that no longer dies on a bad frame, saves that
  say when they fail, and the em-dashes gone from every text.
- Sparring runs on the local engine in an online world, and a refused fight says why instead of
  dealing forever.
- Name labels ride their sprites instead of leading them by a tile.
- A typed address opens nothing the hero could not reach on foot.
- The security audit of 20 September: budgets on every route and socket, the world's own word on
  quests and kills, dice from the system's randomness, the keeper's door keyed, hidden letters
  stripped from names, and the metrics door shut.

## Before the first release (19 September 2026)

Online play shipped on nornloom.com: two worlds (Midgard with duels by consent, Jotunheim with Open
PvP outside the villages and a tenth of the purse at stake), chat with private threads and blocks,
parcels through the traders, face-to-face trade, the market, profiles and boards, temples a hero may
make its home, idle heroes let go with a warning, and a world four times the size: a ten by six grid
of lands, each with its own level band, hamlets, caves and sagas.
