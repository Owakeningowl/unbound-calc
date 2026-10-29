# Pokémon Unbound 2.1.1.1 Damage Calculator, with dark mode and sprite panels

Live at <https://owakeningowl.github.io/unbound-calc/>.

A copy of the Unbound calc at <https://unboundcalc.byethost3.com/> (the Unbound fork of the
Smogon damage calculator by SkiDY), with three additions:

- **Dark mode**: the Dark mode / Light mode button in the header. The choice is saved in your
  browser; with no saved choice it follows your system setting.
- **Team / Box / Trash** under Pokémon 1: everything you import through Import / Export shows up
  as sprites. Click one to load it, drag between Team, Box and Trash, right-click to swap Team and
  Box. "Delete Pokémon in the trash" removes those sets.
- **Opposing Team** under Pokémon 2: the selected trainer's whole team as sprites (click to load),
  plus Previous / Next Trainer. Teams are shown in the party order from the Unbound Insane trainer
  doc where the trainer is in it.

The calc itself, its mechanics and its trainer sets are unchanged. The added files are
`css/unbound-extras.css`, `js/unbound-extras.js` and `js/data/team-order.js`; `index.html` only
gains the button, the two panels and those three includes (the external analytics tag is removed).

Credits: calc by the Smogon damage-calc contributors (MIT) and SkiDY's Unbound fork; sprites from
Pokémon Showdown; panel layout and dark palette follow the Null damage calc (MIT).
