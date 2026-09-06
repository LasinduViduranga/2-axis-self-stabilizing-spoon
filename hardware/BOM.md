# Bill of Materials (BOM)

## Electronics

| Component | Quantity | Specification | Purpose |
|---|---:|---|---|
| Arduino Nano | 1 | ATmega328P-based | Main microcontroller |
| MPU6050 | 1 | 6-axis IMU | Motion sensing |
| SG90 servo motor | 2 | Micro servo | 2-axis actuation |
| LiPo battery | 1 | 7.4 V, 2200 mAh, 2S, 60C | Main power source |
| Power regulation circuit | 1 | Project-specific | Provides suitable regulated supply |
| Connecting wires | As required | — | Electrical connections |

## Mechanical

| Component | Quantity | Specification | Purpose |
|---|---:|---|---|
| 3D-printed spoon structure | 1 | Project-specific | Supports the spoon and servo mechanism |
| Spoon | 1 | Project-specific | End effector |
| Fasteners / hardware | As required | Project-specific | Mechanical assembly |

## Notes

- Verify the required voltage and current for every component before assembly.
- Do not connect a 2S LiPo battery directly to components that are not rated for its voltage.
- Servo motors can produce high transient current. The power circuit should be designed accordingly.
- Replace "project-specific" with exact part numbers/materials if those details are available.

## Recommended additions for reproducibility

If rebuilding this project, record:

- Exact Arduino Nano variant.
- MPU6050 module/model used.
- Servo model and torque specification.
- Voltage regulator / BEC model and current rating.
- Battery connector type.
- 3D-print material.
- Print settings.
- Fastener dimensions.
