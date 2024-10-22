# Creat Walllets

Được sử dụng để tạo ví cho nhiều blockchain khác nhau, bao gồm Ethereum (EVM), Sui, Solana và Aptos. Ứng dụng sử dụng BIP39 và BIP44 để tạo địa chỉ và khóa riêng.

## Tính năng:

- Tạo nhiều ví cho EVM, Sui, Solana và Aptos bằng một mã ghi nhớ duy nhất.
- Xuất dữ liệu ví sang định dạng Excel hoặc CSV.
- Lưu trữ địa chỉ, khóa riêng và mã ghi nhớ trong tệp văn bản.

## Data:

- **EVM Address**
- **Sui Address**
- **Solana Address**
- **Aptos Address**
- **Private Key EVM**
- **Private Key Sui**
- **Private Key Solana**
- **Mnemonic**

## Module:

- Python 3.7 or later
- `pip` (Python package installer)

## Installation

1. Open cmd or Shell, then run the command:
```bash
git clone https://github.com/thog9/Creat-wallets.git
cd Creat-wallets
```
2. Install Module: `requirements.txt`.
```bash
pip install -r requirements.txt
```
3. Run.
```bash
python bot.py
```