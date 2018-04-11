# CSS Guide - pseudo-elements
 
-------------

&lt;input type="search"&gt;
-------------

```css
input[type=search]::-webkit-search-cancel-button

input[type=search]::-webkit-search-cancel-button:after

input[type=search]::-webkit-search-decoration

input[type=search]::-webkit-search-results-decoration

input[type=search]::-webkit-search-results-button

input[type=search]::-webkit-textfield-decoration-container
```


&lt;input type="file"&gt;
-------------

```css
input[type=file]::-ms-browse

input[type=file]::-webkit-file-upload-button

input[type=file]:focus::-webkit-file-upload-button

input[type=file]:active::-webkit-file-upload-button

input[type=file]:active:disabled::-webkit-file-upload-button

input[type=file] > input[type=button]::-moz-focus-inner
```

&lt;input type="range"&gt;
-------------

```css
input[type=range]::-webkit-slider-container

input[type=range]::-webkit-media-slider-container

input[type=range]::-webkit-slider-runnable-track

input[type=range]:focus::-webkit-slider-runnable-track

input[type=range]::-webkit-slider-thumb

input[type=range]::-webkit-slider-thumb:before

input[type=range]::-webkit-slider-thumb:after

input[type=range]:active::-webkit-slider-thumb

input[type=range]:hover::-webkit-slider-thumb:before

input[type=range]:hover::-webkit-slider-thumb:after

input[type=range]:focus::-webkit-slider-thumb:before

input[type=range]:focus::-webkit-slider-thumb:after

input[type=range]:disabled::-webkit-slider-thumb:before

input[type=range]:disabled::-webkit-slider-thumb:after

input[type=range]::-webkit-media-slider-thumb

input[type=range]:disabled::-webkit-slider-thumb

input[type=range]:hover::-webkit-slider-thumb

input[type=range]:focus::-webkit-slider-thumb

input[type=range]::-webkit-color-swatch-wrapper

input[type=range]::-webkit-color-swatch

input[type=range]::-moz-range-track

input[type=range][orient=vertical]::-moz-range-track

input[type=range]:focus::-moz-range-track

input[type=range]::-moz-range-progress

input[type=range]::-moz-range-thumb

input[type=range]:focus::-moz-range-thumb

input[type=range]:focus::-moz-range-thumb:before

input[type=range]:focus::-moz-range-thumb:after

input[type=range]::-moz-focus-outer

input[type=range]::-ms-fill-lower

input[type=range]::-ms-fill-upper

input[type=range]::-ms-ticks-before

input[type=range]::-ms-ticks-after

input[type=range]::-ms-thumb

input[type=range]::-ms-thumb:hover

input[type=range]::-ms-track

input[type=range]:focus::-ms-track

input[type=range]::ms-tooltip
```


&lt;input type="time"&gt;
-------------

```css
input[type=time]::-ms-clear

input[type=time]::-webkit-clear-button
```


&lt;input type="date"&gt;
-------------

```css
input[type=date]::-webkit-datetime-edit

input[type=date]::-webkit-datetime-edit-fields-wrapper

input[type=date]::-webkit-datetime-edit-text

input[type=date]::-webkit-datetime-edit-month-field

input[type=date]::-webkit-datetime-edit-day-field

input[type=date]::-webkit-datetime-edit-year-field

input[type=date]::-webkit-inner-spin-button

input[type=date]::-webkit-calendar-picker-indicator

input[type=date]::-webkit-clear-button
```


&lt;input type="color"&gt;
-------------

```css
input[type=color]::-webkit-color-swatch

input[type=color]::-webkit-color-swatch-wrapper

input[type=color]::-moz-color-swatch

input[type=color]::-moz-focus-inner
```


&lt;input type="number"&gt;
-------------

```css
input[type=number]::-webkit-textfield-decoration-container

input[type=number]::-webkit-textfield-decoration-container:before

input[type=number]::-webkit-textfield-decoration-container:after

input[type=number]::-webkit-inner-spin-button

input[type=number]::-webkit-outer-spin-button

input[type=number]::-moz-number-wrapper

input[type=number]::-moz-number-text

input[type=number]::-moz-number-spin-box

input[type=number]::-moz-number-spin-up

input[type=number]::-moz-number-spin-down
```


&lt;input type="checkbox"&gt;
-------------

```css
input[type=checkbox]::-ms-check
```


&lt;input type="radio"&gt;
-------------

```css
input[type=radio]::-ms-check
```


&lt;input type="text"&gt;
-------------

```css
input[type=text]::-ms-value

input[type=text]::-ms-clear
```


&lt;input type="password"&gt;
-------------

```css
input[type=password]::-ms-reveal

input[type=password]::-ms-value
```


&lt;input type="reset"&gt;
-------------

```css
input[type=reset]::-moz-focus-inner
```


&lt;input type="submit"&gt;
-------------

```css
input[type=submit]::-moz-focus-inner
```


&lt;input type="button"&gt;
-------------

```css
input[type=button]::-moz-focus-inner
```


placeholder Attribute
-------------

```css
::-moz-placeholder

:-ms-input-placeholder

::-webkit-input-placeholder
```


&lt;keygen&gt;
-------------

```css
::-webkit-keygen-select
```


&lt;input&gt;
-------------

```css
input:valid + label::after

input:invalid + label::after

input::-webkit-input-list-button

input::-webkit-input-speech-button

input::-webkit-textfield-decoration-container

input::-webkit-calendar-picker-indicator

input::-moz-placeholder

input::-moz-focus-inner

input::-ms-clear
```


&lt;button&gt;
-------------

```css
button::-moz-focus-inner
```


&lt;select&gt;
-------------

```css
select::-ms-expand
```


&lt;details&gt;
-------------

```css
details::-webkit-details-marker
```


&lt;summary&gt;
-------------

```css
summary::-webkit-details-marker
```


&lt;meter&gt;
-------------

```css
meter::-webkit-meter

meter::-webkit-meter-horizontal-bar

meter::-webkit-meter-vertical-bar

meter::-webkit-meter-horizontal-optimum-value

meter::-webkit-meter-horizontal-suboptimal-value

meter::-webkit-meter-horizontal-even-less-good-value

meter::-webkit-meter-vertical-optimum-value

meter::-webkit-meter-vertical-suboptimal-value

meter::-webkit-meter-vertical-even-less-good-value

meter::-moz-meter-bar

meter:-moz-meter-optimum::-moz-meter-bar

meter:-moz-meter-sub-optimum::-moz-meter-bar

meter:-moz-meter-sub-sub-optimum::-moz-meter-bar
```

```css
-webkit-appearance: continuous-capacity-level-indicator;
-webkit-appearance: discrete-capacity-level-indicator;
-webkit-appearance: relevancy-level-indicator;
-webkit-appearance: rating-level-indicator;
```


&lt;progress&gt;
-------------

```css
progress::-webkit-progress-bar

progress::-webkit-progress-value

progress::-webkit-progress-bar-value

progress::-moz-progress-bar

progress::-ms-fill
```


&lt;textarea&gt;
-------------

```css
textarea::-webkit-resizer

textarea::-webkit-resizer:window-inactive

textarea::-webkit-input-placeholder

textarea::-moz-placeholder
```

```css
textarea {
  resize: none;
}
```


&lt;img&gt;
-------------
```css
img::-webkit-image-inner-element
```


&lt;p&gt;
-------------

```css
p::after

p::before

p::first-letter

p::first-line

p::selection
```


&lt;video&gt;
-------------

```css
video::-webkit-media-controls-panel

video::-webkit-media-controls-play-button

video::-webkit-media-controls-volume-slider-container

video::-webkit-media-controls-volume-slider

video::-webkit-media-controls-mute-button

video::-webkit-media-controls-timeline

video::-webkit-media-controls-current-time-display

video::-webkit-full-page-media::-webkit-media-controls-panel

video::-webkit-media-controls-timeline-container

video::-webkit-media-controls-time-remaining-display

video::-webkit-media-controls-seek-back-button

video::-webkit-media-controls-seek-forward-button

video::-webkit-media-controls-fullscreen-button

video::-webkit-media-controls-overlay-play-button

video::-webkit-media-controls-rewind-button

video::-webkit-media-controls-return-to-realtime-button

video::-webkit-media-controls-toggle-closed-captions-button
```


&lt;audio&gt;
-------------

```css
audio::-webkit-media-controls-panel

audio::-webkit-media-controls-mute-button

audio::-webkit-media-controls-play-button

audio::-webkit-media-controls-timeline-container

audio::-webkit-media-controls-current-time-display

audio::-webkit-media-controls-time-remaining-display

audio::-webkit-media-controls-timeline

audio::-webkit-media-controls-volume-slider-container

audio::-webkit-media-controls-volume-slider

audio::-webkit-media-controls-seek-back-button

audio::-webkit-media-controls-seek-forward-button

audio::-webkit-media-controls-fullscreen-button

audio::-webkit-media-controls-rewind-button

audio::-webkit-media-controls-return-to-realtime-button

audio::-webkit-media-controls-toggle-closed-captions-button
```


Scrollbar
-------------

```css
::-webkit-scrollbar

::-webkit-scrollbar-button

::-webkit-scrollbar-button:disabled

::-webkit-scrollbar-button:double-button:horizontal:end:decrement

::-webkit-scrollbar-button:double-button:horizontal:end:increment

::-webkit-scrollbar-button:double-button:horizontal:end:increment:corner-present

::-webkit-scrollbar-button:double-button:horizontal:start:decrement

::-webkit-scrollbar-button:double-button:horizontal:start:increment

::-webkit-scrollbar-button:double-button:vertical:end:decrement

::-webkit-scrollbar-button:double-button:vertical:end:increment

::-webkit-scrollbar-button:double-button:vertical:end:increment:corner-present

::-webkit-scrollbar-button:double-button:vertical:start:decrement

::-webkit-scrollbar-button:double-button:vertical:start:increment

::-webkit-scrollbar-button:end

::-webkit-scrollbar-button:end:decrement

::-webkit-scrollbar-button:end:increment

::-webkit-scrollbar-button:horizontal

::-webkit-scrollbar-button:horizontal:decrement

::-webkit-scrollbar-button:horizontal:decrement:active

::-webkit-scrollbar-button:horizontal:decrement:hover

::-webkit-scrollbar-button:horizontal:decrement:window-inactive

::-webkit-scrollbar-button:horizontal:end

::-webkit-scrollbar-button:horizontal:end:decrement

::-webkit-scrollbar-button:horizontal:end:increment

::-webkit-scrollbar-button:horizontal:end:increment:corner-present

::-webkit-scrollbar-button:horizontal:increment

::-webkit-scrollbar-button:horizontal:increment:active

::-webkit-scrollbar-button:horizontal:increment:hover

::-webkit-scrollbar-button:horizontal:increment:window-inactive

::-webkit-scrollbar-button:horizontal:start

::-webkit-scrollbar-button:horizontal:start:decrement

::-webkit-scrollbar-button:horizontal:start:increment

::-webkit-scrollbar-button:start

::-webkit-scrollbar-button:start:decrement`

::-webkit-scrollbar-button:start:increment

::-webkit-scrollbar-button:vertical

::-webkit-scrollbar-button:vertical:decrement

::-webkit-scrollbar-button:vertical:decrement:active

::-webkit-scrollbar-button:vertical:decrement:hover

::-webkit-scrollbar-button:vertical:decrement:window-inactive

::-webkit-scrollbar-button:vertical:end

::-webkit-scrollbar-button:vertical:end:decrement

::-webkit-scrollbar-button:vertical:end:increment

::-webkit-scrollbar-button:vertical:end:increment:corner-present

::-webkit-scrollbar-button:vertical:increment

::-webkit-scrollbar-button:vertical:increment:active

::-webkit-scrollbar-button:vertical:increment:hover

::-webkit-scrollbar-button:vertical:increment:window-inactive

::-webkit-scrollbar-button:vertical:start

::-webkit-scrollbar-button:vertical:start:decrement

::-webkit-scrollbar-button:vertical:start:increment

::-webkit-scrollbar-corner

::-webkit-scrollbar-corner:window-inactive

::-webkit-scrollbar-thumb

::-webkit-scrollbar-thumb:horizontal

::-webkit-scrollbar-thumb:horizontal:active

::-webkit-scrollbar-thumb:horizontal:hover

::-webkit-scrollbar-thumb:horizontal:window-inactive

::-webkit-scrollbar-thumb:vertical

::-webkit-scrollbar-thumb:vertical:active

::-webkit-scrollbar-thumb:vertical:hover

::-webkit-scrollbar-thumb:vertical:window-inactive

::-webkit-scrollbar-track

::-webkit-scrollbar-track-piece

::-webkit-scrollbar-track-piece:disabled

::-webkit-scrollbar-track-piece:end

::-webkit-scrollbar-track-piece:horizontal:decrement

::-webkit-scrollbar-track-piece:horizontal:decrement:active

::-webkit-scrollbar-track-piece:horizontal:decrement:hover

::-webkit-scrollbar-track-piece:horizontal:end

::-webkit-scrollbar-track-piece:horizontal:end:corner-present

::-webkit-scrollbar-track-piece:horizontal:end:double-button

::-webkit-scrollbar-track-piece:horizontal:end:no-button

::-webkit-scrollbar-track-piece:horizontal:end:no-button:corner-present

::-webkit-scrollbar-track-piece:horizontal:end:single-button

::-webkit-scrollbar-track-piece:horizontal:increment

::-webkit-scrollbar-track-piece:horizontal:increment:active

::-webkit-scrollbar-track-piece:horizontal:increment:hover

::-webkit-scrollbar-track-piece:horizontal:start

::-webkit-scrollbar-track-piece:horizontal:start:double-button

::-webkit-scrollbar-track-piece:horizontal:start:no-button

::-webkit-scrollbar-track-piece:horizontal:start:single-button

::-webkit-scrollbar-track-piece:start

::-webkit-scrollbar-track-piece:vertical:decrement

::-webkit-scrollbar-track-piece:vertical:decrement:active

::-webkit-scrollbar-track-piece:vertical:decrement:hover

::-webkit-scrollbar-track-piece:vertical:end

::-webkit-scrollbar-track-piece:vertical:end:corner-present

::-webkit-scrollbar-track-piece:vertical:end:double-button

::-webkit-scrollbar-track-piece:vertical:end:no-button

::-webkit-scrollbar-track-piece:vertical:end:no-button:corner-present

::-webkit-scrollbar-track-piece:vertical:end:single-button

::-webkit-scrollbar-track-piece:vertical:increment

::-webkit-scrollbar-track-piece:vertical:increment:active

::-webkit-scrollbar-track-piece:vertical:increment:hover

::-webkit-scrollbar-track-piece:vertical:start

::-webkit-scrollbar-track-piece:vertical:start:double-button

::-webkit-scrollbar-track-piece:vertical:start:no-button

::-webkit-scrollbar-track-piece:vertical:start:single-button

::-webkit-scrollbar-track:disabled

::-webkit-scrollbar-track:horizontal

::-webkit-scrollbar-track:horizontal:disabled

::-webkit-scrollbar-track:horizontal:disabled:corner-present

::-webkit-scrollbar-track:vertical:disabled

::-webkit-scrollbar-track:vertical:disabled:corner-present

::-webkit-scrollbar:horizontal

::-webkit-scrollbar:horizontal:corner-present

::-webkit-scrollbar:horizontal:window-inactive

::-webkit-scrollbar:vertical

::-webkit-scrollbar:vertical:corner-present

::-webkit-scrollbar:vertical:window-inactive

::-webkit-textfield-decoration-container
```


Form validation message-bubbe
-------------

```css
::-webkit-validation-bubble

::-webkit-validation-bubble-arrow

::-webkit-validation-bubble-arrow-clipper

::-webkit-validation-bubble-heading

::-webkit-validation-bubble-message

::-webkit-validation-bubble-text-block
```

Source
-------------
* https://developer.mozilla.org/en-US/docs/Web/CSS/Pseudo-elements