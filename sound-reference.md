# Steam Deck UI sound reference

A list of applicable sounds (and their filenames) can be found below.
The sound files could be found at `(steam path)/steamui/sounds/`.

## Sound List (Categories)

There are a few categories of sounds, listed below:

### Toast

Toasts are notification sounds.

| Filename                        | Description                  | Condition                                                    |
| ------------------------------- | ---------------------------- | ------------------------------------------------------------ |
| `deck_ui_achievement_toast.wav` | Achievement sound            | Plays when an achievement is awarded.                        |
| `deck_ui_toast.wav`             | Notification sound           | Plays when a notification is recieved.                       |
| `desktop_toast_default.wav`     | Alternate notification sound | Plays occasionally isntead of the `deck_ui_toast.wav` sound. |
| `desktop_toast_short.wav`       | Alternate notification sound | Plays occasionally isntead of the `deck_ui_toast.wav` sound. |

### Navigation

These sounds are related to menu navigation.

| Filename                         | Description             | Condition                                                                                                                                             |
| -------------------------------- | ----------------------- | ----------------------------------------------------------------------------------------------------------------------------------------------------- |
| `deck_ui_misc_10.wav`            | Move cursor             | Plays as the user moves the navigation cursor on the screen.                                                                                          |
| `deck_ui_navigation.wav`         | Move cursor (Side menu) | Plays as the user moves the navigation cursor in some sidebar menus.                                                                                  |
| `deck_ui_bumper_end_02.wav`      | End of list             | Plays in some menus when you try to navigate past the edges of the menu, e.g. trying to go above the first item, or trying to go below the last item. |
| `deck_ui_into_game_detail.wav`   | Enter game menu         | Plays when the user selects a game and goes to its main page the one with the Play button and shows the game's banner art.                            |
| `deck_ui_out_of_game_detail.wav` | Exit game menu          | Plays when the user leaves the game menu page.                                                                                                        |
| `deck_ui_side_menu_fly_in.wav`   | Show side panel menu    | Plays when the Steam or Quick Access Panel menus appear.                                                                                              |
| `deck_ui_side_menu_fly_out.wav`  | Hide side panel menu    | Plays when the Steam or Quick Access Panel menus disappear. In some cases this will not play.                                                         |
| `deck_ui_tab_transition_01.wav`  | Change tab              | Plays when navigating to another tab in a horizontal tab list.                                                                                        |

### Actions

These sounds are related to buttons the user presses (not exactly related to navigation.)

| Filename                         | Description                  | Condition                                                            |
| -------------------------------- | ---------------------------- | -------------------------------------------------------------------- |
| `deck_ui_default_activation.wav` | Confirmation/Accept sound    | Plays in some menus depending on the button pressed.                 |
| `deck_ui_launch_game.wav`        | Game start sound             | Plays when the user starts a game from its game page.                |
| `deck_ui_slider_down.wav`        | Turn slider down             | Plays when moving a slider to the left.                              |
| `deck_ui_slider_up.wav`          | Turn slider up               | Plays when moving a slider to the right.                             |
| `deck_ui_switch_toggle_off.wav`  | Turn switch off              | Plays when toggling off a switch.                                    |
| `deck_ui_switch_toggle_on.wav`   | Turn switch on               | Plays when toggling on a switch.                                     |
| `deck_ui_typing.wav`             | Key press (virtual keyboard) | Plays when pressing a key on the virtual keyboard.                   |
| `deck_ui_volume.wav`             | Volume change                | Plays when exiting the slider on the Settings > Audio > Output page. |

### Modal

| Filename                 | Description   | Condition                   |
| ------------------------ | ------------- | --------------------------- |
| `deck_ui_hide_modal.wav` | Modal hiding  | Plays when a modal closes.  |
| `deck_ui_show_modal.wav` | Modal showing | Plays when a modal appears. |

## Unused Sounds

| Filename                              | Description                                                                 |
| ------------------------------------- | --------------------------------------------------------------------------- |
| `bumper_end.wav`                      | Presumably a "close" or "dismiss" sound.                                    |
| `confirmation_negative.wav`           | Presumably a sound used when turning something off.                         |
| `confirmation_positive.wav`           | Presumably a sound used when turning something on.                          |
| `deck_ui_message_toast.wav`           | Presumably a toast or notification of some sort.                            |
| `deck_ui_misc_01.wav`                 | Unknown                                                                     |
| `deck_ui_misc_08.wav`                 | Unknown                                                                     |
| `deck_ui_tile_scroll.wav`             | Possibly an unused sound meant for scrolling game tiles on the Library page |
| `pop_sound.wav`                       | Unknown                                                                     |
| `steam_at_mention.m4a`                | Possibly a Steam chat room mentioned sound?                                 |
| `steam_chatroom_notification.m4a`     | Possibly an unused Steam chat room sound?                                   |
| `timer_expired_alarm.wav`             | Possibly from an unused timer feature?                                      |
| `ui_steam_message_old_smooth.m4a`     | Steam friend message sound                                                  |
| `ui_steam_smoother_friend_join.m4a`   | Unknown                                                                     |
| `ui_steam_smoother_friend_online.m4a` | Unknown                                                                     |