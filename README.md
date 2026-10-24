# mister-utils

Standalone MiSTer / DE10-Nano helpers used by DreamSTer, moved out of minicast.

- [`mem_wc`](mem_wc/) — kernel module exposing `/dev/mem_wc`, a write-combining `/dev/mem`.
- [`load_fpga_bitstream`](load_fpga_bitstream/) — minimal FPGA bitstream (`.rbf`) loader.
- [`setup_hdmi`](setup_hdmi/) — minimal ADV7513 HDMI transmitter setup, fixed at 1920x1080.

Each directory has its own README with build instructions.
