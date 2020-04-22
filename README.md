# Nice & Simple CSS framework

Demo: https://tomsoderlund.github.io/niceandsimple-css/

Design goals:

- A good starting point for any web/mobile/PWA project.
- Easy to customize. Example: change the color of `button`, and hover states are automatically updated (they use `filter`).
- Avoid weird classes* as much as possible, just use element names.
- Lightweight (somewhat).
- Compatible (somewhat).

*Exceptions: `.fieldset` (because of `fieldset` flexbox bug), `.tag` (tags/tokens), `.flex` (flexbox container for columns etc).


## Install

    yarn add niceandsimple-css


## Import in JavaScript

    import '../node_modules/niceandsimple-css/niceandsimple.css'
