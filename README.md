<img src="demonstration.gif" width="350px" alt="Demo">

The <strong>segmented-control (reactive forms)</strong> is the adapted version for reactive form made with CVA.<br>
The other version is ideal for filters, view toggles and such.

<strong>How to use</strong><br>
```html
<segmented-control
    [options]="options"
    [value]="selectedOption"
    (valueChanged)="selectedOption = $event"
/>
```
<li> [value]="selectedOption" // Sets the current value </li>

<strong>Example inputs</strong><br>
```html
options: SegmentedControlOption[]= [
    {label:"low", value: 1},
    {label:"medium", value: 2},
    {label:"high", value: 3}
];
```
