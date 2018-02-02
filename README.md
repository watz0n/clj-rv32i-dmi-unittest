A simple unit-test example to transfer RISCV instruction through DMI module and validate test result, 
build this example for [Chisel Learning Journey](https://github.com/librecores/riscv-sodor/wiki/Chisel-Learning-Journey) discussion.

The unit-test code is under `src\test\scala\rv32` directory, and it's simulate [riscv-fesvr](https://github.com/codelec/riscv-fesvr/tree/f9754d8db7d8c1bd659f223017873fb6a25f1257) send commands throught SimDTM.v in [Sodor Project](https://github.com/librecores/riscv-sodor).

* Execute Unit-Test: `bash dmi-unit.sh`
* Clear Unit-Test generate files: `bash unit-clear.sh`

Please let me know if you have any question. I would be available by email `watz0n.tw at gmail.com` or open an issue. Or join [Chisel Learning Journey](https://github.com/librecores/riscv-sodor/wiki/Chisel-Learning-Journey) hangout discussion, I would check messages occasionally.