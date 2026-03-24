# Pinout / Interface Table

| Type      | Pin Name  | Voltage   |
|-----------|----------|----------|
| Power     | Logic_VDD | 1.2V      |
| Ground    | VSS/GND   | 0V        |
| Analog    | VHLS      | 5V        |
| Analog    | VBAT      | 5V        |
| Analog    | VBAT2     | < 5V      |
| Digital I | Vs        | 1.2V      |
| Analog    | VH        | 0-10V     |
| Analog    | Vddls     | 3.3V      |
| Digital I | IN        | 1.2V      |
| Analog    | Vout      | 0-10V     |

## Verification Status

- **DRC:** Only Filler and Density Errors (Minimal/Maximal)
- **LVS:** Clean, but could not export log so placed .spice instead
