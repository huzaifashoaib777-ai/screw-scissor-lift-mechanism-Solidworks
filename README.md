# Screw Scissor Lift Mechanism (SolidWorks)

[Screw%20scissor%20lift%20mechanism.jpg]

A complete 3D CAD assembly of a **two-stage screw-driven scissor lift mechanism** modeled and assembled in **SolidWorks** (MMGS units). The assembly combines 6 unique native `.SLDPRT` components (25 total instances) into a symmetric dual X-stage linkage driven by a central lead screw and handwheel.

## Technical Overview

| Parameter | Specification |
| :--- | :--- |
| **Mechanism Type** | Two-Stage Screw-Driven Scissor Lift |
| **Platform Footprint** | `500.0 × 300.0 mm` (60 mm flanged U-channels) |
| **Scissor Link Length** | `350.0 mm` overall (`320.0 mm` pin-to-pin, `5.0 mm` thick) |
| **Guide Slot Travel** | `250.0 mm` (`Ø10 mm` slot width on Base & Top platforms) |
| **Drive Mechanism** | `Ø15.0 mm` Lead Screw with `Ø120.0 mm` 5-Spoke Handwheel |
| **Unit System** | MMGS (Millimeter, Gram, Second) |
| **Total Components** | 6 unique parts (25 instances in assembly) |

## Bill of Materials (BOM)

| File | Component Name | Qty | Key Dimensions (mm) |
| :--- | :--- | :---: | :--- |
| `Part1.sldprt` | Base & Top Platform | 2 | `300 × 60 × 500`, `250 mm` horizontal slots, `Ø10` pivot holes |
| `Part2.sldprt` | Scissor Arm / Link | 8 | `350 × 30 × 5`, 3× `Ø10` holes (`320 mm` pin-to-pin) |
| `Part3.sldprt` | Trunnion Cross-Bar | 2 | `304 mm` long, `Ø40` barrel, `Ø10` end pins, `Ø15` center bore |
| `Part04.sldprt` | Lead Screw & Handwheel | 1 | `361.8 mm` long, `Ø15` screw shaft, `Ø120` handwheel |
| `Part5.SLDPRT` | Slider Pin | 4 | `30 mm` long, `Ø10` shaft, `Ø20` cap |
| `Part6.sldprt` | Pivot Pin | 8 | `20 mm` long, `Ø10` cylindrical pin |

## How to Open & Simulate

1. Download or clone all files into a single local folder (keep all `.SLDPRT` files in the same directory as the `.SLDASM` file).
2. Open `Screw_Scissor_Lift_Assembly.SLDASM` in **SolidWorks**.
3. Drag the **Top Platform** vertically (or run **Motion Study 1** with a linear/rotary motor) to observe the scissor linkage raising and lowering.

## License

Shared for educational and CAD portfolio purposes under the MIT License.
