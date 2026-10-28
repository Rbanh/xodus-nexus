# Nexus feature previews

These screenshots accompany the separately selectable feature PRs #405, #406, and #409-#413 in domsvoboda/xodus-nexus. They are rendered from the actual React components with synthetic data, not copied Xbox web pages.

Every profile, message, game entry, counter and party member is sample data. The capture profile has no live account and blocks external HTTP(S). The Guide uses a preview backdrop; no game, microphone, voice session, real message, invitation or relationship change was used. These images demonstrate UI only, not end-to-end social interoperability.

The screenshots live on this separate documentation branch so none of the feature PR source commits or tested code trees need to change.

- [01-update-reuse.png](01-update-reuse.png): Sample update queue: verified local reuse and network bytes are shown separately. Counters are synthetic.
- [02-chat-compose.png](02-chat-compose.png): Sample conversation with a multiline draft. Shift+Enter keeps a newline.
- [03-chat-enter-send.png](03-chat-enter-send.png): The same dummy conversation after Enter submits the draft once. This is a synthetic send, not a real message.
- [04-social-shelf.png](04-social-shelf.png): The right-side Social shelf inside Nexus, using made-up friends.
- [05-social-actions.png](05-social-actions.png): Profile, message, favorites and blocking actions in the friend context menu. No relationship action was performed.
- [06-full-profile.png](06-full-profile.png): A full profile inside Nexus. All names, scores, connections and game history are sample data.
- [07-recent-players.png](07-recent-players.png): The Recent players view, populated with dummy entries.
- [08-chat-window.png](08-chat-window.png): A separate chat BrowserWindow, opened from the Social view with dummy data.
- [09-second-chat-window.png](09-second-chat-window.png): Another independent chat BrowserWindow with a different sample recipient.
- [10-party-controls.png](10-party-controls.png): Party controls with synthetic members and voice state. This preview does not verify live voice or invite acceptance.
- [11-guide-shelf.png](11-guide-shelf.png): The separate Guide layout, opening from the left. The backdrop and profiles are synthetic; no game was launched.
- [12-guide-chat.png](12-guide-chat.png): A movable chat view inside the Guide, shown with a dummy conversation and preview backdrop.
- [13-guide-settings.png](13-guide-settings.png): Guide controls below storage: enable switch, recorded shortcut and shelf edge. All paths and account details are dummy values.
- [14-shortcut-recording.png](14-shortcut-recording.png): Shortcut recording in progress. The fixture uses a synthetic shortcut-registration API.
- [15-guide-party.png](15-guide-party.png): The Guide party-controls connector, displaying synthetic party/voice state. No microphone, call or invitation was used.
