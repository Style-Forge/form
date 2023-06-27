# style-forge.form
This is styling of all input fields

[![npm](https://img.shields.io/npm/v/style-forge.form)][npm-link]
[![npm](https://img.shields.io/npm/dm/style-forge.form)][npm-link]

Form CSS for [style-forge](https://www.npmjs.com/package/style-forge)

<hr />

## Installation
```bash
npm install style-forge.form
```
```bash
yarn add style-forge.form
```

<hr />

<details>
<summary><strong><code>Input</code></strong></summary>

```html
<div class="input">
  <input type="text" placeholder="text" />
  <label>text</label>
  <span class="shape"></span>
</div>
```
```html
<div class="input">
  <input type="search" placeholder="search" />
  <label>search</label>
  <span class="shape"></span>
</div>
```
```html
<div class="input">
  <input type="email" placeholder="email" />
  <label>email</label>
  <span class="shape"></span>
</div>
```
```html
<div class="input">
  <input type="number" placeholder="number" />
  <label>number</label>
  <span class="shape"></span>
</div>
```
```html
<div class="input">
  <input type="password" placeholder="password" autocomplete="off" />
  <label>password</label>
  <span class="shape"></span>
</div>
```
```html
<div class="input">
  <input type="tel" placeholder="tel" />
  <label>tel</label>
  <span class="shape"></span>
</div>
```
```html
<div class="input">
  <input type="url" placeholder="url" />
  <label>url</label>
  <span class="shape"></span>
</div>
```
```html
<input type="color" />
```
```html
<input type="file" />
```
```html
<input type="image" src="" alt="" />
```
```html
<input type="range" />
```

Loading
```html
<div class="input">
  <input type="text" placeholder="text" loading />
  <label>text</label>
  <span class="shape"></span>
</div>
```

Required
```html
<div class="input">
  <input type="text" placeholder="text" required />
  <label>text</label>
  <span class="shape"></span>
</div>
```

Readonly
```html
<div class="input">
  <input type="text" placeholder="text" value="Text readonly" readonly />
  <label>text</label>
  <span class="shape"></span>
</div>
```

Disabled
```html
<div class="input">
  <input type="text" placeholder="text" value="Text disabled" disabled />
  <label>text</label>
  <span class="shape"></span>
</div>
```

Error
```html
<div class="input error">
  <input type="text" placeholder="text" required />
  <label>text</label>
  <span class="shape"></span>
</div>
<div class="error">This input needed fill</div>
```
</details>

<details>
<summary><strong><code>Button</code></strong></summary>

```html
<input class="button" type="button" value="button" />
```
```html
<input class="button" type="reset" />
```
```html
<input class="button" type="submit" />
```
```html
<button class="button" type="button">button</button>
```
```html
<button class="button" type="submit">submit</button>
```
```html
<button class="button" type="reset">reset</button>
```

Loading
```html
<input class="button" type="button" value="button" loading />
```
```html
<button class="button" type="button" loading>button</button>
```

Disabled
```html
<input class="button" type="button" value="button" disabled />
```
```html
<button class="button" type="button" disabled>button</button>
```
</details>

<details>
<summary><strong><code>Checkbox</code></strong></summary>

```html
<label class="checkbox">
  <input type="checkbox" checked>
  Text
</label>
```

Loading
```html
<label class="checkbox" loading>
  <input type="checkbox" checked>
  Text
</label>
```

Disabled
```html
<label class="checkbox">
  <input type="checkbox" checked disabled>
  Text
</label>
```
</details>

<details>
<summary><strong><code>Radio</code></strong></summary>

```html
<label class="radio">
  <input type="radio" name="radio" checked />
  First
</label>
<label class="radio">
  <input type="radio" name="radio" disabled />
  Second
</label>
```

Loading
```html
<label class="radio" loading>
  <input type="radio" name="radio" checked />
  First
</label>
<label class="radio">
  <input type="radio" name="radio" disabled />
  Second
</label>
```
</details>

<details>
<summary><strong><code>Select</code></strong></summary>

```html
<select class="select">
  <option value="o1" disabled>First</option>
  <option value="o2">Second</option>
  <option value="o3">Third</option>
  <option value="o4">Fourth</option>
</select>
```

Loading
```html
<select class="select" loading>
  <option value="o1" disabled>First</option>
  <option value="o2">Second</option>
  <option value="o3">Third</option>
  <option value="o4">Fourth</option>
</select>
```

Disabled
```html
<select class="select" disabled>
  <option value="o1">First</option>
  <option value="o2">Second</option>
  <option value="o3">Third</option>
  <option value="o4">Fourth</option>
</select>
```

Multiple
```html
<select class="select" multiple>
  <option value="o1" disabled>First</option>
  <option value="o2">Second</option>
  <option value="o3">Third</option>
  <option value="o4">Fourth</option>
</select>
```

Group
```html
<select class="select">
  <optgroup label="Group One" disabled>
    <option value="o1">First</option>
    <option value="o2">Second</option>
  </optgroup>
  <optgroup label="Group Two">
    <option value="o3" disabled>Third</option>
    <option value="o4">Fourth</option>
  </optgroup>
</select>
```
</details>

<details>
<summary><strong><code>Switch</code></strong></summary>

```html
<label class="switch">
  <input type="checkbox" checked>
  Remember me
</label>
```

Loading
```html
<label class="switch" loading>
  <input type="checkbox" checked>
  Remember me
</label>
```
</details>

<details>
<summary><strong><code>Switch [multiple Radio]</code></strong></summary>

```html
<div class="switch" multiple>
  <div class="switch-toggle">
    <label><input name="state" type="radio" /><span>-1</span></label>
    <label><input name="state" type="radio" /><span>Off</span></label>
    <label disabled><input name="state" type="radio" checked disabled /><span>Default</span></label>
    <label><input name="state" type="radio" /><span>On</span></label>
  </div>
  <div class="switch-label">triple and more...</div>
</div>
```

Vertical
```html
<div class="switch" multiple>
  <div class="switch-toggle" vert>
    <label><input name="state" type="radio" /><span>-1</span></label>
    <label><input name="state" type="radio" /><span>Off</span></label>
    <label disabled><input name="state" type="radio" checked disabled /><span>Default</span></label>
    <label><input name="state" type="radio" /><span>On</span></label>
  </div>
  <div class="switch-label">triple and more...</div>
</div>
```

Loading
```html
<div class="switch" multiple>
  <div class="switch-toggle" loading>
    <label><input name="state" type="radio" /><span>-1</span></label>
    <label><input name="state" type="radio" /><span>Off</span></label>
    <label disabled><input name="state" type="radio" checked disabled /><span>Default</span></label>
    <label><input name="state" type="radio" /><span>On</span></label>
  </div>
  <div class="switch-label">triple and more...</div>
</div>
```
</details>

<details>
<summary><strong><code>Switch [multiple Checkbox]</code></strong></summary>

```html
<div class="switch" multiple>
  <div class="switch-toggle">
    <label><input name="state" type="checkbox" /><span>-1</span></label>
    <label><input name="state" type="checkbox" /><span>Off</span></label>
    <label disabled><input name="state" type="checkbox" disabled /><span>Default</span></label>
    <label><input name="state" type="checkbox" /><span>On</span></label>
  </div>
  <div class="switch-label">triple and more...</div>
</div>
```

Vertical
```html
<div class="switch" multiple>
  <div class="switch-toggle" vert>
    <label><input name="state" type="checkbox" /><span>-1</span></label>
    <label><input name="state" type="checkbox" /><span>Off</span></label>
    <label disabled><input name="state" type="checkbox" disabled /><span>Default</span></label>
    <label><input name="state" type="checkbox" /><span>On</span></label>
  </div>
  <div class="switch-label">triple and more...</div>
</div>
```

Loading
```html
<div class="switch" multiple>
  <div class="switch-toggle" loading>
    <label><input name="state" type="checkbox" /><span>-1</span></label>
    <label><input name="state" type="checkbox" /><span>Off</span></label>
    <label disabled><input name="state" type="checkbox" disabled /><span>Default</span></label>
    <label><input name="state" type="checkbox" /><span>On</span></label>
  </div>
  <div class="switch-label">triple and more...</div>
</div>
```
</details>

<details>
<summary><strong><code>textarea</code></strong></summary>

```html
<textarea class="textarea" placeholder="textarea"></textarea>
```

Required
```html
<textarea class="textarea" placeholder="textarea" required></textarea>
```

Readonly
```html
<textarea class="textarea" placeholder="textarea readonly" readonly></textarea>
```

Disabled
```html
<textarea class="textarea" placeholder="textarea disabled" disabled></textarea>
```

Loading
```html
<textarea class="textarea" placeholder="textarea disabled" loading></textarea>
```
</details>

<details>
<summary><strong><code>time</code></strong></summary>

```html
<div class="input">
  <input type="time" value="01:00" />
  <label>time</label>
  <span class="shape"></span>
</div>
```
```html
<div class="input">
  <input type="week" value="2023-W01" />
  <label>week</label>
  <span class="shape"></span>
</div>
```
```html
<div class="input">
  <input type="month" value="2023-01" />
  <label>month</label>
  <span class="shape"></span>
</div>
```
```html
<div class="input">
  <input type="date" value="2023-01-01" />
  <label>date</label>
  <span class="shape"></span>
</div>
```
```html
<div class="input">
  <input type="datetime-local" value="2023-01-01T01:00" />
  <label>datetime-local</label>
  <span class="shape"></span>
</div>
```
</details>

<details>
<summary><strong><code>datalist</code></strong></summary>

```html
<div class="input">
  <input list="browsers" name="browser" placeholder="browsers" />
  <label>browsers</label>
  <span class="shape"></span>
  <datalist id="browsers">
    <option label="IE">Internet Explorer</option>
    <option label="FF">Firefox</option>
    <option label="Chrome">Google</option>
    <option label="Opera">Mini</option>
    <option label="Safari">Apple</option>
  </datalist>
</div>
```
</details>

<hr />

## License [![NPM](https://img.shields.io/npm/l/style-forge.form)](https://github.com/Sarmaged/style-forge.form/blob/main/LICENSE)

Distributed under the MIT License. See `LICENSE` for more information.

[npm-link]: https://www.npmjs.com/package/style-forge.form
[github-link]: https://github.com/Sarmaged/style-forge.form
