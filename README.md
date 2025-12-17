<img src="demonstration.gif" width="350px" alt="Demo">

<strong>How to use</strong><br>
```html
<segmented-control
    [options]="options"
    [value]="selectedOption"
    (valueChanged)="selectedOption = $event"
/>
```

<strong>Example inputs</strong><br>
```html
options: SegmentedControlOption[]= [
    {label:"low", value: 1},
    {label:"medium", value: 2},
    {label:"high", value: 3}
];
```
  <li> [value]="selectedOption" //the current value </li>
</ul>
