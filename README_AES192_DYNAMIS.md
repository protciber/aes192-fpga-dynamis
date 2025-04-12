
# AES-192 Cryptographic Core (Verilog)

This repository contains a full implementation of the AES-192 encryption algorithm in Verilog, developed for academic research at FEEC - DYNAMIS.

## 🔧 Features

- Fully modular structure: Datapath, Control Unit, Key Expander
- 12-round AES-192 compliant with [FIPS 197](https://nvlpubs.nist.gov/nistpubs/FIPS/NIST.FIPS.197.pdf)
- Integrated testbench in Verilog and C
- Simulatable in Vivado and Verilator

## 📁 File Structure

- `aes_core_AES192.v`: Top-level module
- `aes_core_control_unit_AES192.v`: FSM control
- `aes_core_datapath_AES192.v`: Data transformation logic
- `key_expander_AES192.v`: Key schedule logic
- `aes192_tb.v`: Verilog testbench with FIPS vector
- `testbench_aes192_fips.c`: C-based software testbench

## ▶️ Simulation

### Using Vivado

```tcl
source vivado_project.tcl
```

### Using Verilator

```bash
make
```

## 🧪 Test Vector (FIPS)

- **Key**: `8e73b0f7da0e6452c810f32b809079e562f8ead2522c6b7b`
- **Plaintext**: `6bc1bee22e409f96e93d7e117393172a`
- **Expected Ciphertext**: `bd334f1d6e45f25ff712a214571fa5cc`

## 📄 Documentation

Please refer to `Documentacao_Tecnica_AES192_DYNAMIS.pdf` for the full technical report.

## 📚 License

Academic use only. Developed for postgraduate research at DYNAMIS.
