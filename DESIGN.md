# Editor hub design

Use the Ink and apricot palette from OmniReply Admin. The shared stylesheet in `assets/hub-theme.*.css` covers the hub and both installation pages.

Keep logo artwork unchanged. Orange is reserved for the original plugin logo artwork. Use cream page backgrounds, white cards, 12px card corners, 8px controls, hairline neutral borders, and ink primary actions. Hub choices use outlined actions; each installation page has one filled download action. Body links use the accent text token, chrome uses secondary text, and keyboard focus uses the double ring. Text on tinted panels is primary or accent, with semantic colors for status messages. Keep the theme light.

When editing the stylesheet, give it a new content-hash filename and update all three HTML references to bust caches. Keep old hashed assets available for cached pages. Preserve package links, update feeds, and installation instructions when making visual changes.

Place the original Thunderbird logo immediately left of the hub title, 36px square with a 12px gap and no background tile. Keep its official colors.
