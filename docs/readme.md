# Design Toolbox modal

Modal component of the TenForce design toolbox.

## CSS

This component is using [one](https://github.com/tenforce/design-toolbox-modal/blob/master/docs/sass/toolbox-modal.scss) CSS file.

## HTML structure

The Design documentation was built in Jekyll using SASS and Liquid. Most of the modals just use a table inside them. A simple error modal for example:

``` html
<div class="toolbox-modal" id="ms-error">
  <div class="toolbox-table">
    <div class="toolbox-table__row">
      <ul class="toolbox-table__rowInner toolbox-table__rowInner--custom">
        <li class="toolbox-table__cell">
          <div class="toolbox-table__cellInner">
            <div class="toolbox-note toolbox-note--error">
              <p>Item could not be selected. <a href="#" class="link link--primary">Read more</a></p>
            </div>
          </div>
        </li>
      </ul>
    </div>
  </div>
</div>
```

For a more complex example, see the [columnpicker]([raw](https://github.com/tenforce/design-toolbox-modal/blob/master/docs/_includes/popups/toolbox-modal-columnpicker.html).

## Usage
### Links to CSS files
- main CSS
  - [built](https://tenforce.github.io/design-toolbox-modal/sass/toolbox-modal.css)
  - [raw](https://github.com/tenforce/design-toolbox-modal/blob/master/docs/sass/toolbox-modal.scss)

### Jekyll
Add [the content of this file](https://github.com/tenforce/design-toolbox-modal/tree/master/docs/import/include-modal.html) to the another Jekyll project to include files from this project.

## Dependencies
- [Tailwind v0.6.4](https://tailwindcss.com)
- [TenForce default CSS](https://github.com/tenforce/design-toolbox-default-css)
- [jQuery (for javascript)](https://jquery.com)
