
# Hyper Paste

This little [Alfred App](https://www.alfredapp.com) workflow adds a couple new global paste functions to macOS. 

## Uses

**Penultimate Paste (pasting second last item)** - this function allows you to paste the second last thing in your clipboard (easier than triggering clipboard history, then ⌘+2). This promotes that item to the most recent item in your clipboard. There are several uses for this:
  - if you thought you were pasting a helpful code snippet, but in fact pasted a link to a cat video, this is your mulligan! _(I can't be the only person this happens to constantly)_
  - if you needed to alternately paste, for example your name and email into several documents repeatedly.
  - when you get used to this being here you start to actively plan on using it; fearlessly and constantly copying multiple things to clipboard.

**Paste & Purge (paste then remove)** - in addition to pasting your clipboard contents into your active application, Alfred afterwards removes it from the clipboard entirely (this is done with timed delays which is a bit hacky, but is the only way to pull this off). Use cases: 
  - If you want a handy way to remove something from your clipboard (could be stealth reasons, or to clean up your current clipboard for a 'mass paste').
  - Mass pasting: being able to paste many items without fussing about navigating through clipboard history with arrow keys or ⌘+numbers. For example; if I have a dozen tabs open that I need to send the URLs of, I can copy+close tab a dozen times, then destructo paste a dozen times and be done with it.

<img src="screenshot-hyperpaste.png" width="1040">
> A screenshot of how I have this workflow configured


## Requirement & Setup

- Requires an Apple computer :S 
- Requires Alfred App v3
- When importing a workflow certain items are empty. Populate the triggering hotkey. You can see in the screenshot that I use Hyper+V and Hyper+B; use what you like. To use Hyper in your hotkey _(command+alt+ctrl+shift)_ you may need an application like [Karabiner Elements](https://github.com/tekezo/Karabiner-Elements) _(at the time of writing Hyper is only functional on beta, [more info](https://github.com/tekezo/Karabiner-Elements/pull/170#issuecomment-308121709))_
- Populate the Key Combos - In the screenshot you can see I use cmd+alt+ctrl+v - find your setting in Alfred: _Features > Clipboard > Viewer hotkey_
