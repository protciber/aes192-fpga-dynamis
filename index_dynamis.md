
# AES-192 FPGA Core

> Projeto desenvolvido por **CYBER-DYNAMIS**, baseado no padrão [FIPS 197](https://nvlpubs.nist.gov/nistpubs/FIPS/NIST.FIPS.197.pdf)

---

## 🔐 Sobre o Projeto

Este núcleo implementa o algoritmo **AES-192 (Advanced Encryption Standard)** com foco em aplicações embarcadas e sistemas de segurança digital.

Foi desenvolvido em **Verilog HDL**, validado com vetores FIPS e projetado para operação em **FPGAs Xilinx**, como Artix-7 e Zynq.

---

## ⚙️ Arquitetura

O projeto é composto por:

- **Datapath**: Transformações criptográficas (SubBytes, MixColumns, ShiftRows)
- **Unidade de Controle**: Sequência das rodadas (12)
- **Expansor de Chave AES-192**: Geração das subchaves a partir da chave de 192 bits

---

## 🧪 Validação

Testes com vetor FIPS oficial:

- 🔑 Key: `8e73b0f7da0e6452c810f32b809079e562f8ead2522c6b7b`
- 🧾 Plaintext: `6bc1bee22e409f96e93d7e117393172a`
- ✅ Ciphertext Esperado: `bd334f1d6e45f25ff712a214571fa5cc`

---

## 📄 Documentação

- [Documentação Técnica (PDF)](docs/Documentacao_Tecnica_AES192_DYNAMIS.pdf)
- [README.md](docs/README.md)

---

## 📦 Repositório

Acesse o código-fonte completo, testbenches e scripts no GitHub:

👉 **https://github.com/seu-usuario/aes192-fpga-unicamp**

---

## 🖼️ Visual do Projeto

![Banner AES-192](docs/banner.png)

---

## © CYBER-DYNAMIS • 2024
