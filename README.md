# MiraBox_SyncRGB

The open-source repository for MiraBox SyncRGB.

This project adapts and maintains code from upstream open-source projects. It brings together the RGB control service and low-level driver sources used by MiraBox SyncRGB, making it easier for developers to review, build, debug, and improve the software.

## Repository Structure

| Directory | Description | Upstream Project |
| --- | --- | --- |
| `RGBServer` | An OpenRGB-based RGB device control service with custom features | [OpenRGB](https://gitlab.com/CalcProgrammer1/OpenRGB) |
| `PawnIO` | Low-level input/output driver source code for Windows | [PawnIO](https://pawnio.eu) |

For feature details, build instructions, and development documentation, see the `README.md` and related documentation in each subdirectory.

## Contributing

Issues and pull requests are welcome. Contributions that improve device support, compatibility, and the overall user experience are greatly appreciated.

## License

Each component in this repository retains the open-source license of its respective upstream project. Before using, modifying, or distributing the code, please review the license files and copyright notices in the corresponding subdirectories.
