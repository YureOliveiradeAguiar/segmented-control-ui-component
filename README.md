[![Demo Video](demo.png)](https://github.com/user/repo/assets/12345678/v1.0.0.mp4)

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
