## Checklist for testing Vim Vixen

### Keybindings in JSON settings

Test operations with default key maps.

#### Misc

- [ ] Toggle enabled/disabled of plugin bu <kbd>Shift</kbd>+<kbd>Esc</kbd>
- [ ] Hide error and info console by <kbd>Esc</kbd>
- [ ] Vim-Vixen icons changes on <kbd>Shift</kbd>+<kbd>Esc</kbd>
- [ ] Add-on is enabled and disabled by clicking the indicator on the tool bar.
- [ ] The indicator changed on selected tab changed (changes add-on enabled)
- [ ] Notify to users on add-on updated at first time.
- [ ] Reopen tab on *only current window* by <kbd>u</kbd>

### Properties

- [ ] Toggle smooth scroll by `:set smoothscroll` and `:set nosmoothscroll`
- [ ] Configure smooth scroll by settings `"smoothscroll": true` and `"smoothscroll": false`

### Settings

#### Form Settings

##### Updating

- [ ] keymap settings are applied to open tabs without reload
- [ ] search settings are applied to open tabs without reload
