# zen

# TrainingTelemetry

External C++ training telemetry and visualization system.

## Technologies

- C++17
- Windows API
- DirectX 11
- Dear ImGui
- CMake
- Shared Memory / IPC

## Modules

- Core: Application lifecycle
- Memory: Authorized telemetry reader
- Renderer: DirectX 11 and ImGui
- Logic: AimAssist mathematics and ESP visualization
- Input: Windows input abstraction
- Data: Player telemetry structures

## Requirements

- Windows 10/11
- Visual Studio 2022
- Windows SDK
- CMake 3.20+
- DirectX 11

## Build

```bash
cmake -S . -B build
cmake --build build --config Release
```

## Purpose

Designed for authorized game-training environments,
custom simulators and telemetry visualization.

## License

MIT
