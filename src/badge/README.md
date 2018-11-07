# Badge
The `Badge` component creates a notification badge with a counter and unread alert.

## Demo

<div class="example">
  <div class="header">Example</div>
  <div class="content">
    <tonic-badge></tonic-badge>
    <div class="button-group">
      <span id="add-notification">Add</span>
      <span id="subtract-notification">Subtract</span>
    </div>
  </div>
</div>

## Code

To update the notification count, pass in the `count` property.

#### HTML
```html
<tonic-badge></tonic-badge>
```

#### JS
```js
tonicBadge.reRender(props => ({
  ...props,
  count: `${count}`
}))
```

## Api

### Properties

| Property | Type | Description | Default |
| :--- | :--- | :--- | :--- |
| `id` | *string* | Adds the `id` attribute. | |
| `name` | *string* | Adds the `name` attribute. | |
| `count` | *string* | Updates the `count` property. | `0` |
| `theme` | *string* | Adds a theme color (`light`, `dark` or whatever is defined in your base CSS. | `light` |