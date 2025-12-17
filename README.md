[![Demo Video](./assets/demo.png)](https://github.com/YureOliveiradeAguiar/segmented-control-ui-component/issues/1#issue-3739239136)

<strong>How to use</strong><br>
<segmented-control
    [options]="options"
    [value]="selectedOption"
    (valueChanged)="selectedOption = $event"
/>

<strong>Example inputs</strong><br>
<ul>
  <li>
      options: SegmentedControlOption[]= [
      {label:"abracadabra", value: 69},
      {label:"simSalomão", value: 420},
      {label:"teste", value: 123}
    ];
  </li>
  <li> [value]="selectedOption" //the current value </li>
</ul>
