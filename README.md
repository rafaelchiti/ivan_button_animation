# Reveal button

### CSS

- Include the `reveal_button.css` that contains all the styles required for the
button to work. The classes have been namespaced with `revealButton_` to prevent clashing.

### HTML

The structure required for the button to work can be found in the index.html example.
Or just copy as follows:

```html
<div class="revealButtonContainer" >
  <div class="revealButton_transitioner">
    <div class="revealButton_fullTextBox  js-revealButton_triggerShow">
      <span class="revealButton_fullText">REQUEST INVITE</span>
    </div>
    <div class="revealButton_formBox">
      <input placeholder="Enter info..."  type="text" class="revealButton_inputText js-revealButton_input" />
      <input type="button" class="revealButton_button" value="SEND" />
    </div>
    <span class="revealButton_clear"></span>
  </div>
</div>
```

### How to toggle the animation.

In order to trigger the animation the revealButtonContainer div needs to get the class `show` added. In the demo here we are simply using jquery but this belongs to userland whatever tool that can simply add a class, including vanilla js, will make it.

### Customization

- To change the size just adjust the width or height of the revealButtonContainer div.
