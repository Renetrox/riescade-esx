

    ███████   ██ ████████  ████████   ██████      ██     ███████   ████████
    ░██░░░░██ ░██░██░░░░░  ██░░░░░░   ██░░░░██    ████   ░██░░░░██ ░██░░░░░ 
    ░██   ░██ ░██░██      ░██        ██    ░░    ██░░██  ░██    ░██░██      
    ░███████  ░██░███████ ░█████████░██         ██  ░░██ ░██    ░██░███████ 
    ░██░░░██  ░██░██░░░░  ░░░░░░░░██░██        ██████████░██    ░██░██░░░░  
    ░██  ░░██ ░██░██             ░██░░██    ██░██░░░░░░██░██    ██ ░██      
    ░██   ░░██░██░████████ ████████  ░░██████ ░██     ░██░███████  ░████████
    ░░     ░░ ░░ ░░░░░░░░ ░░░░░░░░    ░░░░░░  ░░      ░░ ░░░░░░░   ░░░░░░░░  

RIESCADE-ESX v3 — TEST: dynamic category tabs / Riescade geometry

This version was rebuilt after comparing:
1. the working Swatch PS5 ES-X theme structure,
2. the original Riescade system/gamelist XML geometry,
3. the supplied real Riescade screenshots.

Key decisions:
- Swatch-style native ES-X system carousel.
- Swatch-style native ES-X horizontal gamelist carousel.
- Riescade's original carousel vertical position and selected-game geometry.
- Original Riescade filter/config/avatar/header resources.
- Original Riescade fanart, overlay, platform logos, frames and click sound.
- No Batocera subset, storyboard, stackpanel, rectangle, onclick or expression syntax.
- No unsupported image opacity property.
- No theme.ini dependency in this stability-first version.
- TEST: Original 7 category labels are separate, opt-in styled text extras.

Limitations:
- TEST: Hardware-category tabs now highlight from native ES-X activeFor metadata; on-device evaluation pending.
- The Play button is visual; normal A/Enter launches the selected game.
- Batocera's game-time binding is not exposed as a native themed metadata field,
  so the right card uses Players + Play Count + Release Year instead.


