# Advisor
This is a [Hearthstone Deck Tracker](https://github.com/HearthSim/Hearthstone-Deck-Tracker) plugin which tries to guess the opponent's deck while playing and shows it's supposed deck and cards left.

# Decription
Advisor tries to guess the opponent's deck based on the played cards.
First, the import function of Advisor allows you to quickly import hundreds of archetype decks from metastats.net.
Now while playing a Hearthstone game, with every revealed opponent card the plugin calculates similarities between those cards and all imported archetype decks.
Finally the deck with the highest match is presented to the player via overlay.
Since all played cards are additionally removed from that archetype deck, the player can see which cards the opponent supposably has left in his deck or hand with a certain likelihood.

# Installation
- Download the [latest release](https://github.com/djdookie/Advisor/releases) (zip file)
- Unzip it into your HDT plugin folder (should be %AppData%\HearthstoneDeckTracker\Plugins)
- Enable the plugin in HDT (Options->Tracker->Plugins->Advisor->Enabled)
- Import archetype decks (Plugins->Advisor->Import archetype decks)
- Play the game and enjoy
- Optional: Check the plugins settings to fit your preferences
- Hint: Move the secrets overlay position of HDT a bit to the right to not overlap with Advisors overlay window (Options->Overlay->General->Unlock overlay)

# Donation
If you like Advisor and want to support it, you can contribute here or make a [donation](https://paypal.me/djdookie). Thank you!

# Special Thanks
This project is open source, like all the great stuff it is based on or inspired by.
I especially want to thank the people behind Hearthstone Deck Tracker, Metastats.net and some other HDT plugins like EndGame.